# Module-3
# 🧹 Strings-Remove Nth Index Character from a String

## 🎯 Aim
To write a Python program that accepts a string and removes the character at a specified index.

## 🧠 Algorithm
1. Define a function named remove that takes a string s as an argument.
2. Read an integer n from the user input, which represents the index of the character to remove.
3. Initialize an empty string result to store the new string.
4. Iterate over each index i of the string s using a for loop.
5. Inside the loop, check if i is not equal to n.
6. If i != n, append the character s[i] to the string result.
7. After the loop finishes, print the string result.

## 💻 Program
```
def remove(s):
    n=int(input())
    result=s[:n]+s[n+1:]
    print(result)
```
## Output
![WhatsApp Image 2025-09-01 at 17 30 45_3e07a200](https://github.com/user-attachments/assets/3775bacd-c2a6-400d-8798-04d4d70779e4)


## Result
The Python program was successfully executed to remove a character at a specified index from a string.
