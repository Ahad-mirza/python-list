# Fibonacci Sequence Generator 📜

## Table of Contents 🗂️
1. [Introduction](#1-introduction-📘)  
2. [Steps to Generate Fibonacci Sequence](#2-steps-to-generate-fibonacci-sequence-🚀)  
3. [Key Points](#3-key-points-⭐)  
4. [Output Explanation](#4-output-explanation-🔍)  
5. [Example Code](#5-example-code-💻)  

---

## 1. Introduction 📘
This code dynamically generates a Fibonacci sequence. Fibonacci numbers follow the pattern where each number is the sum of the two preceding numbers. It starts with 0 and 1, and the sequence grows as you add subsequent terms.

---

## 2. Steps to Generate Fibonacci Sequence 🚀
1. **Initialize the Sequence**:
   - Start with a list containing the first two Fibonacci numbers: `0` and `1`.  
   - This serves as the base for generating the sequence.

2. **Iterate for a Fixed Range**:
   - Use a `for` loop to calculate the next Fibonacci numbers.
   - The loop runs 8 times, as we want to generate 8 additional terms.

3. **Calculate the Next Term**:
   - For each iteration, find the sum of the last two numbers in the list (`fib[-1]` and `fib[-2]`).

4. **Append the New Term**:
   - Add the computed value to the list using the `append` method.
   - The list grows dynamically as new terms are added.

5. **Print the Final List**:
   - After the loop finishes, print the entire Fibonacci sequence.

---

## 3. Key Points ⭐
- **Dynamic Growth**: The list grows as new terms are calculated and appended.
- **Efficient Calculation**: The use of `fib[-1]` and `fib[-2]` ensures that the program always works with the latest two numbers in the sequence.
- **Flexibility**: Changing the range in the loop adjusts the number of terms generated.

---

## 4. Output Explanation 🔍
- The sequence begins with `0` and `1`.
- The next numbers are calculated as follows:
  - **1st iteration**: `0 + 1 = 1` → List: `[0, 1, 1]`
  - **2nd iteration**: `1 + 1 = 2` → List: `[0, 1, 1, 2]`
  - **3rd iteration**: `1 + 2 = 3` → List: `[0, 1, 1, 2, 3]`
  - **4th iteration**: `2 + 3 = 5` → List: `[0, 1, 1, 2, 3, 5]`
  - **5th iteration**: `3 + 5 = 8` → List: `[0, 1, 1, 2, 3, 5, 8]`
  - **6th iteration**: `5 + 8 = 13` → List: `[0, 1, 1, 2, 3, 5, 8, 13]`
  - **7th iteration**: `8 + 13 = 21` → List: `[0, 1, 1, 2, 3, 5, 8, 13, 21]`
  - **8th iteration**: `13 + 21 = 34` → List: `[0, 1, 1, 2, 3, 5, 8, 13, 21, 34]`
  
- **Final Output**: `[0, 1, 1, 2, 3, 5, 8, 13, 21, 34]`.

This approach is both simple and efficient, making it ideal for generating small to medium-sized Fibonacci sequences.

---

## 5. Example Code 💻
```python
fib = [0, 1]
for i in range(8):
    fib.append(fib[-1] + fib[-2])
print(fib)  # Output: [0, 1, 1, 2, 3, 5, 8, 13, 21, 34]

