# Quiz Lah!

**Quiz Lah!** is a responsive, browser-based quiz app designed for students to test their knowledge in a fun and interactive way. It supports multiple-choice and open-ended questions, allows teachers to host quizzes via Google Sheets, and provides automatic result summaries and optional submissions.

## 🚀 Features

- No login or data collection — all in-browser.
- Load quizzes from:
  - A list of built-in quizzes (Google Sheets-based).
  - A custom Quiz ID (Google Sheet ID).
- Multiple question types: MCQ and typing answers.
- Timer support and progress tracking.
- Automatic scoring and result summary.
- Review questions and explanations after the quiz.
- Optional submission of results to teachers using a Submission ID.
- Supports screenshots for saving quiz results.
- Visitor counter (GoatCounter integration).

## 🌐 Live Demo

[🔗 Try it now](https://linsnotes.com/quiz)  

## 📁 How to Use

1. **Open the app in your browser**.
2. Enter your name.
3. Choose a built-in quiz OR enter a custom Quiz ID provided by your teacher.
4. (Optional) Enter a Submission ID to send your results to your teacher.
5. Complete the quiz and view your results.
6. Review answers and download a screenshot if needed.

## 🧑‍🏫 For Teachers

- Prepare your quiz in a Google Sheet.
- Share the **sheet ID** with students.
- Optionally, set up a **Google Apps Script Web App** to collect submissions (used as Submission ID).

## 📊 Google Sheets Format

| No. | Question | Answer | Type | MCQ Options | Reading Material | Hint | Explanation | TimeLimit |
|-----|----------|--------|------|-------------|------------------|------|-------------|-----------|

- `Type`: `"MCQ"` or `"Text"`
- `MCQ Options`: Separate options using `#`
- `TimeLimit`: Optional (applies to the whole quiz)

## 📦 Tech Stack

- HTML/CSS/JavaScript
- [XLSX.js](https://github.com/SheetJS/sheetjs)
- [html2canvas](https://html2canvas.hertzen.com/)
- [Font Awesome](https://fontawesome.com/)
- [GoatCounter](https://www.goatcounter.com/) (for visitor tracking)

## 🛠 Setup for Local Use

1. Clone the repo:
   ```bash
   git clone https://github.com/yourusername/quiz-lah.git
   cd quiz-lah
   ```

2. Open `index.html` in a browser.

## 📄 License
[MIT License](LICENSE)



