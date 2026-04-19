# Random Password Generator
password generator

🔐 Password Generator
A sleek, high-security random password generator built with HTML, CSS, and Vanilla JavaScript. This tool generates two unique, complex passwords simultaneously to help users secure their digital lives.

🚀 Live Demo
[https://rosslergkboquiren.github.io/Random-Password-Generator/]

✨ Features
One-Click Generation: Instantly creates two unique passwords.

High Complexity: Uses a wide array of symbols, numbers, and upper/lowercase letters.

Modern UI: A clean, dark-themed interface built with a mobile-first approach.

Monospace Clarity: Passwords are displayed in monospace font to easily distinguish between similar characters like O and 0 or l and 1.

🛠️ Built With
HTML5 – Semantic structure and layout.

CSS3 – Custom styling with Flexbox and a modern dark-mode aesthetic.

JavaScript (ES6) – Logic for character randomization and DOM manipulation.

Gemini AI – Utilized for code refactoring, logic troubleshooting, and UI/UX design consultation.

📖 How to Use
Open index.html in your browser.

Click the "Generate Passwords" button.

Two random 15-character passwords will appear in the green boxes below.

To get new ones, simply click the button again—the previous passwords will clear automatically.

💻 Code Highlights
To ensure the generator is truly random, the app pulls from a comprehensive array of 91 distinct characters using the Math.random() method:

JavaScript

// Example of the randomization logic
passwordOne += characters[Math.floor(Math.random() * characters.length)];