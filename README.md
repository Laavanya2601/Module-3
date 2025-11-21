# EX:3 List Operations in Python: Sum of List Items

##  Aim
To write a Python program that calculates the **sum of all elements** in a list.

##  Algorithm
1. Define a list of numbers.
2. Use Python’s built-in `sum()` function to calculate the total.
3. Print the result.

##  Program
```
l= [1,2,-8]
print(sum(l))
```
## Output
![image](https://github.com/user-attachments/assets/fe910a1a-6898-4530-927e-f543ec165b4c)

## Result
Thus,the Python program that calculates the sum of all elements in a list is created successfully.

# Regex in Python: Filter Words Without the Letter 'e'

##  Aim
To write a Python program that filters out and returns all elements from a list **that do not contain the letter `'e'`**, using **regular expressions (regex)**.

##  Algorithm
1. Import the `re` module.
2. Initialize an empty list `l1` to store results.
3. Define a list of words:  
   `items = ['goal', 'new', 'user', 'sit', 'eat', 'dinner']`
4. Iterate through each word in the list:
   - Use `re.search(r"e", i)` to check if the word contains `'e'`.
   - If **not**, append the word to `l1`.
5. Print the final filtered list.

##  Program
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
![image](https://github.com/user-attachments/assets/22c285f4-8c81-414f-b972-fe7a69f62daa)

## Result
Thus,the Python program that filters out and returns all elements from a list **that do not contain the letter `'e'`**, using **regular expressions (regex)** is created successfully.

# Strings-Remove Nth Index Character from a String

##  Aim
To write a Python program that accepts a string and removes the character at a specified index.

##  Algorithm
1. Define a function named `remove` that takes the input string as an argument.
2. Read the index `n` from the user input.
3. Initialize an empty string `a` to store the new string.
4. Iterate over each index of the string using a `for` loop.
5. Check if the current index `i` is not equal to `n`.
6. If `i != n`, append the character at index `i` to string `a`.
7. After the loop, return the modified string `a`.
8. Print the final result.

##  Program
```
def remove(text):
    result = ''
    for i in range(len(text)):
        if i != 3:  
            result += text[i]
    return result
print(remove("learning")) 

```
## Output
![image](https://github.com/user-attachments/assets/f1f1d6a6-8d13-4577-a256-dedaac0c4a93)

## Result
Thus,the Python program that accepts a string and removes the character at a specified index is created successfully.

# Strings-Palindrome Check in Python (Without Built-in Functions)

##  Aim
To write a Python program to check whether the string `"google"` is a **palindrome** or not, without using built-in palindrome checking functions.

##  Algorithm
1. Assign the string `"google"` to a variable.
2. Reverse the string manually using slicing (`[::-1]`).
3. Compare the original string with the reversed string.
   - If they are equal, print that the string is a palindrome.
   - Otherwise, print that it is not a palindrome.
4. Execute the program.

##  Program
```
a=input()
b=a[::-1]
if a==b:
    print("The entered string is palindrome")
else:
    print("The entered string is not palindrome")
```
## Output
![image](https://github.com/user-attachments/assets/d49fb658-3e3a-490a-bcd3-c5205ad537c8)

## Result
Thus,the Python program to check whether the string `"malayalam"` is a **palindrome** or not, without using built-in palindrome checking functions is created successfully.

# Tuple in Python: Check Element Existence

##  Aim
To write a Python program that checks if the element `'n'` and the element `8` exist within a given tuple.

##  Algorithm
1. Define a tuple `x` with some letters and numbers.
2. Use the `in` operator to check if the string `'n'` exists within the tuple.
3. Use the `in` operator to check if the integer `8` exists within the tuple.
4. Print the results.

##  Program
```
a=eval(input())
b=bool('8' in a)
c=bool('n' not in a)
print(c)
print(b)
```
## Output
![image](https://github.com/user-attachments/assets/990dbc00-43b5-477b-8e88-4af7d6f77a98)

## Result
Thus,the Python program that checks if the element `'n'` and the element `8` exist within a given tuple is created successfully.
