# NumPy Program: Column-wise Sorting of a 2D Array

## 🎯 Aim
To write a **NumPy** program that sorts the elements in each column of a given 2D array in ascending order.

## 🧠 Algorithm

1. **Import NumPy**: Start by importing the NumPy library.
2. **Get Input**: Accept a 2D NumPy array from the user.
3. **Sort Column-wise**: Use the `np.sort()` function with `axis=0` to sort each column in ascending order.
4. **Store Result**: Store the sorted result in a new array.
5. **Display Output**: Print the original array and the column-wise sorted array.

## 🧾 Program:
```
# Program to sort a 2D array column-wise using NumPy

import numpy as np

# Input from user
rows = int(input("Enter number of rows: "))
cols = int(input("Enter number of columns: "))

print("Enter elements row-wise:")
data = []
for i in range(rows):
    row = list(map(int, input().split()))
    data.append(row)

# Convert to NumPy array
arr = np.array(data)

# Column-wise sort
sorted_arr = np.sort(arr, axis=0)

# Output
print("Original Array:")
print(arr)

print("Column-wise Sorted Array:")
print(sorted_arr)
```

## Output:

<img width="529" height="530" alt="image" src="https://github.com/user-attachments/assets/1ec4f7fc-2099-4ae9-a96e-36d1ea7221fb" />


## Result:

Thus, the Python program using NumPy to sort a 2D array column-wise was successfully executed and verified.
