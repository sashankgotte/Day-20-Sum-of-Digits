# Day 20 – Sum of Digits in a Number

## 📌 Description
This Python program calculates the sum of all digits in a given number using a `while` loop.

## 💻 Program
```python
n = int(input("Enter number: "))

total = 0

while n > 0:
    total += n % 10
    n //= 10

print("Sum of digits =", total)
```

## ▶️ Sample Output
```text
Enter number: 1234
Sum of digits = 10
```

## 🧠 Concepts Used
- Python Variables
- User Input
- While Loop
- Modulus Operator (%)
- Floor Division (//)
- Arithmetic Operations

## 🎯 Learning Outcome
Learned how to extract individual digits from a number and calculate their sum using a while loop.

## 📚 Challenge
Python Programming – 20 Days Challenge

**Day 20: Sum of Digits in a Number** 🐍