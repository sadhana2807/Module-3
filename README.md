# List Operations in Python: Sum of List Items

## 🎯 Aim
To write a Python program that calculates the **sum of all elements** in a list.

## 🧠 Algorithm
1. Define a list of numbers.
2. Use Python’s built-in `sum()` function to calculate the total.
3. Print the result.

## 🧾 Program
~~~
numbers = [14, 16, 18, 22]
total = sum(numbers)
print(total)
~~~

## Output
<img width="832" height="285" alt="image" src="https://github.com/user-attachments/assets/ea7770e5-76db-496d-931e-7e1ef8cd5e92" />


## Result
Thus , the program has been executed successfully.

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
~~~
import re
l1 = []
items = ['goal', 'new', 'user', 'sit', 'eat', 'dinner']
for i in items:
    if not re.search(r"e", i):
        l1.append(i)
print(l1)
~~~
## Output
<img width="701" height="186" alt="image" src="https://github.com/user-attachments/assets/e700467c-1bf7-4f06-b83b-3f6d03f4f043" />


## Result
Thus , the program has been executed successfully.

# Module-3
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
~~~
def remove(string):
    n = int(input())
    a = ""
    for i in range(len(string)):
        if i != n:
            a += string[i]
    print(a)
~~~

## Output
<img width="915" height="231" alt="image" src="https://github.com/user-attachments/assets/3dd19c42-67f2-4134-9298-fc637f4c62b8" />


## Result
Thus , the program has been executed successfully.

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
~~~
string = "google"
reversed_string = string[::-1]
if string == reversed_string:
    print(f"{string} is a palindrome.")
else:
    print(f"{string} is not a palindrome.")
~~~
## Output
<img width="817" height="172" alt="image" src="https://github.com/user-attachments/assets/1cea4594-b6b3-418b-8c3a-ce414b22a773" />


## Result
Thus the given program is verified and executed sucessfully.

# Tuple in Python: Check Element Existence

## 🎯 Aim
To write a Python program that checks if the element `'n'` and the element `8` exist within a given tuple.

## 🧠 Algorithm
1. Define a tuple `x` with some letters and numbers.
2. Use the `in` operator to check if the string `'n'` exists within the tuple.
3. Use the `in` operator to check if the integer `8` exists within the tuple.
4. Print the results.

## 🧾 Program
~~~
a=eval(input())
print("n" not in a)
print("8" in a)
~~~
## Output
<img width="1128" height="281" alt="image" src="https://github.com/user-attachments/assets/c022289a-ef0b-48a9-8d34-04c32a80183e" />

## Result
Thus the given program is verified and executed sucessfully.
