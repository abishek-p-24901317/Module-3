# List Operations in Python: Sum of List Items

## 🎯 Aim
To write a Python program that calculates the **sum of all elements** in a list.

## 🧠 Algorithm
1. Define a list of numbers.
2. Use Python’s built-in `sum()` function to calculate the total.
3. Print the result.

## 🧾 Program
```
Developed by: Abishek P
Register Number: 212224240002
items=[153,147,124,102]
print(sum(items))
```
## Output
![438588168-66305d32-3488-42d3-a8ba-0f37998fc3e6](https://github.com/user-attachments/assets/93644d4a-9c8d-4a8b-9877-28665ff6ceee)

## Result
The program successfully calculates and prints the sum of all elements in the list using the built-in sum() function.

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
```
Developed by: Abishek P
Register Number: 212224240002
import re
l1 = []
items = ['goal', 'new', 'user', 'sit', 'eat', 'dinner']
for i in items:
    if not re.search(r"e", i):
        l1.append(i)
print("Words without 'e':", l1)
```
## Output
![438594607-a80859da-2d91-4ad1-bcc8-62df36ec9b89](https://github.com/user-attachments/assets/bf5b0309-1515-45fa-ad16-6e60bc36d4ff)


## Result
Thus the program executed successfully.

---
# 🧹 Strings-Remove Nth Index Character from a String

## 🎯 Aim
To write a Python program that accepts a string and removes the character at a specified index.

## 🧠 Algorithm
1. Define a function named `remove` that takes the input string as an argument.
2. Read the index `n` from the user input.
3. Initialize an empty string `a` to store the new string.
4. Iterate over each index of the string using a `for` loop.
5. Check if the current index `i` is not equal to `n`.
6. If `i != n`, append the character at index `i` to string `a`.
7. After the loop, return the modified string `a`.
8. Print the final result.

## 💻 Program
```
Developed by: Abishek P
Register Number: 212224240002
n=int(input())
def remove(a):
    for i in range(0,len(a)):
        if(i!=n):
            print(a[i],end='')
```
## Output
![438589026-1a17899e-b00b-4870-a86c-03823006a30d](https://github.com/user-attachments/assets/2d147775-cf99-45d8-9879-c8121eff3d16)

## Result
Thus the program executed successfully.

---
# Strings-Palindrome Check in Python (Without Built-in Functions)

## 🎯 Aim
To write a Python program to check whether the string `"google"` is a **palindrome** or not, without using built-in palindrome checking functions.

## 🧠 Algorithm
1. Assign the string `"google"` to a variable.
2. Reverse the string manually using slicing (`[::-1]`).
3. Compare the original string with the reversed string.
   - If they are equal, print that the string is a palindrome.
   - Otherwise, print that it is not a palindrome.
4. Execute the program.

## 🧾 Program
```
Developed by: Abishek P
Register Number: 212224240002
a=input()
s=a[::-1]
if a==s:
    print("The entered string is palindrome")
else:
    print("The entered string is not palindrome")
```
## Output
![438594726-0f57db4d-fa15-4c9c-a11b-394defe7f4c5](https://github.com/user-attachments/assets/3808668c-02ae-4a9f-85c4-5b8923dba62d)

## Result
Thus the program executed successfully.

---
# Tuple in Python: Check Element Existence

## 🎯 Aim
To write a Python program that checks if the element `'n'` and the element `8` exist within a given tuple.

## 🧠 Algorithm
1. Define a tuple `x` with some letters and numbers.
2. Use the `in` operator to check if the string `'n'` exists within the tuple.
3. Use the `in` operator to check if the integer `8` exists within the tuple.
4. Print the results.

## 🧾 Program
```
Developed by: Abishek P
Register Number: 212224240002
tuplex = input()
print("n" in tuplex)
print("8" in tuplex)
```
## Output
![438594831-9eb5f9ee-f253-4ce0-8de0-13535810c69a](https://github.com/user-attachments/assets/ee258d4c-23b9-4eca-a298-8ad2d14ecd1d)

## Result
Thus the program executed successfully.
