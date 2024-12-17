
### ➕ Adding an Element to a List

Below is an example of adding an element to a list using the `append` method:

```python
list = [10, 20, 30, 40, 50]
list.append(60)  # Add 60 to the end of the list
print(list)
```

**✨ Output:**

```
[10, 20, 30, 40, 50, 60]
```

### 📝 Steps to Understand the Code:

1. **Define the List:**
   - `list = [10, 20, 30, 40, 50]`: A list of integers is defined.

2. **Append an Element:**
   - `list.append(60)`: The `append()` method adds the value `60` to the end of the list.
   - This operation modifies the list in place.

3. **Print the Updated List:**
   - The updated list `[10, 20, 30, 40, 50, 60]` is printed using the `print()` function.

### 🔍 About the `append` Method:

- **Purpose:** Adds a single element to the end of a list.
- **Syntax:** `list.append(element)`
- **In-Place Operation:** The list is modified directly without creating a new list.
- **Examples:**
  ```python
  my_list = [1, 2, 3]
  my_list.append(4)  # Adds 4 to the end
  print(my_list)  # Output: [1, 2, 3, 4]
  ```

The `append` method is a simple and efficient way to dynamically add elements to a list! 🚀

