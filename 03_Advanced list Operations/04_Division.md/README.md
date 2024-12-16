# Finding Numbers Divisible by 3 and 5 in a Range 🔢✨

## Table of Contents 🗂️  
1. [Introduction 📘](#1-introduction-📘)  
2. [Steps to Find the Numbers 🚀](#2-steps-to-find-the-numbers-🚀)  
3. [Key Points 🌟](#3-key-points-🌟)  
4. [Output Explanation 🔍](#4-output-explanation-🔍)  
5. [Example Code 💻](#5-example-code-💻)  

---

## 1. Introduction 📘  
This example demonstrates how to use **list comprehensions** in Python to find numbers within a range that are divisible by both `3` and `5`. The result is a list of such numbers, making it a quick and efficient solution. 🚀

---

## 2. Steps to Find the Numbers 🚀  

1. **Define the Range 🎯**:  
   - Use `range(1, 101)` to generate numbers from 1 to 100.  

2. **Apply Conditions 🔗**:  
   - Use the modulo operator (`%`) to check divisibility by both `3` and `5`.  

3. **List Comprehension 📝**:  
   - Use a compact list comprehension to filter numbers meeting the condition.  

4. **Print the Result 🖨️**:  
   - Display the list of numbers that are divisible by both `3` and `5`.  

---

## 3. Key Points 🌟  

- **Efficient Filtering 🏎️**:  
  - List comprehensions allow concise and fast filtering of numbers.  

- **Modulo Operator `%` ➗**:  
  - Checks if there is no remainder when dividing by `3` and `5`.  

- **Readable Syntax 🧹**:  
  - Combines logic and iteration into a single, easy-to-read line of code.  

---

## 4. Output Explanation 🔍  

- **Range of Numbers 📜**:  
  - Numbers from `1` to `100` are generated using `range(1, 101)`.  

- **Condition Applied ✅**:  
  - A number is included if it satisfies both `i % 3 == 0` and `i % 5 == 0`.  

- **Resulting List 📋**:  
  - The final list is `[15, 30, 45, 60, 75, 90]`. These are the numbers divisible by both `3` and `5`.  

---

## 5. Example Code 💻  
```python
divisible_by_3_and_5 = [i for i in range(1, 101) if i % 3 == 0 and i % 5 == 0]
print(divisible_by_3_and_5)  # Output: [15, 30, 45, 60, 75, 90]

