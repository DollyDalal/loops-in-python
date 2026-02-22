# 🔁 STUDY OF LOOPS IN PYTHON 🐍  

## 📌 Aim  
To study and implement different types of loops in Python.

---

## 📖 Introduction  

Loops are used to execute a block of code repeatedly 🔄  
They reduce repetition and make programs efficient.

Python mainly provides:

- 🔹 for loop  
- 🔹 while loop  
- 🔹 Nested loops  
- 🔹 Loop control statements  

---

# 🔹 1️⃣ for Loop  

The `for` loop is used when the number of iterations is known.

## ✅ Syntax:
```python
for variable in sequence:
    statements
```

## ✅ Example:
```python
for i in range(5):
    print(i)
```

## 🖥 Output:
```
0
1
2
3
4
```

👉 `range(5)` generates numbers from 0 to 4.

---

# 🔹 2️⃣ while Loop  

The `while` loop runs as long as the condition is True.

## ✅ Syntax:
```python
while condition:
    statements
```

## ✅ Example:
```python
i = 1
while i <= 5:
    print(i)
    i += 1
```

---

# 🔹 3️⃣ Nested Loop 🔁  

A loop inside another loop is called a nested loop.

## ✅ Example:
```python
for i in range(3):
    for j in range(2):
        print(i, j)
```

👉 Used for patterns ⭐, tables 📊, matrices, etc.

---

# 🔹 4️⃣ Loop Control Statements 🛑  

## 🔸 break  
Stops the loop immediately.

```python
for i in range(5):
    if i == 3:
        break
    print(i)
```

---

## 🔸 continue  
Skips the current iteration.

```python
for i in range(5):
    if i == 3:
        continue
    print(i)
```

---

## 🔸 pass  
Does nothing (placeholder statement).

```python
for i in range(5):
    pass
```

---

# 🔹 5️⃣ for-else Concept 🤯  

The `else` block executes only if the loop finishes normally (without break).

```python
for i in range(5):
    print(i)
else:
    print("Loop completed successfully")
```

---

# ⚠️ Infinite Loop  

If the condition never becomes False, the loop runs forever.

```python
while True:
    print("Infinite Loop")
```

---

# 🔹 Applications of Loops 💡  

✔ Printing patterns  
✔ Prime number checking  
✔ Armstrong number  
✔ Tables generation  
✔ Searching elements  
✔ Menu-driven programs  
✔ Data processing  

---

# 🎯 Conclusion  

Loops are very important in Python programming 🐍  

They:
- Reduce repetition  
- Improve efficiency  
- Help in logical thinking  
- Are essential for problem solving  

Mastering loops is necessary to become good at programming 💻🔥
