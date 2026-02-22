# 🎮 High-Low Number Guessing Game

A logic-based interactive guessing game built with Vanilla JavaScript. This project serves as a foundational exercise in managing game states, implementing loops, and handling user input.

![Difficulty: Easy](https://img.shields.io/badge/Difficulty-Easy-brightgreen?style=for-the-badge)
![Topic: JavaScript Logic](https://img.shields.io/badge/Topic-JS_Logic-yellow?style=for-the-badge)
![Tech: HTML/CSS/JS](https://img.shields.io/badge/Tech-Vanilla_JS-orange?style=for-the-badge)

---

## 🎯 Project Goal
The objective is to guess a randomly generated number between **1 and 100** in the fewest attempts possible. The game provides real-time feedback (Higher or Lower) until the correct number is found.

## 🛠️ Technical Implementation
This project showcases several core JavaScript programming patterns:

* **Randomization:** Utilizing `Math.random()` and `Math.floor()` to generate dynamic target numbers within a specific range.
* **Game Loops:** Implementing a `while` loop that persists until the user satisfies the win condition.
* **Input Handling:** Managing user interaction via synchronous window methods: `window.prompt()`, `window.alert()`, and `window.confirm()`.
* **Data Sanitization:** Using `parseInt()` to convert string-based prompt inputs into integers for mathematical comparison.
* **Recursive Logic:** Utilizing function recursion to allow the player to restart the game without a browser refresh.

## 🚀 How to Play
1.  Open `index.html` in any modern web browser.
2.  An alert will welcome you and the game will begin automatically.
3.  Enter a number between 1 and 100 in the prompt box.
4.  Follow the **"Too High"** or **"Too Low"** hints provided.
5.  Once you win, the game will display your total attempts and offer a choice to play again.

## 📂 Project Structure
- `index.html`: The entry point for the browser.
- `script.js`: The "brain" containing the core game logic and loop.
- `style.css`: Basic CSS for layout and typography.
