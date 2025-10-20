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
```
input_dict = {2: 56, 1: 2, 5: 12, 4: 24, 6: 18, 3: 323}

sorted_items = sorted(input_dict.items())

print("Keys and Values sorted in alphabetical order by the key")

for key, value in sorted_items:

    print(f"({key}, {value})", end=' ')
```
    
## Sample Output

<img width="1197" height="266" alt="image" src="https://github.com/user-attachments/assets/9a8ab0c7-75f1-4604-8bf9-a594c45c0537" />

## Result
Thus, code is executed successfully.
