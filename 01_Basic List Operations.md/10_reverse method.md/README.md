# Reverse Method in List 🔄
---
## 1. **Define the list:**
We start with a list of numbers:
```python
list = [10, 20, 30, 40, 50] 📋
```
This list contains several numbers, and we want to reverse the order of these elements.

## 2. Call the reverse() method:
We use the `reverse()` method to reverse the order of elements in the list.

```python
Copy code
list.reverse() 🔄
```
This method reverses the elements in place `(modifies the original list)`.

## 3. Output the result:
After calling `reverse()`, we print the list:

```python
Copy code
print(list) 🖨️
```
The output will be:

**[50, 40, 30, 20, 10]**
This means that the list is now reversed.

## What Happens Internally 🔍:
- The reverse() method `rearranges` the elements in the list by reversing their order.
- The method works in place, meaning it directly modifies the original list.
## Important Notes 📌
- The reverse() method does not return a new list, it modifies the existing one.
- If the list is empty or has one element, calling reverse() will not change the list.
- The method is only valid for mutable lists (like Python lists).

