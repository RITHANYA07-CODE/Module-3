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
input_string = input("Enter a string: ")

# Input index to remove
index = int(input("Enter the index of character to remove: "))

# Call function and print result
modified_string = remove(input_string, index)
print("Modified string:", modified_string)
```
## Output
<img width="504" height="283" alt="image" src="https://github.com/user-attachments/assets/6b6af68f-c265-427d-9798-96523b0facea" />

## Result
The Python program was successfully executed to remove a character at a specified index from a string.
