# Unzipping a Zipped List 🔓🔗

## Table of Contents 🗂️  
1. [Introduction 📘](#1-introduction-📘)  
2. [Steps to Unzip a Zipped List 🚀](#2-steps-to-unzip-a-zipped-list-🚀)  
3. [Key Points 🌟](#3-key-points-🌟)  
4. [Output Explanation 🔍](#4-output-explanation-🔍)  
5. [Example Code 💻](#5-example-code-💻)  

---

## 1. Introduction 📘  

Unzipping a zipped list refers to the process of converting a list of tuples back into separate lists. This can be done using the `zip()` function with the unpacking operator `*`. 🧳✨  

---

## 2. Steps to Unzip a Zipped List 🚀  

1. **Start with a Zipped List 📋**:  
   - The list of tuples, such as `zipped_list = [(1, 'a'), (2, 'b'), (3, 'c')]`.  

2. **Unpack the Zipped List 🧳**:  
   - Use the unpacking operator `*` inside the `zip()` function to extract the elements of the tuples.  

3. **Convert the Unpacked Elements into Lists 🔄**:  
   - Convert the unpacked values into separate lists using `list()`.  

4. **Print the Result 🖨️**:  
   - Display the two lists that were separated from the zipped list.  

---

## 3. Key Points 🌟  

- **Tuple Unpacking 🧳**:  
  - The `*` operator is used to unpack the tuples into separate variables.  

- **Multiple Lists 🔄**:  
  - The zipped list can be split into multiple lists, maintaining the order of the elements.  

- **Flexibility 📚**:  
  - This method works with any number of tuples and can unzip them into as many lists as there are tuple elements.  

---

## 4. Output Explanation 🔍  

- **Zipped List 📋**:  
  - `zipped_list = [(1, 'a'), (2, 'b'), (3, 'c')]`  

- **Unzipping Process 🔓**:  
  - The unpacking operator `*` splits the tuples into two separate lists.  

- **Final Output ✅**:  
  - `list1` contains the first elements from each tuple: `[1, 2, 3]`.  
  - `list2` contains the second elements from each tuple: `['a', 'b', 'c']`.  

---

## 5. Example Code 💻  
```python
zipped_list = [(1, 'a'), (2, 'b'), (3, 'c')]
list1, list2 = zip(*zipped_list)
print(list(list1))  # Output: [1, 2, 3]
print(list(list2))  # Output: ['a', 'b', 'c']

