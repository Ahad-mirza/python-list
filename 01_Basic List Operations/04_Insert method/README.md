
# Python List insert() Method

In this example, we are using the `insert()` method to insert an element at a specified position in the list.

### 📝 Steps to Use `insert()` Method:

1. **🔢 Initial List:**
   - The initial list is: `[10, 20, 30, 40, 50]`

2. **🛠️ Using `insert()` Method:**
   - The line `list.insert(2, 25)` will insert the value `25` at index `2`.
   - The index `2` means the third position in the list (indexing starts from `0`).

3. **🔄 After Insertion:**
   - After the insertion, the list becomes: `[10, 20, 25, 30, 40, 50]`

### 💡 `insert()` Method Details:
- **Syntax:** `list.insert(index, element)`
  - `index` is the position where you want to insert the element.
  - `element` is the value to be inserted.
- 🧑‍💻 The list is modified in-place, and all the elements after the inserted element shift to the right.

### 🚀 Example:
```python
list = [10, 20, 30, 40, 50]
list.insert(2, 25)
print(list) # Output: [10, 20, 25, 30, 40, 50]
```

### ✅ Key Points:
- 🛠️ `insert()` modifies the list directly.
- 🎯 It inserts the element at the specific index you provide.
- ➡️ The list elements after the insertion shift one place to the right.

