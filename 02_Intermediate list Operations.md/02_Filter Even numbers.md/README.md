# List Comprehension with Conditions in Python 📝

## Table of Contents 📑
1. [Introduction](#introduction)
2. [Step-by-Step Explanation](#step-by-step-explanation)
   - [Iterating Over a Range](#iterating-over-a-range)
   - [Applying the Condition](#applying-the-condition)
   - [Creating the List](#creating-the-list)
3. [Key Points 📝](#key-points)
4. [Features of List Comprehension 🧑‍💻](#features-of-list-comprehension)
5. [Uses of List Comprehension 🛠️](#uses-of-list-comprehension)
6. [Conclusion 💡](#conclusion)
7. [Code Example with Output](#code-example-with-output)

---

## Introduction 🧐
This code uses list comprehension with a **conditional filter** to generate a list of even numbers from 1 to 10. The condition `i % 2 == 0` ensures that only even numbers are included in the list.
## Code Example with Output 🖥️

```python
even = [i for i in range(1, 11) if i % 2 == 0]
print(even)
```
#### *Output*
`[2, 4, 6, 8, 10]`

## Step-by-Step Explanation 🚶‍♂️

### Iterating Over a Range 🔄
- The `range(1, 11)` part generates a sequence of numbers starting from 1 up to 10.
- This means we will check each number from 1 to 10 to see if it meets the condition.

### Applying the Condition ❌✔️
- `if i % 2 == 0` checks if a number is even.
  - The expression `i % 2 == 0` returns `True` if the number `i` is divisible by 2 (i.e., even).
  - If the condition is `True`, the number is included in the new list.

### Creating the List 📋
- The list comprehension `[i for i in range(1, 11) if i % 2 == 0]` creates a new list containing only the even numbers from 1 to 10.
- The result is stored in the variable `even`.

---

## Key Points 📝

- **List Comprehension**: A concise way to create lists with optional conditions.
- **Condition Filter**: You can add conditions to include or exclude certain items in the list.
- **Compact Syntax**: List comprehension allows you to create and filter lists in a single line of code.

---

## Features of List Comprehension 🧑‍💻

- **Efficient**: Often faster than traditional loops for creating and filtering lists.
- **Readable**: It’s easy to see the transformation applied to the original data.
- **Flexible**: You can apply mathematical operations, string manipulations, and filtering conditions in one step.

---

## Uses of List Comprehension 🛠️

- **Filtering Data**: You can filter data based on specific conditions (e.g., even/odd numbers, strings containing certain characters).
- **Mathematical Operations**: Apply mathematical transformations like squaring, multiplying, or adding to list elements.
- **Extracting Subsets**: Use it to extract subsets of data that meet certain criteria from a larger dataset.

---

## Conclusion 💡

List comprehension is a powerful tool in Python, especially when combined with conditional logic. It provides an elegant, compact, and efficient way to work with lists while applying transformations or filters. Whether you're dealing with simple or complex data, list comprehension helps simplify your code and improve readability.

---



