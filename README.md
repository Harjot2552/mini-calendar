# 📅 Mini Calendar

A simple and elegant **Mini Calendar** built using **HTML**, **CSS**, and **JavaScript**. This calendar displays the current date, day, month, and year.

## 🕒 Features
- Displays today's date with a clean and minimal design.
- Automatically updates to show the correct day, month, and year.

## 🗒 Preview
![Calendar Preview](https://harjotrocks.com/javascript/mini-calendar/)

## 🛠️ How to Use
1. Clone or download this repository.
2. Open `index.html` in any modern web browser.

## 📚 Code Explanation
### HTML Structure
The calendar layout has two sections: 
- **Left:** Displays the date and day.
- **Right:** Displays the month and year.
```html
<div class="calendar">
  <div class="left">
    <p id="date">01</p>
    <p id="day">Sunday</p>
  </div>
  <div class="right">
    <p id="month">January</p>
    <p id="year">2024</p>
  </div>
</div>
```

### JavaScript Logic
The script dynamically updates the calendar content using the `Date` object:
```javascript
const weekdays = ["Sunday", "Monday", "Tuesday", "Wednesday", "Thursday", "Friday", "Saturday"];
const allMonths = ["January", "February", "March", "April", "May", "June", "July", "August", "September", "October", "November", "December"];

let today = new Date();
date.innerHTML = (today.getDate() < 10 ? "0" : "") + today.getDate();
day.innerHTML = weekdays[today.getDay()];
month.innerHTML = allMonths[today.getMonth()];
year.innerHTML = today.getFullYear();
```

## ✨ Demo
Open `index.html` directly in your browser to see the mini calendar.

## 🌐 Technologies Used
- HTML5
- CSS3
- JavaScript ES6

## 🛠️ Setup Instructions
1. Clone the repository:
   ```bash
   git clone https://github.com/Harjot2552/mini-calendar.git
   ```
2. Navigate to the project directory and open `index.html`.

## ❤️ Contribution
Feel free to submit issues or pull requests to enhance this project.


