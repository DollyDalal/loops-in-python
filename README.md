# 📘 STUDY OF CONDITIONAL STATEMENTS IN PYTHON 🐍

## 🎯 Aim
To study and understand **conditional statements in Python** and their role in decision-making.

## 📖 Introduction
Conditional statements in Python are used to **execute different blocks of code based on conditions**.
The condition is evaluated as ✅ True or ❌ False, and the program works accordingly.

## 📚 Types of Conditional Statements in Python

### 1️⃣ if Statement
The `if` statement executes a block of code **only when the condition is true**.

🔹 Syntax:
if condition:
    statement

🔹 Example:
a = 10
if a > 5:
    print("a is greater than 5")

---

### 2️⃣ if-else Statement
The `if-else` statement executes **one block if the condition is true** and **another block if false**.

🔹 Syntax:
if condition:
    statement
else:
    statement

🔹 Example:
num = 6
if num % 2 == 0:
    print("Even number")
else:
    print("Odd number")

---

### 3️⃣ if-elif-else Statement
Used when **multiple conditions** need to be checked.

🔹 Syntax:
if condition1:
    statement
elif condition2:
    statement
else:
    statement

🔹 Example:
marks = 80
if marks >= 90:
    print("Grade A 🏆")
elif marks >= 75:
    print("Grade B 👍")
else:
    print("Grade C 📘")

---

### 4️⃣ Nested if Statement
An `if` statement written **inside another if statement**.

🔹 Example:
num = 8
if num > 0:
    if num % 2 == 0:
        print("Positive Even Number ✅")

---

## 🔁 Flow of Execution 🔄
1️⃣ Condition is checked  
2️⃣ If condition is **True ✅**, code inside `if` runs  
3️⃣ If condition is **False ❌**, control moves to `else` or next `elif`

---

## 🛠 Applications 💡
✔️ Even / Odd checking  
✔️ Grade calculation  
✔️ Income tax calculation  
✔️ Salary calculation  
✔️ Decision-making programs  

---

## 🧾 Conclusion 📝
Conditional statements help in **making logical decisions** in Python programs.
They make programs **flexible, efficient, and easy to understand** 🚀
