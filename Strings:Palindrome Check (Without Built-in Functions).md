# Strings-Palindrome Check in Python (Without Built-in Functions)

## 🎯 Aim
To write a Python program to check whether the string `"civic"` is a **palindrome** or not, without using built-in palindrome checking functions.

## 🧠 Algorithm
1. Assign the string `"civic"` to a variable.
2. Reverse the string manually using slicing (`[::-1]`).
3. Compare the original string with the reversed string.
   - If they are equal, print that the string is a palindrome.
   - Otherwise, print that it is not a palindrome.
4. Execute the program.

## 🧾 Program
```
def palindrome(a):
    l=[]
    for i in a:
        l.append(i)
    l2=l[::-1]
    if l==l2:
        print("The entered string is palindrome")
    else:
        print("The entered string is not palindrome")
string =input()
palindrome(string)
```
## Output
![image](https://github.com/user-attachments/assets/58026bde-fd16-408d-961a-4b0dd5b2e87d)

## Result
Thus the program to check whether the string `"civic"` is a **palindrome** or not has executed successfully.
