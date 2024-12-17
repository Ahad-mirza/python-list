# **Pyton `index()` method**
---
# Steps Explained 🚶‍♂️

## 1. **Define the list:**
We start with a list of numbers:
```python
list = [10, 20, 30, 40, 50] 📋
This list contains several numbers, and we want to find the index of a specific element.
```
## 2. Call the index() method:
We use the index() method to find the `position` (index) of the element `40` in the list.

```python
Copy code
result = list.index(40) 🔢
```
This method searches the list and returns the index of the first occurrence of the element 40. The index is the position of the element, starting from `0`.

## 3. Output the result:
After calling `index(40)`, we print the result:

```python
Copy code
print(result) 🖨️
```
The output will be:

```python
Copy code
3
```
This means that 40 is located at index 3 in the list.

## What Happens Internally 🔍:
The `index()` method starts from the beginning of the list.
It checks each element one by one until it finds the first occurrence of 40.
Once found, it returns the index of that element.
### Important Notes 📌
The index() method returns the index of the first occurrence of the specified element.
If the element is not found, Python will raise a ValueError ⚠️.
The index starts from 0, so the first element of the list has index 0, the second has index 1, and so on.


