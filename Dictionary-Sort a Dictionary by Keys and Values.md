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
~~~
data = {
    'banana': 'yellow',
    'apple': 'red',
    'grape': 'purple',
    'orange': 'orange'
}

sorted_by_keys = dict(sorted(data.items()))

sorted_by_values = dict(sorted(data.items(), key=lambda item: item[1]))

print("Original Dictionary:")
print(data)

print("\nSorted by Keys:")
print(sorted_by_keys)

print("\nSorted by Values:")
print(sorted_by_values)
~~~

## Sample Output
<img width="1038" height="572" alt="image" src="https://github.com/user-attachments/assets/79bac3f4-4774-4019-99a3-5af0eb9abe0c" />

## Result
The Python program that sorts a dictionary's is executed successfully.

