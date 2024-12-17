# 📝 Advanced List Operations

## Table of Contents 🗂️  
1. [Generate Fibonacci Numbers 🔢](#generate-fibonacci-numbers-🔢)  
2. [Split List into Two Halves 📄](#split-list-into-two-halves-📄)  
3. [Find Second Largest Number 🥈](#find-second-largest-number-🥈)  
4. [Divisible by 3 and 5 🌟](#divisible-by-3-and-5-🌟)  
5. [Prime Numbers Less Than 50 🔢](#prime-numbers-less-than-50-🔢)  
6. [Zip Two Lists 🔗](#zip-two-lists-🔗)  
7. [Unzip a List of Tuples 📤](#unzip-a-list-of-tuples-📤)  
8. [Rotate List 🔄](#rotate-list-🔄)  
9. [Find Common Elements 🔍](#find-common-elements-🔍)  
10. [Reverse Strings in a List 🔄](#reverse-strings-in-a-list-🔄)  

---
### File Structure 📂  
- [01_Fibonacci list 🔢](https://github.com/Ahad-mirza/Python-List/tree/main/03_Advanced%20list%20Operations/01_Fibonacci%20list)  
- [02_Half of list 📄](https://github.com/Ahad-mirza/Python-List/tree/main/03_Advanced%20list%20Operations/02_Half%20of%20list)  
- [03_Find Largest Number 🥈](https://github.com/Ahad-mirza/Python-List/tree/main/03_Advanced%20list%20Operations/03_Find%20largest%20numbers)  
- [04_Division 🌟](https://github.com/Ahad-mirza/Python-List/tree/main/03_Advanced%20list%20Operations/04_Division)  
- [05_Prime Numbers list 🔢](https://github.com/Ahad-mirza/Python-List/tree/main/03_Advanced%20list%20Operations/05_Prime%20num.%20list)  
- [06_Zip method](https://github.com/Ahad-mirza/Python-List/tree/main/03_Advanced%20list%20Operations/06_Zip%20method)  
- [07_Unzip Tuples 📤](https://github.com/Ahad-mirza/Python-List/tree/main/03_Advanced%20list%20Operations/07_Unzip%20tuples)  
- 08_[Rotation 🔄](https://github.com/Ahad-mirza/Python-List/tree/main/03_Advanced%20list%20Operations/08_Rotation)  
- [09_Find Common Elements 🔍](https://github.com/Ahad-mirza/Python-List/tree/main/03_Advanced%20list%20Operations/09_Find%20common%20elements)  
- [10_Reverse Strings in a List 🔄](https://github.com/Ahad-mirza/Python-List/tree/main/03_Advanced%20list%20Operations/10_Reverse%20of%20string)

---
  

## 01. 🔢 Generate Fibonacci Numbers  

### Steps:  
1️⃣ **Start with the first two numbers:** Initialize the sequence with 0 and 1.  
2️⃣ **Calculate the next number:** Add the last two numbers in the sequence to find the next one.  
3️⃣ **Repeat:** Continue adding the last two numbers until you have the desired count.  

💡 **Why it's useful:** The Fibonacci sequence is found in nature, art, and mathematics, making it a fascinating example of iterative calculations.  

---

## 02. 📄 Split List into Two Halves  

### Steps:  
1️⃣ **Find the midpoint:** Calculate the middle index of the list using its length.  
2️⃣ **Slice the list:** Split the list into two parts:  
   - The first half contains elements from the start to the midpoint.  
   - The second half contains elements from the midpoint to the end.  

💡 **Applications:** Common in divide-and-conquer algorithms and when processing or comparing two sections of data.  

---

## 03. 🥈 Find Second Largest Number  

### Steps:  
1️⃣ **Remove duplicates:** Ensure all numbers are unique by converting the list to a set.  
2️⃣ **Sort the numbers:** Arrange the numbers in ascending order.  
3️⃣ **Pick the second largest:** Select the second-to-last number from the sorted list.  

💡 **Why it matters:** Useful in ranking systems, data analysis, and determining runners-up in competitions.  

---

## 04. 🌟 Find Numbers Divisible by 3 and 5  

### Steps:  
1️⃣ **Define the range:** Decide the range of numbers to check (e.g., 1 to 100).  
2️⃣ **Check divisibility:** Use the modulo operator to find numbers divisible by both 3 and 5.  
3️⃣ **Collect the results:** Store these numbers in a list.  

💡 **Real-world use:** Helps in filtering datasets or solving logical problems like "FizzBuzz."  

---

## 05. 🔢 Find Prime Numbers Less Than 50  

### Steps:  
1️⃣ **Understand primes:** Prime numbers are divisible only by 1 and themselves.  
2️⃣ **Iterate through numbers:** Check each number from 2 to 50.  
3️⃣ **Test divisibility:** Ensure the number is not divisible by any smaller number (up to its square root).  
4️⃣ **Collect primes:** Add all qualifying numbers to the list.  

💡 **Applications:** Crucial in cryptography, algorithms, and understanding number theory.  

---

## 06. 🔗 Zip Two Lists  

### Steps:  
1️⃣ **Take two lists:** Start with two lists of equal or varying lengths.  
2️⃣ **Combine elements:** Pair corresponding elements from each list into tuples.  
3️⃣ **Create the zipped list:** Store these tuples in a single list.  

💡 **Use case:** Perfect for merging datasets or combining related sequences like names and scores.  

---

## 07. 📤 Unzip a List of Tuples  

### Steps:  
1️⃣ **Start with tuples:** Begin with a list of tuples containing paired data.  
2️⃣ **Unpack the tuples:** Separate the elements of each tuple.  
3️⃣ **Store in separate lists:** Create individual lists for each component of the tuples.  

💡 **When to use:** Ideal for splitting paired data back into individual datasets for analysis.  

---

## 08. 🔄 Rotate a List  

### Steps:  
1️⃣ **Decide the rotation count:** Determine how many positions to shift the list.  
2️⃣ **Slice the list:**  
   - Extract the last `n` elements (for right rotation).  
   - Extract the remaining elements.  
3️⃣ **Concatenate slices:** Combine the two parts in the new order.  

💡 **Why rotate:** Essential for cyclic operations like round-robin scheduling or transforming data.  

---

## 09. 🔍 Find Common Elements  

### Steps:  
1️⃣ **Convert to sets:** Change both lists into sets to handle unique values.  
2️⃣ **Find the intersection:** Use set operations to identify shared elements.  
3️⃣ **Convert back to a list:** Store the result as a list for further use.  

💡 **Common uses:** Frequently used in data comparison, database queries, and finding overlaps.  

---

## 10. 🔄 Reverse Strings in a List  

### Steps:  
1️⃣ **Take a list of strings:** Start with a collection of strings.  
2️⃣ **Reverse each string:** Use slicing or another method to invert the order of characters.  
3️⃣ **Store the reversed strings:** Save the modified strings in a new list.  


