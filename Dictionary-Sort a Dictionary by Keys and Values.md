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
original_dict = {'apple': 'fruit', 'carrot': 'vegetable', 'banana': 'fruit', 'date': 'dry fruit'}

# Sort dictionary by keys
sorted_by_keys = dict(sorted(original_dict.items()))

# Sort dictionary by values
sorted_by_values = dict(sorted(original_dict.items(), key=lambda item: item[1]))

print("Original dictionary:", original_dict)
print("Sorted by keys:", sorted_by_keys)
print("Sorted by values:", sorted_by_values)
```
## Sample Output
<img width="832" height="330" alt="image" src="https://github.com/user-attachments/assets/600cb9f5-0347-4298-8be3-183a9bcc2678" />

## Result
Thus implementation of a Python program that sorts a dictionary is done successfully:


