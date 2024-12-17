# Prime Numbers in a Range Using List Comprehension 💡✨  

## Table of Contents 🗂️  
1. [Introduction 📘](#1-introduction-📘)  
2. [Steps to Find Prime Numbers 🚀](#2-steps-to-find-prime-numbers-🚀)  
3. [Key Points 🌟](#3-key-points-🌟)  
4. [Output Explanation 🔍](#4-output-explanation-🔍)  
5. [Example Code 💻](#5-example-code-💻)  

---

## 1. Introduction 📘  

This example demonstrates how to efficiently find **prime numbers** in a given range using **list comprehension** and the `all()` function. Prime numbers are integers greater than `1` that are only divisible by `1` and themselves. 🧮✨  

---

## 2. Steps to Find Prime Numbers 🚀  

1. **Define the Range 🎯**:  
   - Use `range(2, 50)` to generate numbers from `2` to `49`.  

2. **Prime Number Check 🔗**:  
   - For each number, check if it is divisible by any number between `2` and the square root of the number.  

3. **Efficient Filtering with `all()` 🛠️**:  
   - Use the `all()` function to ensure none of the divisors divide the number evenly.  

4. **List Comprehension 📝**:  
   - Combine iteration and condition into a single line to filter out primes.  

5. **Print the Result 🖨️**:  
   - Display the list of all prime numbers within the range.  

---

## 3. Key Points 🌟  

- **Efficient Prime Check 🏎️**:  
  - Instead of dividing by all numbers up to `x`, we only check up to `sqrt(x)` for efficiency.  

- **`all()` Function 🔗**:  
  - Ensures all divisor checks return `True` (i.e., no divisors found).  

- **List Comprehension 🧹**:  
  - Combines logic and iteration into a concise and readable format.  

---

## 4. Output Explanation 🔍  

- **Range of Numbers 📜**:  
  - Numbers from `2` to `49` are generated using `range(2, 50)`.  

- **Condition Applied ✅**:  
  - A number `x` is included if it is not divisible by any number in `range(2, int(x**0.5) + 1)`.  

- **Resulting List 📋**:  
  - The final list of prime numbers is:  
    `[2, 3, 5, 7, 11, 13, 17, 19, 23, 29, 31, 37, 41, 43, 47]`.  

---

## 5. Example Code 💻  
```python
primes = [x for x in range(2, 50) if all(x % i != 0 for i in range(2, int(x**0.5) + 1))]
print(primes)  # Output: [2, 3, 5, 7, 11, 13, 17, 19, 23, 29, 31, 37, 41, 43, 47]

