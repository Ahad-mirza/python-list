# Rotating a List in Python 🔄

## Table of Contents 🗂️  
1. [Introduction 📘](#1-introduction-📘)  
2. [Steps to Rotate a List 🚀](#2-steps-to-rotate-a-list-🚀)  
3. [Key Points 🌟](#3-key-points-🌟)  
4. [Output Explanation 🔍](#4-output-explanation-🔍)  
5. [Example Code 💻](#5-example-code-💻)  

---

## 1. Introduction 📘  

Rotating a list involves shifting its elements to the right or left by a certain number of positions. In this example, we will rotate the list to the right by `n` positions. This is achieved using slicing and concatenation in Python. 🔄  

---

## 2. Steps to Rotate a List 🚀  

1. **Define the List 📋**:  
   - Start with a list, such as `my_list = [1, 2, 3, 4, 5]`.

2. **Specify the Number of Positions `n` 🧮**:  
   - Choose the number of positions to rotate the list, e.g., `n = 2`.

3. **Slice the List and Concatenate 🔄**:  
   - Use slicing to divide the list into two parts:  
     - `my_list[-n:]` gives the last `n` elements.  
     - `my_list[:-n]` gives the elements up to the last `n` elements.  
   - Concatenate these two parts to get the rotated list.

4. **Print the Result 🖨️**:  
   - Display the new rotated list.

---

## 3. Key Points 🌟  

- **Slicing 🧩**:  
  - Slicing allows you to extract parts of the list using indices.  

- **Concatenation ➕**:  
  - The `+` operator combines the two sliced parts of the list.

- **Rotation 🔄**:  
  - The rotation works by moving elements from the end of the list to the front.  

---

## 4. Output Explanation 🔍  

- **Original List 📋**:  
  - `my_list = [1, 2, 3, 4, 5]`

- **Rotation Process 🔄**:  
  - The last `n` elements `[4, 5]` are moved to the front, and the remaining elements `[1, 2, 3]` are shifted to the right.

- **Final Output ✅**:  
  - `rotated_list = [4, 5, 1, 2, 3]`

---

## 5. Example Code 💻  
```python
my_list = [1, 2, 3, 4, 5]
n = 2
rotated_list = my_list[-n:] + my_list[:-n]
print(rotated_list)  # Output: [4, 5, 1, 2, 3]

