# 🔤 Dictionary-Python Program to Sort a Dictionary by Keys and Values

This Python program demonstrates how to sort a dictionary:
- Alphabetically by keys
- Alphabetically by values

---

## 🎯 Aim

To write a Python program that sorts a dictionary's:
- Keys in alphabetical order
- Values in alphabetical order

---

## 🧠 Algorithm

1. **Start the program.**
2. **Define** a dictionary with key-value pairs.
3. **Sort by Keys**:
   - Use `sorted(dictionary.items())`
   - Convert the result to a dictionary using `dict()`
4. **Sort by Values**:
   - Use `sorted(dictionary.items(), key=lambda item: item[1])`
   - Convert the result to a dictionary using `dict()`
5. **Display** the original and sorted dictionaries.
6. **End the program.**

---

## 🧪Program
Add Code here
```
data = {'banana': 3, 'apple': 5, 'cherry': 2, 'date': 4}

sorted_by_keys = dict(sorted(data.items())) 
sorted_by_values = dict(sorted(data.items(), key=lambda item: item[1]))

print("Original dictionary:", data) 
print("Sorted by keys:", sorted_by_keys) 
print("Sorted by values:", sorted_by_values)
```
## Sample Output
<img width="1782" height="495" alt="image" src="https://github.com/user-attachments/assets/9620d58a-aa46-4077-bbd9-b4dbdf3db498" />

## Result
Thus To write a Python program that sorts a dictionary's: Keys in alphabetical order Values in alphabetical order Hence the code has been executed successfully.
