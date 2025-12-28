# NumPy Program: Replace the Second Column in a 2D Array

## 🎯 Aim
To write a **NumPy** program that deletes the second column from a given 2D array and inserts a new column at the same position.

## 🧠 Algorithm
1. **Import NumPy**: Start by importing the NumPy library.
2. **Get Input**: Get a 2D NumPy array and a new column (as another array) from the user.
3. **Delete Column**: Use `np.delete()` to remove the second column (index 1) from the original array.
4. **Insert Column**: Use `np.insert()` to insert the new column at the second column's original position.
5. **Display Result**: Print the updated array with the replaced column.

## 🧾 Program

```
import numpy as np
l=eval(input())
l1=eval(input())
a=np.array(l)
newc=np.array(l1)
print("Printing Original array")
print(a)
a=np.delete(a,1,axis=1)
print("Array after deleting column 2 on axis 1")
print(a)
a=np.insert(a,1,newc,axis=1)
print("Array after inserting column 2 on axis 1")
print(a)
```
## Output
![WhatsApp Image 2025-12-28 at 2 22 22 PM](https://github.com/user-attachments/assets/98e87bb8-efeb-4b01-9fe3-d2ad0e62c6c4)


## Result
Thus,the program has been executed successfully.
