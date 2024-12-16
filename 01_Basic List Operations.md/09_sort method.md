# `sort()` method in list
---
# Steps Explained 🚶‍♂️
## 1. Define the list:
We start with a list of numbers:

```python
Copy code
list = [5, 3, 8, 6, 7, 2] 📋
```
This list contains `unsorted` numbers, and we want to sort them in `ascending` order.

## 2. Call the sort() method:
We use the `sort()` method to arrange the elements of the list in ascending order.

```python
Copy code
list.sort() 🔢
```
This method sorts the elements of the list in place, meaning it modifies the original list rather than creating a new one.

## 3. Output the result:
After calling `sort()`, we print the list:

```python
Copy code
print(list) 🖨️
```
The output will be:

### `[2, 3, 5, 6, 7, 8]`
This means that the list is now sorted in ascending order.

## What Happens Internally 🔍:
The `sort()` method compares each element in the list.
It rearranges them so that they are in `ascending order`.
This `sorting` happens in place, modifying the original list directly.
## Important Notes 📌
The `sort()` method only works with *mutable* lists (i.e., lists that can be changed).
If the list contains elements that cannot be compared (e.g., mixing strings and numbers), it will raise a TypeError.
By default, sort() sorts the list in ascending order. You can pass reverse=True to sort the list in descending order.
