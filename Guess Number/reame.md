# 🎯 Guess The Number Game

A fun JavaScript-based number guessing game where users try to guess a randomly generated number within a limited number of attempts.

## 🚀 Features

- Random number generation
- Sound effects for success and failure 🎵
- Responsive design (mobile + desktop)
- Score counter
- Hint for “too high” or “too low”

## 🕹️ How to Play

1. Enter your guess.
2. Click the "Check" button.
3. Get feedback if your guess is too high or too low.
4. Try to guess the correct number before you run out of attempts!

## 🔗 Live Demo

👉 [Play Now](https://techie-being.github.io/guess-the-number/)

Made with ❤️ by [Rakesh]

## 📁 Project Structure

<pre lang = "markdown"> ```
guess-the-number/
├── index.html
├── index.css
├── index.js
├── success.mp3
├── fail.mp3
└── readme.md
``` </pre>

---

## 🚀 How to Run Locally

1. Download or clone the repo.
2. Open `index.html` in your browser.
3. Play and enjoy!

---

## 🌐 How to Host This on GitHub

### 1. Create a GitHub Repository

- Go to [https://github.com](https://github.com)
- Click **New** and name your repo (e.g., `guess-number-game`)
- Set visibility to **Public**
- Click **Create repository**

---

### 2. Push Your Code to GitHub

If you already have the folder on your computer, open **VS Code** or **Command Line** in that project folder:

```bash
# Initialize Git (if not done)
git init

# Add the remote repo (change YOUR_USERNAME and repo name)
git remote add origin https://github.com/YOUR_USERNAME/guess-number-game.git

# Add all files
git add .

# Commit your code
git commit -m "Initial commit 🎯 Guess the Number Game"

# Push to GitHub (main branch)
git branch -M main
git push -u origin main