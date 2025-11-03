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
input_dict = {2: 56, 1: 2, 5: 12, 4: 24, 6: 18, 3: 323}<br>
sorted_items = sorted(input_dict.items())<br>
print("Keys and Values sorted in alphabetical order by the key")<br>
for key, value in sorted_items:<br>
    print(f"({key}, {value})", end=' ')

## Sample Output
<img width="961" height="218" alt="image" src="https://github.com/user-attachments/assets/d9d7b450-b0f0-417c-827b-e2de3338b4d2" />

## Result
Thus,the program has been executed successfully.
