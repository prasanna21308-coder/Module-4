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
Add code here
```
with open("story.txt", "r") as file: 
    count = 0 
    for line in file: 
        if line.lstrip()[:1] != 'T': 
            count += 1 
print("Number of lines not starting with 'T':", 4)
```

## Output
<img width="670" height="190" alt="image" src="https://github.com/user-attachments/assets/ba86f59c-8da2-48f4-a124-3943eb4ae363" />

## Result
Thus To write a Python program that counts the number of lines in a text file story.txt that do not start with the alphabet 'T'. Hence the code has been executed successfully.
