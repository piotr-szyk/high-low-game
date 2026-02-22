
# 🎮 High-Low Number Guessing Game

A logic-based interactive guessing game built with Vanilla JavaScript. This project was designed to practice core programming patterns like loops, conditional logic, and state management.

![Difficulty: Easy](https://img.shields.io/badge/Difficulty-Easy-brightgreen?style=for-the-badge)
![Topic: JavaScript Logic](https://img.shields.io/badge/Topic-JS_Logic-yellow?style=for-the-badge)

---

## 🎯 Project Goal
The objective is to guess a randomly generated number between **1 and 100** in the fewest attempts possible. The game provides real-time feedback (Higher or Lower) until the correct number is found.

## 🛠️ Technical Implementation
This project showcases the following JavaScript fundamentals:

* **Randomization:** Utilizing `Math.random()` and `Math.floor()` to generate dynamic target numbers.
* **Game Loops:** Implementing a `while` loop that persists until the user meets the win condition.
* **Input Handling:** Managing user interaction via `window.prompt()`, `window.alert()`, and `window.confirm()`.
* **Data Conversion:** Using `parseInt()` to sanitize string inputs into numbers for comparison.
* **Recursion:** Implementing a functional restart logic by allowing the function to call itself based on user confirmation.

## 🚀 How to Play
1. Open `index.html` in any modern web browser.
2. An alert will welcome you and the game will begin.
3. Enter a number between 1 and 100 in the prompt box.
4. Follow the "Too High" or "Too Low" hints.
5. Once you win, you'll see your total attempts and have the option to play again!

## 📂 Structure
- `index.html`: The entry point for the browser.
- `assets/js/script.js`: The "brain" containing the game logic.
- `assets/css/style.css`: Basic styling for a clean interface.
