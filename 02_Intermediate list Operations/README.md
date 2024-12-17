# Python List Comprehensions and Operations 📝

## File Structure 🗂️
1. [01_Squares of Numbers🔢](https://github.com/Ahad-mirza/Python-List/tree/main/02_Intermediate%20list%20Operations/01_Square%20of%20numbers)  
2. [02_Filtering Even Numbers🟢](https://github.com/Ahad-mirza/Python-List/tree/main/02_Intermediate%20list%20Operations/02_Filter%20Even%20numbers)  
3. [03_Tuples with Numbers and Squares🎲](https://github.com/Ahad-mirza/Python-List/tree/main/02_Intermediate%20list%20Operations/03_Tuples-square)  
4. [04_Flattening Nested Lists📋](https://github.com/Ahad-mirza/Python-List/tree/main/02_Intermediate%20list%20Operations/04_List%20Flatten)  
5. [05_Finding Vowels in a String🅰️🅾️](https://github.com/Ahad-mirza/Python-List/tree/main/02_Intermediate%20list%20Operations/05_Extract%20vowels🅰️🅾️)  
6. [06_Concetenation➕](https://github.com/Ahad-mirza/Python-List/tree/main/02_Intermediate%20list%20Operations/06_Concetenation)  
7. [07_Converting to Upper Case🔠](https://github.com/Ahad-mirza/Python-List/tree/main/02_Intermediate%20list%20Operations/07_List%20uppercase)  
8. [08_Removing Specific Elements❌](https://github.com/Ahad-mirza/Python-List/tree/main/02_Intermediate%20list%20Operations/08_Remove)  
9. [09_Checking for an Empty List🔍](https://github.com/Ahad-mirza/Python-List/tree/main/02_Intermediate%20list%20Operations.md/09_Empty%20list)  
10. [10_Replacing Vowels in Text⭐](https://github.com/Ahad-mirza/Python-List/tree/main/02_Intermediate%20list%20Operations.md/10_Replace)  

---

## 1. Squares of Numbers 🔢
### Description:
Generate a list of squares for numbers ranging from 1 to 10 using list comprehension.

### Steps:
1. **Iterate** through numbers from 1 to 10.
2. **Square** each number using the `**2` operator.
3. Store the results in a new list.

### Key Points:
- This is an efficient way to compute squares of numbers in a single line.
- List comprehension simplifies the process.

---

## 2. Filtering Even Numbers 🟢
### Description:
Create a list of even numbers from 1 to 10 using list comprehension with a condition.

### Steps:
1. **Iterate** through numbers from 1 to 10.
2. Check if the number is divisible by 2 (`i % 2 == 0`).
3. **Include** only even numbers in the list.

### Key Points:
- Conditional logic inside list comprehension makes it concise.
- Useful for filtering data based on specific criteria.

---

## 3. Tuples with Numbers and Squares 🎲
### Description:
Generate a list of tuples where each tuple contains a number and its square.

### Steps:
1. **Iterate** through numbers from 1 to 10.
2. For each number, create a tuple `(number, number**2)`.
3. **Store** the tuples in a list.

### Key Points:
- Tuples provide a structured way to pair related values.
- Ideal for scenarios requiring paired data.

---

## 4. Flattening Nested Lists 📋
### Description:
Flatten a nested list into a single-level list using list comprehension.

### Steps:
1. Iterate through each **sublist** in the nested list.
2. Extract each **element** from the sublists.
3. Combine all elements into a single flat list.

### Key Points:
- Efficient for handling nested data structures.
- Simplifies further processing of data.

---

## 5. Finding Vowels in a String 🅰️🅾️
### Description:
Extract vowels from a given string using list comprehension.

### Steps:
1. Iterate through each **character** in the string.
2. Check if the character is a vowel (`a, e, i, o, u`).
3. **Collect** all vowels in a list.

### Key Points:
- Helps isolate specific types of characters.
- Can be adapted for other character filters.

---

## 6. Merging Two Lists ➕
### Description:
Combine two separate lists into a single list using the `+` operator.

### Steps:
1. Take two lists, e.g., `list1` and `list2`.
2. Use the `+` operator to **merge** them into a new list.
3. Preserve the order of elements.

### Key Points:
- Original lists remain unchanged.
- The merged list is a new object.

---

## 7. Converting to Upper Case 🔠
### Description:
Convert all elements of a list (e.g., characters) to uppercase using list comprehension.

### Steps:
1. Iterate through each **element** in the list.
2. Apply the `.upper()` method to convert it to uppercase.
3. Collect the uppercase values in a new list.

### Key Points:
- Great for text processing tasks.
- Ensures consistency in letter casing.

---

## 8. Removing Specific Elements ❌
### Description:
Remove all occurrences of a specific element (e.g., `3`) from a list.

### Steps:
1. Iterate through each **element** in the list.
2. Check if the element is **not** equal to the value to be removed (`!= 3`).
3. Collect all elements that meet the condition.

### Key Points:
- Filters out unwanted values.
- Retains the original order of remaining elements.

---

## 9. Checking for an Empty List 🔍
### Description:
Determine if a list is empty using an `if not` condition.

### Steps:
1. Check if the list is **empty** using the `not` keyword.
2. Print a message indicating whether the list is empty or not.

### Key Points:
- Quick way to verify list contents.
- Useful in conditional workflows.

---

## 10. Replacing Vowels in Text ⭐
### Description:
Replace all vowels in a string with a specific character (e.g., `*`).

### Steps:
1. Iterate through each **character** in the string.
2. Check if the character is a vowel.
3. Replace vowels with `*` and keep other characters unchanged.
4. Combine the modified characters into a new string.

### Key Points:
- Great for obfuscating sensitive data.
- Retains the structure of the original string.

---

## Conclusion 💡
This collection demonstrates the versatility of Python list comprehensions and operations. From generating patterns to filtering and modifying data, these techniques simplify common tasks and enhance code readability.
