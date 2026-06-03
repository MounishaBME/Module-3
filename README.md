# List Operations in Python: Sum of List Items

## 🎯 Aim
To write a Python program that calculates the **sum of all elements** in a list.

## 🧠 Algorithm
1. Define a list of numbers.
2. Use Python’s built-in `sum()` function to calculate the total.
3. Print the result.

## 🧾 Program
```
numbers = [10, 20, 30, 40, 50]
total = sum(numbers)
print("The sum of all elements in the list is:", total)
```
## Output

<img width="605" height="166" alt="image" src="https://github.com/user-attachments/assets/76658523-9e30-42f8-945c-bb5b3470225f" />

## Result

Thus, the program has been excecuted successfully.


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

l1 = []
items = ['goal', 'new', 'user', 'sit', 'eat', 'dinner']

for i in items:
    if not re.search(r"e", i):
        l1.append(i)

print(l1)
```
## Output

<img width="394" height="184" alt="image" src="https://github.com/user-attachments/assets/eae6e815-9b53-48e5-8a11-bccba408ea8a" />

## Result
Thus, the program has been excecuted successfully.



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
def remove(string):
    n = int(input("Enter the index to remove: "))
    a = ""
    for i in range(len(string)):
        if i != n:
            a += string[i]
    return a

str1 = input("Enter a string: ")
print("Modified string:", remove(str1))
```

## Output

<img width="468" height="265" alt="image" src="https://github.com/user-attachments/assets/5743d524-0cce-4de6-805f-7d449435d197" />

## Result
Thus, the program has been excecuted successfully.


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
string = "google"
rev = string[::-1]

if string == rev:
    print("The string is a palindrome.")
else:
    print("The string is not a palindrome.")

```
## Output

<img width="402" height="177" alt="image" src="https://github.com/user-attachments/assets/aca4b6d7-2f40-4dc2-8721-05017cfda76f" />

## Result
Thus, the program has been excecuted successfully.


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
x = ('a', 'n', 'g', 'e', 'l', 8, 10, 15)

print('n' in x)
print(8 in x)
```
## Output

<img width="399" height="217" alt="image" src="https://github.com/user-attachments/assets/aa1d298c-a153-49e6-b96f-920ccd7aebe7" />

## Result
Thus, the program has been excecuted successfully.
