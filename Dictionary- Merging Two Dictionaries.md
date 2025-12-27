## Dictionary Operations in Python: Merging Two Dictionaries

## 🎯 Aim
To write a Python program that merges **two dictionaries** and combines their key-value pairs.

## 🧠 Algorithm
1. Define two dictionaries `dict1` and `dict2` with some key-value pairs.
2. Define a function `merge()` that merges the two dictionaries using the `**` unpacking operator.
   - The merged result will combine keys from both dictionaries. If a key exists in both, the value from `dict2` will overwrite that from `dict1`.
3. Call the `merge()` function and print the merged dictionary.

## 🧾 Program
~~~

import math

class cse:
    def mech(self, radius):
        area = math.pi * radius ** 2
        return area
try:
    radius_input = float(input("Enter the radius of the circle: "))
    circle = cse()
    area = circle.mech(radius_input)
    print(f"The area of the circle is: {area:.2f}")
except ValueError:
    print("Please enter a valid number for the radius.")
~~~
## Output
<img width="1036" height="466" alt="image" src="https://github.com/user-attachments/assets/e8e62f57-c8d3-43af-9883-b2c70d3a39f0" />

## Result
The Python program that calculates the area of a circle based on the radius provided by the user. This program uses a class named cse and a method mech to perform the calculation is executed successfully.
