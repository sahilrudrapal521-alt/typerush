
# ⌨️ TypeRush — Typing Speed Challenge

A modern, interactive typing speed test website built using HTML, CSS, and JavaScript.

Test your typing speed, improve your accuracy, and challenge yourself to beat your personal best!

---

## 🌟 Features

- **Multiple Time Modes:** Choose between 15, 30, and 60-second typing challenges.
- **Live WPM:** Track your words per minute in real time.
- **Accuracy Tracking:** Monitor your typing accuracy while practicing.
- **Error Detection:** Incorrect characters are highlighted in red.
- **Character Highlighting:** Correct characters appear in green.
- **Countdown Timer:** A live timer tracks the remaining test duration.
- **Progress Bar:** See your typing progress throughout the test.
- **Personal Best:** Your highest WPM score is saved automatically.
- **Random Passages:** Practice with different text passages.
- **Results Screen:** View your final speed, accuracy, errors, and characters typed.
- **Responsive Design:** Works on desktop, laptop, tablet, and mobile devices.
- **Dark UI:** A modern dark interface with neon green accents.

---

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| HTML5 | Website structure |
| CSS3 | Styling, animations, and responsive design |
| JavaScript | Typing logic, timer, and score calculation |
| Local Storage | Saving personal best |

---

## 📂 Project Structure

```text
TypeRush/
│
└── index.html
```

The entire website is contained in a single HTML file, including its CSS and JavaScript.

---

## 🚀 Getting Started

### 1. Download or Clone the Project

Clone the repository:

```bash
git clone https://github.com/your-username/typerush.git
```

### 2. Open the Project

Navigate to the project folder:

```bash
cd typerush
```

### 3. Run the Website

Open `index.html` in your preferred web browser.

No installation, build tools, or external dependencies are required.

---

## 🎮 How to Play

1. Open the TypeRush website.
2. Select a typing duration: 15, 30, or 60 seconds.
3. Click **Start Typing** or begin typing the displayed passage.
4. Type the text as accurately as possible.
5. Watch your WPM and accuracy update in real time.
6. Complete the test before the timer reaches zero.
7. View your final results and try to beat your personal best!

---

## ⌨️ Keyboard Shortcuts

| Key | Action |
|---|---|
| `Enter` | Start the typing test |
| `Tab` | Restart the test |

---

## 📊 How WPM Is Calculated

WPM stands for **Words Per Minute**.

The website uses the standard typing-test convention of counting every 5 correctly typed characters as one word.

```text
WPM = (Correct Characters / 5) / Time in Minutes
```

For example:

If you type 250 correct characters in 1 minute:

```text
WPM = (250 / 5) / 1
WPM = 50
```

Your typing speed is **50 WPM**.

### Accuracy

Accuracy measures the percentage of correctly typed characters.

```text
Accuracy = (Correct Characters / Total Typed Characters) × 100
```

---

## 💾 Personal Best

TypeRush uses the browser's Local Storage to save your highest WPM score.

Your personal best remains saved when you refresh or reopen the website in the same browser.

No account or database is required.

---

## 🎨 Customization

You can customize TypeRush by:

- Changing the colors in the CSS `:root` section.
- Adding your own typing passages.
- Modifying the available test durations.
- Changing the fonts and layout.
- Adding new statistics or game modes.

---

## 🔮 Future Improvements

Possible future features include:

- Multiplayer typing competitions
- Global leaderboard
- User profiles and accounts
- More typing passages
- Custom text mode
- Difficulty levels
- Sound effects
- Achievements and badges
- Typing history and performance charts
- Daily typing challenges

---

## 📸 Preview

TypeRush features a dark, modern interface with:

- Neon green highlights
- Minimal dashboard design
- Live typing statistics
- Interactive typing area
- Animated progress indicators

---

## 📄 License

This project is open source and available for personal and educational use.

---

## 👨‍💻 Author

Created with ❤️ using HTML, CSS, and JavaScript.

**TypeRush — Find your flow.**
