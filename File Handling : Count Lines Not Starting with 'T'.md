# File Handling in Python: Count Lines Not Starting with 'T'

## 🎯 Aim
To write a Python program that counts the number of lines in a text file `story.txt` that do **not** start with the alphabet `'T'`.

## 🧠 Algorithm
1. Open the file `story.txt` in **read mode**.
2. Initialize a counter `count` to zero.
3. Iterate through each line of the file:
   - Check if the first character of the line is **not** `'T'`.
   - If the line does not start with `'T'`, increment the `count` by 1.
4. After processing all lines, print the `count` value, which represents the number of lines that do not start with `'T'`.

## 🧾 Program
```
def create_file(file_path, content):
    with open(file_path, 'w') as file:
        file.write(content)

# Function to print lines that contain a specific substring
def print_lines_with_substring(file_path, substring):
    with open(file_path,'r') as f:
        r=f.readlines()
        for x in r:
            if substring in x:
                print(x)
```    

## Output
<img width="1140" height="500" alt="Screenshot 2025-10-21 122733" src="https://github.com/user-attachments/assets/1a408c4d-ce14-4f8a-86af-8f5bda92c772" />

## Result
successfully created a Python program that counts the number of lines in a text file `story.txt` that do **not** start with the alphabet `'T'`.
