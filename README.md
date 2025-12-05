# 💸 Simple Java Loan Calculator

<!-- Badges -->
[![Java Version](https://img.shields.io/badge/Java-8%2B-blue.svg)](#)  
[![Project Status](https://img.shields.io/badge/status-complete-success.svg)](#)  

## 📖 Table of Contents  
- [Description](#description)  
- [Features](#features)  
- [Getting Started](#getting-started)  
  - [Prerequisites](#prerequisites)  
  - [Compile & Run](#compile--run)  
- [Usage Example](#usage-example)  
- [Project Structure](#project-structure)  
- [Potential Improvements](#potential-improvements)  
- [License / Notes](#license--notes)  

---

## Description  
A simple command-line Java application that calculates the monthly payment for a loan, based on user input of principal amount, annual interest rate, and loan term (in years). It demonstrates basic Java skills: user input handling, arithmetic calculations, and formatted output.  

## Features  
- ✅ Calculates monthly payment for a loan using the standard amortization formula  
- ✅ Handles zero-interest loans (i.e. when rate = 0) gracefully  
- ✅ No external dependencies — pure Java, console-based  
- ✅ Simple and clear code — ideal for learning and small-scale demonstration  

## Getting Started

### Prerequisites  
- Java Development Kit (JDK) 8 or higher  
- A terminal / command-line environment  

### Compile & Run  
From the root directory (where the `VariableDeclaration` folder resides), run:  
```bash
javac VariableDeclaration/SimpleLoanCalculator.java
java VariableDeclaration.SimpleLoanCalculator
````

Then follow the prompts to enter the loan amount, annual interest rate, and term in years.

---

## Usage Example

```
Loan amount: 
> 10000  
Annual interest rate (%): 
> 5  
Term (years): 
> 3  

Monthly payment: 299.71
```

---

## Project Structure

```
VariableDeclaration/
  └─ SimpleLoanCalculator.java   ← Main program
```

---

## Potential Improvements / Next Steps

* Format output so that decimals are always shown with two decimal places (already done with `printf`, but could be extended with currency formatting)
* Add input validation (e.g. disallow negative values or non-numeric input)
* Extend to support different payment frequencies (e.g. monthly, bi-weekly) or extra payments
* Add feature to show total payment amount and total interest paid over the loan term
* Optionally convert to a small GUI or web-based tool for easier use

---

## License / Notes

This is a simple educational / demonstration project — feel free to use, modify, or extend it as you like.
