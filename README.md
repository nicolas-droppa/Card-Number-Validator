# 💳 Card Number Validator

Welcome to the **Card Number Validator**! This is a simple GUI-based application created using Tkinter, which allows users to validate credit card numbers. The validation is based on the Luhn algorithm.

## 📋 Table of Contents

- [📝 Introduction](#introduction)
- [🎲 Features](#features)
- [💻 Installation](#installation)
- [🚀 How to Use](#how-to-use)
- [🔍 Validation Algorithm](#validation-algorithm)
- [📷 Screenshots](#screenshots)

---

## 📝 Introduction

**Card Number Validator** is a Tkinter-based GUI application that helps users validate credit card numbers by using the Luhn algorithm. This application accepts card numbers from the user and determines if the card is valid or not. It also clears the card number input, displays random card information, and shows a real-time validation result.

---

## 🎲 Features

- **🎨 Intuitive UI**: Simple and user-friendly interface built with Tkinter.
- **✅ Real-time Validation**: Displays the validation result ("Valid" or "Invalid") based on the Luhn algorithm.
- **🔢 Random Card Data**: Generates random names, expiration dates, and card types for testing purposes.
- **🖱️ Interactive Buttons**: Includes buttons for validating and clearing the card number input.
- **💡 Dynamic Feedback**: Provides immediate feedback on the validity of the card number with color-coded indicators.

---

## 💻 Installation

To run **Card Number Validator**, follow these steps:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/nicolas-droppa/Card-Number-Validator.git
   cd Card-Number-Validator
   ```
   
2. **Install the required dependencies**:
   Ensure you have Python and Tkinter installed on your machine. Tkinter comes pre-installed with Python in most distributions. If it's not installed, you can add it with:
   On Linux (Ubuntu/Debian):
   ```bash
   sudo apt-get install python3-tk
   ```
   On Windows, Tkinter is included with Python by default, so no additional installation should be needed.

3. **Run the application**:
   Once the dependencies are installed, run the application by executing the following command:
   ```bash
   python card_number_validator.py
   ```

---

## 🚀 How to Use

1. **Enter a card number**: Type a card number into the input field.
2. **Click 'Validate'**: The app will instantly check if the card number is valid or invalid.
3. **Clear the input**: You can reset the input by clicking the "Clear" button.
4. **Random data generation**: Random names, expiration dates, and card types are generated to simulate a more dynamic interface.

---

## 🔍 Validation Algorithm

The validation process is based on the **Luhn algorithm**. Here’s a brief overview:

1. Double every second digit from the right.
2. If doubling results in a number greater than 9, subtract 9 from it.
3. Sum all the adjusted digits.
4. If the total sum is divisible by 10, the card number is valid.

---

## 📷 Screenshots

![Card Validator Screenshot](https://github.com/user-attachments/assets/card_validator_screenshot.png)

---

Thank you for trying out the **Card Number Validator**! 🎉
