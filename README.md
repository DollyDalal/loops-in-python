# 📘 STUDY OF CONDITIONAL STATEMENTS IN PYTHON 🐍

## 🎯 Aim
To study, understand, and implement **conditional statements in Python** and learn how decision-making is performed in Python programs.

---

## 📖 Theory 📚
Conditional statements are used in Python to **control the flow of execution** of a program.
They allow the program to take **decisions** based on certain conditions.

A condition is an **expression** that evaluates to either:
- ✅ True  
- ❌ False  

Depending on the result of the condition, the corresponding block of code is executed.
Conditional statements make programs **dynamic, logical, and interactive**.

Python uses **indentation** instead of brackets `{ }` to define blocks of code.
Proper indentation is very important while using conditional statements.

---

## 📚 Types of Conditional Statements in Python

### 1️⃣ if Statement
The `if` statement is used to execute a block of code **only when the given condition is true**.
If the condition is false, the code inside the `if` block is skipped.

🔹 Syntax:
if condition:
    statement

🔹 Example:
a = 10
if a > 5:
    print("a is greater than 5")

---

### 2️⃣ if-else Statement
The `if-else` statement is used when there are **two possible outcomes**.
One block executes if the condition is true, and the other executes if the condition is false.

🔹 Syntax:
if condition:
    statement
else:
    statement

🔹 Example:
num = 6
if num % 2 == 0:
    print("Even number 🔢")
else:
    print("Odd number 🔢")

---

### 3️⃣ if-elif-else Statement
The `if-elif-else` statement is used when **multiple conditions** need to be checked.
Python checks conditions from top to bottom and executes the **first true condition**.

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
A nested `if` statement means an `if` statement written **inside another if statement**.
It is used when a condition depends on another condition.

🔹 Example:
num = 8
if num > 0:
    if num % 2 == 0:
        print("Positive Even Number ✅")

---

## 🔁 Flow of Execution 🔄
1️⃣ Condition is evaluated  
2️⃣ If the condition is **True ✅**, the corresponding block is executed  
3️⃣ If the condition is **False ❌**, control moves to `else` or next `elif`  
4️⃣ Program continues with the next statements

---

## 🛠 Applications 💡
✔️ Checking even or odd numbers  
✔️ Finding greatest of numbers  
✔️ Grade calculation  
✔️ Income tax calculation  
✔️ Salary calculation  
✔️ Decision-making programs  

---

## ⭐ Advantages ⭐
✨ Makes programs logical and efficient  
✨ Improves decision-making ability  
✨ Reduces code complexity  
✨ Easy to read and understand  
