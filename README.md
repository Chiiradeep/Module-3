# List Operations in Python: Sum of List Items

## 🎯 Aim
To write a Python program that calculates the **sum of all elements** in a list.

## 🧠 Algorithm
1. Define a list of numbers.
2. Use Python’s built-in `sum()` function to calculate the total.
3. Print the result.

## 🧾 Program
~~~python
 L=[153,147,124,102] 
print(sum(L)))

~~~

## Output
![439296928-d732e3a8-dadb-4ab4-91c7-c4c18b31bd03](https://github.com/user-attachments/assets/7c7feb30-030c-4bd8-879e-288be391d9a7)


## Result
Thus, the program has been executed successfully.

---

# Regex in Python: Filter Words Without the Letter 'e'

## 🎯 Aim
To write a Python program that filters out and returns all elements from a list **that do not contain the letter `'e'`**, using **regular expressions (regex)**.

## 🧠 Algorithm
1. Import the `re` module.
2. Initialize an empty list `l1` to store results.
3. Define a list of words:  
   `items = ['goal', 'new', 'user', 'sit', 'eat', 'dinner']`
4. Iterate through each word in the list:
   - Use `re.search(r"e", i)` to check if the word contains `'e'`.
   - If **not**, append the word to `l1`.
5. Print the final filtered list.

## 🧾 Program
~~~python
import re

items = ['goal', 'new', 'user', 'sit', 'eat', 'dinner']
result = [item for item in items if not re.search(r'e', item)]
print(result)

~~~
## Output

![image](https://github.com/user-attachments/assets/e6a41898-12e3-43bb-bc88-0f89667f43a5)

## Result
Thus,the program has been executed successfully.
