# 💰 Income Tax Calculator

A simple **Income Tax Calculator** built using **HTML, CSS, and JavaScript**.

This project allows users to enter their annual income and calculates the estimated total tax based on the tax slabs implemented in the JavaScript program.

## 🚀 Features

* 💵 Enter your annual income
* 🧮 Automatically calculates total tax
* 📊 Uses different income tax slabs
* ⚡ Instant result without reloading the page
* 🔄 Form automatically resets after submission
* 📱 Simple and beginner-friendly interface

## 🛠️ Technologies Used

* **HTML** – Structure of the webpage
* **CSS** – Styling and design
* **JavaScript** – Tax calculation and form handling

## 📋 Tax Slabs Used

| Income Range            | Tax Calculation |
| ----------------------- | --------------- |
| Up to ₹12,00,000        | 0%              |
| ₹12,00,001 – ₹16,00,000 | 15%             |
| ₹16,00,001 – ₹20,00,000 | 20%             |
| ₹20,00,001 – ₹24,00,000 | 25%             |
| Above ₹24,00,000        | 30%             |

> **Note:** The tax slabs in this project are based on the logic implemented in the JavaScript code. This project is for learning/programming purposes and should not be treated as official tax advice.

## 📂 Project Structure

```text
Income-Tax-Calculator/
│
├── index.html
├── style.css
├── script.js
└── README.md
```

## ⚙️ How It Works

1. The user enters their income.
2. JavaScript gets the value from the input field.
3. The income is converted into a number using `parseInt()`.
4. The program checks which tax slab the income belongs to.
5. The total tax is calculated.
6. The result is displayed on the webpage.
7. The form is reset after submission.

### Example

If the user enters:

```text
Income = ₹18,00,000
```

The program calculates the tax according to the applicable slabs and displays:

```text
Total Tax: ₹120000
```

## 🧠 JavaScript Concepts Practiced

This project helped me practice:

* `querySelector()`
* `addEventListener()`
* Form submission
* `preventDefault()`
* Variables
* `if...else if...else`
* Arithmetic operators
* `parseInt()`
* Template literals
* DOM manipulation
* `textContent`
* `form.reset()`

## ▶️ How to Run

1. Clone this repository:

```bash
git clone YOUR_REPOSITORY_URL
```

2. Open the project folder.

3. Open `index.html` in your browser.

4. Enter your income and click the submit button.

## 🎯 Learning Purpose

This project was created to practice **JavaScript DOM manipulation, event handling, conditional statements, and basic logic** while building a practical mini-project.

## 🔮 Future Improvements

* Add a better responsive UI
* Add detailed tax breakdown
* Add monthly income option
* Add tax-saving deductions
* Add validation for invalid income
* Add reset button
* Add tax calculation history
* Improve accessibility

## 👨‍💻 Author

**Suraj Kumar Singh**

This project is part of my journey of learning **HTML, CSS, and JavaScript**.
