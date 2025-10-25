🧮 Basic Calculator
📘 Project Overview

The Basic Calculator is a simple web-based application that allows users to perform basic arithmetic operations such as addition, subtraction, multiplication, and division.
It is built using HTML, CSS, and JavaScript, making it lightweight, fast, and easy to use.

This project is ideal for beginners who are learning web development fundamentals and want to understand how JavaScript can be used to handle user interactions dynamically.

🚀 Features

-> Perform basic arithmetic operations (+, -, *, /)

-> Clear (AC) button to reset the display

-> Delete (DE) button to remove the last digit

-> Support for decimal inputs

-> Responsive layout using simple CSS

-> User-friendly and interactive interface

🛠️ Technologies Used

-> HTML – Structure of the calculator interface

> CSS – Styling and layout design

-> JavaScript – Handles calculator logic and user input

📂 Project Structure
calculator/
│
├── index.html       # Main HTML file containing the calculator UI
├── style.css        # CSS file for styling the calculator
└── README.md        # Project documentation (this file)

💡 How It Works

-> Each calculator button is an HTML <input type="button">.

-> When a user clicks a button, the corresponding value is appended to the input field (display).

-> The AC button clears the entire display.

-> The DE button deletes the last character using .slice(0, -1).

-> The = button uses JavaScript’s eval() function to evaluate the mathematical expression entered in the display.

-> The result is then shown in the display field.

⚙️ How to Run

-> Download or clone the repository:

-> git clone https://github.com/your-username/basic-calculator.git


-> Open the index.html file in any modern web browser.

-> Start performing calculations!

🧩 Example

Input: 12 + 3 * 4
Output: 24

⚠️ Notes

-> This project uses the eval() function, which can be unsafe for untrusted inputs.
-> It’s suitable for small personal or educational projects but should be avoided in production environments.

-> You can extend the project by adding:

-> Keyboard input support

-> Scientific calculator functions (√, %, sin, cos, etc.)

-> Improved UI with animations

👨‍💻 Author

Kowshik Aravind
A beginner web developer passionate about learning and creating simple, interactive web applications.
