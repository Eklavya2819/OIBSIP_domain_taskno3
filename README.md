# Pro Temperature Converter

## Overview

**Pro Temperature Converter** is a simple web application that converts temperature values between **Celsius and Fahrenheit**. The application is built using **HTML, CSS, and JavaScript** and provides a modern dark-themed interface with an easy-to-use conversion tool.

Users can enter a temperature value, select the conversion type, and instantly view the converted result.

---

## Features

* Convert **Celsius to Fahrenheit**
* Convert **Fahrenheit to Celsius**
* Clean **dark theme user interface**
* **Input validation** for numeric values
* **Interactive button with hover effect**
* Result displayed in a **styled result box**

---

## Technologies Used

* **HTML5** – Structure of the web application
* **CSS3** – Styling and layout design
* **JavaScript** – Temperature conversion logic

---

## Project Structure

```id="projstruct1"
temperature-converter/
│
├── index.html
└── README.md
```

---

## How the Application Works

### 1. Input Temperature

The user enters a temperature value in the **input field**.

### 2. Select Conversion Type

The dropdown menu allows users to choose:

* **Celsius → Fahrenheit**
* **Fahrenheit → Celsius**

### 3. Convert Temperature

When the **Convert Now** button is clicked:

* JavaScript reads the entered value
* It checks if the input is a valid number
* The appropriate conversion formula is applied

### 4. Display Result

The converted temperature is displayed inside the **result box**.

---

## Temperature Conversion Formulas

### Celsius to Fahrenheit

```
F = (C × 9/5) + 32
```

### Fahrenheit to Celsius

```
C = (F − 32) × 5/9
```

---

## How to Run the Project

1. Copy the code into a file.
2. Save the file as **index.html**.
3. Open the file in any web browser (Chrome, Edge, Firefox).
4. Enter a temperature value and click **Convert Now** to see the result.

---

## Example

Input:

```
Temperature: 25
Conversion: Celsius → Fahrenheit
```

Output:

```
77.00 °F
```

---

## Possible Improvements

* Add **Kelvin conversion**
* Add **real-time conversion without button click**
* Add **error messages with better UI feedback**
* Make the layout **fully responsive for mobile devices**

---
