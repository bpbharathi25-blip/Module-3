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
```
import re
items = ['goal', 'new', 'user', 'sit', 'eat', 'dinner'] 
l=[] 
for i in items:
    w=re.search("e",i)
    if w:
        continue
    else:
        l.append(i)#'They ate 5 apples and 5 orange
print(l)
```
## Output
<img width="458" height="300" alt="image" src="https://github.com/user-attachments/assets/e137494d-b4e5-45d8-8db1-1ad095a31024" />

## Result
Thus,the Python program that filters out and returns all elements from a list that do not contain the letter 'e', using regular expressions (regex) is created successfully.
