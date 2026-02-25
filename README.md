
# Single-File Web Calculator

A lightweight, fully functional calculator built in a single file using **HTML**, **JavaScript**, and **Strictly Inline CSS**. 

Because this project uses zero external stylesheets or dependencies, it is incredibly easy to drop into any existing project, email template, or environment where external files are restricted.

## 🚀 Features

- **Single File:** Everything (structure, styling, and logic) is contained in one `.html` file.
- **Strictly Inline CSS:** All styling is done using the `style=""` attribute. No `<style>` blocks or external `.css` files.
- **Modern UI:** Uses Flexbox for perfect button alignment, along with box-shadows and rounded corners for a modern, tactile look.
- **Smart Logic:** Includes error handling for invalid equations (displays "Error" instead of breaking) and prevents infinitely long decimal results.
- **Color-Coded Buttons:** Easy-to-read interface (Red for clear, Yellow for operators, Green for equals).

## 🛠️ Technologies Used

- **HTML5** (Structure)
- **Inline CSS** (Styling & Layout)
- **Vanilla JavaScript** (Calculation logic)

## 💻 How to Use

1. Create a new file on your computer and name it `calculator.html`.
2. Copy the provided HTML code and paste it into the file.
3. Save the file.
4. Double-click `calculator.html` to open it in your default web browser (Chrome, Firefox, Safari, Edge, etc.).

*No server, Node.js, or build tools required!*

## 🧠 Code Overview

### Layout (Flexbox)
The calculator grid is achieved using inline flexbox rules:
```html
<div style="display: flex; flex-wrap: wrap; justify-content: space-between;">
```

### Logic (JavaScript)
The math is handled by three simple functions at the bottom of the file:
- `appendToDisplay(value)`: Adds the clicked number or operator to the screen.
- `clearDisplay()`: Wipes the screen entirely.
- `calculateResult()`: Evaluates the string on the screen, rounds long decimals, and catches syntax errors.
