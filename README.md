# Classes and Objects in Python: Calculate the Area of a Circle

## 🎯 Aim
To write a Python program that calculates the **area of a circle** based on the radius provided by the user. This program uses a class named `cse` and a method `mech` to perform the calculation.

## 🧠 Algorithm
1. **Get user input**: Take the radius of the circle as input from the user.
2. **Define the class**: Create a class named `cse`.
3. **Define the method**: Inside the class, define the method `mech` to calculate the area of the circle using the formula:  
   Area = pi *r^2 
4. **Execute the program**: Create an object of the class and call the method with the radius value.

## 🧾 Program
```
import math

radius = float(input("Enter the radius of the circle: "))

class cse:
    def mech(self, r):
        area = math.pi * r * r
        print("Area of the circle:", area)

obj = cse()
obj.mech(radius)
```
## Output

<img width="1556" height="315" alt="Screenshot 2025-10-20 202449" src="https://github.com/user-attachments/assets/93ee9fc2-6f08-49dc-ab6c-a545a56dcee8" />

## Result

Thus To write a Python program that calculates the **area of a circle** based on the radius provided by the user. This program uses a class named `cse` and a method `mech` to perform the calculation.
Hence the code has been executed successfully.

## Dictionary Operations in Python: Merging Two Dictionaries

## 🎯 Aim
To write a Python program that merges **two dictionaries** and combines their key-value pairs.

## 🧠 Algorithm
1. Define two dictionaries `dict1` and `dict2` with some key-value pairs.
2. Define a function `merge()` that merges the two dictionaries using the `**` unpacking operator.
   - The merged result will combine keys from both dictionaries. If a key exists in both, the value from `dict2` will overwrite that from `dict1`.
3. Call the `merge()` function and print the merged dictionary.

## 🧾 Program
```
dict1 = {'a': 1, 'b': 2, 'c': 3}
dict2 = {'b': 20, 'd': 4}

def merge():
    merged = {**dict1, **dict2}
    print(merged)

merge()
```
## Output

<img width="1574" height="246" alt="Screenshot 2025-10-20 202739" src="https://github.com/user-attachments/assets/0c34d0ca-384c-4fde-9764-7e9b24598f1f" />

## Result

Thus To write a Python program that merges **two dictionaries** and combines their key-value pairs.
Hence the code has been executed successfully.

# 🔤 Dictionary-Python Program to Sort a Dictionary by Keys and Values

## 🎯 Aim

To write a Python program that sorts a dictionary's:
Keys in alphabetical order
Values in alphabetical order

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

## 🧪Program
```
data = {'banana': 3, 'apple': 5, 'cherry': 2, 'date': 4}

sorted_by_keys = dict(sorted(data.items()))
sorted_by_values = dict(sorted(data.items(), key=lambda item: item[1]))

print("Original dictionary:", data)
print("Sorted by keys:", sorted_by_keys)
print("Sorted by values:", sorted_by_values)
```
## Sample Output

<img width="1566" height="254" alt="Screenshot 2025-10-20 203106" src="https://github.com/user-attachments/assets/746d2fb8-442a-4b0d-a755-9847989bc58c" />

## Result

Thus To write a Python program that sorts a dictionary's:
Keys in alphabetical order
Values in alphabetical order
Hence the code has been executed successfully.

# Exception Handling in Python: Avoiding Index Errors

## 🎯 Aim
To write a Python program that handles an **IndexError** when trying to access an element beyond the available range of a list.

## 🧠 Algorithm
1. Define a list `list1` with some integer elements.
2. Use a **try-except** block:
   - In the `try` block, attempt to access an index that is out of range (e.g., `list1[5]`).
   - In the `except` block, catch the error and print a custom message `"You're out of list range"`.
3. Print the result based on whether the index access succeeds or fails.

## 🧾 Program
```
list1 = [1, 2, 3, 4]

try:
    print(list1[5])
except IndexError:
    print("You're out of list range")
```
## Output

<img width="1546" height="232" alt="Screenshot 2025-10-20 203325" src="https://github.com/user-attachments/assets/763f4876-a5f8-4707-8f8e-5cb1d98beebb" />

## Result

Thus To write a Python program that handles an **IndexError** when trying to access an element beyond the available range of a list.
Hence the code has been executed successfully.

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
with open("story.txt", "r") as file:
    count = 0
    for line in file:
        if line.lstrip()[:1] != 'T':
            count += 1
print("Number of lines not starting with 'T':", count)
```
## Output

<img width="1099" height="85" alt="Screenshot 2025-10-20 204947" src="https://github.com/user-attachments/assets/54d142de-8b20-4eda-bb82-e02809b448cb" />

## Result

Thus To write a Python program that counts the number of lines in a text file `story.txt` that do **not** start with the alphabet `'T'`.
Hence the code has been executed successfully.
