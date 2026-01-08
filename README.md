 # 🐍 Basic Python Programs

This repository contains a single Python file that includes **two beginner-level Python programs**.  
These programs help understand **conditional statements**, **loops**, and **user input**.

---

## 📌 Program 1: Even or Odd Number Checker

### Description
This program takes a number from the user and checks whether the number is **even or odd** using the modulus operator (`%`).

### Code
```python
num = int(input("Enter a number: "))

if num % 2 == 0:
    print(f"{num} is an even number.")
else:
    print(f"{num} is an odd number.")



## 📌 Program 2: Sum of Numbers from 1 to 50

### Description
This program uses a **for loop** to calculate the sum of all integers from **1 to 50** and displays the final sum.

### Code
```python
total = 0
for i in range(1, 51):
    total = total + i

print(f"The sum of numbers from 1 to 50 is : {total}")

