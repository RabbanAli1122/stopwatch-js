# 🧾 Stopwatch

[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)  
[![HTML](https://img.shields.io/badge/HTML5-orange.svg)](https://developer.mozilla.org/en-US/docs/Web/HTML)  
[![CSS](https://img.shields.io/badge/CSS3-blue.svg)](https://developer.mozilla.org/en-US/docs/Web/CSS)  
[![JavaScript](https://img.shields.io/badge/JavaScript-ES6-yellow.svg)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)

## ✅ Features

1. Captures time in **milliseconds, seconds, and minutes**
2. Start, Stop, and Reset functionality
3. Responsive and clean user interface
4. Aesthetic gradient background and styled buttons

## 🛠️ How It Works

```javascript
// Start timer with setInterval
timerId = setInterval(startTimer, 10);

// Clear the timer
clearInterval(timerId);

// Display formatted time
timerDisplay.innerHTML = `${minsString} : ${secsString} : ${msecString}`;
```


## 📋 Requirements
- Any modern browser (Chrome, Firefox, Safari, etc.)
- Basic knowledge of HTML, CSS, and JavaScript (for edits)


## 📂 Files in Repository
1. ```index.html``` – Contains the structure of the stopwatch
2. ```style.css``` – Styles the stopwatch UI
3. ```script.js``` – Controls stopwatch logic (start, stop, reset)
4. ```Readme.md``` - Contains information related to repo
5. ```LICENCE``` - MIT-Licence

   
## 🚀 How to Run

```
# Clone the repository
git clone https://github.com/username/stopwatch.git
cd stopwatch

# Open index.html in your browser
start index.html    # For Windows
open index.html     # For macOS
```


## 🧠 Lessons Learned
1. Working with JavaScript timers (setInterval, clearInterval)
2. Formatting time display with leading zeroes
3. Improving CSS aesthetics with shadows and gradients

## 🖼️ Demo
- [Github Pages](https://rabbanali1122.github.io/stopwatch-js/)


## 📸 Screenshots
### Stopwatch UI:
<img width="658" alt="Screenshot 1" src="https://github.com/user-attachments/assets/53b24eb9-d6da-435f-a2d4-b1516b7d24a6" /> <br> <img width="1015" alt="Screenshot 2" src="https://github.com/user-attachments/assets/65f93bca-730e-4093-8f0a-dbfd7b63fdaa" />


## 💻 Technologies Used
- HTML5
- CSS3
- JavaScript (ES6)

## 🙏 Acknowledgements
Thanks to open-source tutorials and online resources for design and logic inspiration.

## 📄 License
This project is licensed under the MIT License. See the LICENSE file for full details.
