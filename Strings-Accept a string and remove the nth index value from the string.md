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
```
# Function to remove character at nth index
def remove(string, n):
    result = ""
    for i in range(len(string)):
        if i != n:
            result += string[i]
    return result

# Input string from user
input_string = input()

# Input index to remove
index = int(input())

# Call function and print result
modified_string = remove(input_string, index)
print(modified_string)
```
## Output
![WhatsApp Image 2025-09-01 at 17 30 45_3e07a200](https://github.com/user-attachments/assets/3775bacd-c2a6-400d-8798-04d4d70779e4)


## Result
The Python program was successfully executed to remove a character at a specified index from a string.
