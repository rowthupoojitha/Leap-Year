# Java Leap Year Checker

A simple Java program that checks whether a given year is a **Leap Year**.

## 📌 What is a Leap Year?

A leap year is a year that contains **366 days** instead of the normal 365 days.

A year is a leap year if:

```text
1. It is divisible by 400
OR
2. It is divisible by 4 but not divisible by 100
```

### Examples

```text
2024 → Leap Year
2000 → Leap Year
2023 → Not a Leap Year
1900 → Not a Leap Year
```

## 📂 Project Structure

```text
java-leap-year/
├── .gitignore
├── LeapYear.java
└── README.md
```

## 💻 Program

The program accepts a year from the user and checks whether it satisfies the leap year conditions.

### Logic

```text
If year % 400 == 0
    → Leap Year

Else if year % 4 == 0 AND year % 100 != 0
    → Leap Year

Otherwise
    → Not a Leap Year
```

## ▶️ How to Run

### Step 1: Check Java

```bash
java --version
```

### Step 2: Check Java Compiler

```bash
javac --version
```

### Step 3: Compile

```bash
javac LeapYear.java
```

### Step 4: Run

```bash
java LeapYear
```

## 📊 Sample Output

### Example 1 — Leap Year

```text
Enter a year: 2024
2024 is a Leap Year.
```

### Example 2 — Not a Leap Year

```text
Enter a year: 2023
2023 is not a Leap Year.
```

### Example 3 — Century Year

```text
Enter a year: 1900
1900 is not a Leap Year.
```

### Example 4 — Divisible by 400

```text
Enter a year: 2000
2000 is a Leap Year.
```

## 🧠 Concepts Used

* Java
* Scanner
* User input
* Variables
* If-else statement
* Logical OR operator `||`
* Logical AND operator `&&`
* Modulus operator `%`
* Conditional statements

## ⏱️ Complexity

**Time Complexity:** `O(1)`

**Space Complexity:** `O(1)`

The program performs a fixed number of arithmetic and logical operations.

## 🚀 Future Improvements

* Check multiple years
* Print all leap years within a range
* Create a method for leap year checking
* Create a menu-driven calendar application
* Build a simple GUI-based leap year checker

## 🛠️ Technologies

* Java
* Git
* GitHub

## 👨‍💻 Author

**Your Name**

GitHub: `https://github.com/your-username`

---

⭐ If you found this project useful, consider giving the repository a star!

```
```