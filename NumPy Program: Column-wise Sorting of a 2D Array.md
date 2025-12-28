# NumPy Program: Column-wise Sorting of a 2D Array

## 🎯 Aim
To write a **NumPy** program that sorts the elements in each column of a given 2D array in ascending order.

## 🧠 Algorithm

1. **Import NumPy**: Start by importing the NumPy library.
2. **Get Input**: Accept a 2D NumPy array from the user.
3. **Sort Column-wise**: Use the `np.sort()` function with `axis=0` to sort each column in ascending order.
4. **Store Result**: Store the sorted result in a new array.
5. **Display Output**: Print the original array and the column-wise sorted array.

## 🧾 Program
```
import numpy as np
l= eval(input())
print("Given array")
a=np.array(l)
print('',a)
print()
a=np.sort(a)
print(a)
```

## Output

![WhatsApp Image 2025-12-28 at 2 21 28 PM](https://github.com/user-attachments/assets/3aea95f1-fd9d-47e4-be2e-8aacedb33955)

## Result
Thus,the program has been executed sucessfully
