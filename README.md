# BMICalculator
A Java BMI Calculator App
Here's a clean, copy-and-paste-ready `README.md` file for your **BMI Calculator** Java project:

---

```markdown
# 🧍 Adult BMI Calculator (Java)

This is a simple Java console application that calculates the **Body Mass Index (BMI)** for adults based on height (in feet and inches) and weight (in pounds). It also classifies the result into standard BMI categories.

### 💡 What It Does

The program:
- Prompts the user to enter:
  - Height in **feet** and **inches**
  - Weight in **pounds**
- Converts the total height into inches and applies the standard U.S. BMI formula:
  ```
  BMI = (weight in pounds / (height in inches)^2) × 703
  ```
- Determines the BMI category:
  - Underweight: BMI < 18.5
  - Healthy Weight: 18.5 ≤ BMI < 25
  - Overweight: 25 ≤ BMI < 30
  - Obesity: BMI ≥ 30
- Displays the BMI, category, and the user’s input for reference.

---

### 🛠 How to Run

1. Copy the code from `BMICalculator.java` into your Java IDE (Eclipse, IntelliJ, VS Code, etc.).
2. Compile and run the program.
3. Follow the prompts to enter height and weight.

---

### ✅ Example Output

```
Adult BMI Calculator
--------------------
Enter Your Height In Feet:  5
Enter Your Remaining Inches:  7
Enter Your Weight In Pounds:  160

Calculated Results
--------------------
BMI: 25.1
BMI CATEGORY: Overweight

Information Entered
---------------------
Height: 5 feet 7 inches
Weight: 160.0 pounds
```

---

### 📁 File Structure

```
project-root/
└── src/
    └── day3/
        └── BMICalculator.java
```

---

### 📄 Requirements

- Java 8 or later
- Any Java IDE or command-line compiler

---

### 🧠 Notes

This project is great for learning:
- User input using `Scanner`
- Arithmetic calculations
- BMI health classifications
- Conditional logic (`if-else`)
- Console output formatting using `System.out.printf()`

