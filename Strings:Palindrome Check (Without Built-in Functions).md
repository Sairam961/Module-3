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
s="google"
if s==s[::-1]:
    print("The string is a palindrome")
else:
    print("The string is not a palindrome")
```
## Output
<img width="1661" height="327" alt="image" src="https://github.com/user-attachments/assets/f0e318ad-a4f8-44cc-ac5c-a263287752a3" />

## Result
Thus the program has been successfully executed
