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
#Add code here

count = 0

with open("story.txt", "r") as file:

    for line in file:
    
        if not line.startswith('T'):
        
            count += 1

print(count)

## Output
<img width="232" height="246" alt="image" src="https://github.com/user-attachments/assets/7e5fa8cc-b035-4643-8af4-1c09c4aeb9be" />


## Result
Thus the program was successfully executed and obtained the result.
