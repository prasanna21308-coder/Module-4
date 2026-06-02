## Dictionary Operations in Python: Merging Two Dictionaries

## 🎯 Aim
To write a Python program that merges **two dictionaries** and combines their key-value pairs.

## 🧠 Algorithm
1. Define two dictionaries `dict1` and `dict2` with some key-value pairs.
2. Define a function `merge()` that merges the two dictionaries using the `**` unpacking operator.
   - The merged result will combine keys from both dictionaries. If a key exists in both, the value from `dict2` will overwrite that from `dict1`.
3. Call the `merge()` function and print the merged dictionary.

## 🧾 Program

Add code here
```
dict1 = {'a': 1, 'b': 2, 'c': 3} 
dict2 = {'b': 20, 'd': 4}

def merge(): 
    merged = {**dict1, **dict2} 
    print(merged)

merge()
```

## Output
<img width="1387" height="427" alt="image" src="https://github.com/user-attachments/assets/aac5145d-c0e4-46c9-ba36-df755ec9b88d" />

## Result
Thus To write a Python program that merges two dictionaries and combines their key-value pairs. Hence the code has been executed successfully.
