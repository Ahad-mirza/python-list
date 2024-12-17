# `Count()` method in List
# Steps Explained 🚶‍♂️

## 1. **Define the list:**
We start with a list of numbers:
```python
list = [2, 3, 2, 5, 2, 7, 8] 📋
This list contains multiple occurrences of the number 2.
```
## 2. Call the count() method:
We use the `count()` method to count how many times the element 2 appears in the list.

```python
Copy code
result = list.count(2) 🔢
This method searches through the list and returns the number of occurrences of the element 2.
```

## 3. Output the result:
After calling count(2), we print the result:

```python
Copy code
print(result) 🖨️
```
The `output` will be:

```python
Copy code
3
```
This means the number `2` appears `3` times in the list.

### Important Notes 📌
The count() method counts the occurrences of a specific element in the list.
If the element is not found, it will return 0.
The count() method is `case-sensitive` for strings, meaning it treats uppercase and lowercase characters as different.
