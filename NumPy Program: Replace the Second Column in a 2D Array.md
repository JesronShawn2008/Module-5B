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
#Complete the following code
import numpy
x=eval(input())
y=eval(input())
print("Printing Original array")
Array = numpy.array(x)
print(Array)

print("Array after deleting column 2 on axis 1")
sampleArray = numpy.delete(Array,1,axis=1) 
print(sampleArray)

arr = numpy.array(y)
print("Array after inserting column 2 on axis 1")
sampleArray = numpy.insert(sampleArray,1,arr,axis=1)
print(sampleArray)
```
## Output
<img width="1140" height="717" alt="image" src="https://github.com/user-attachments/assets/0d1f342b-b75c-4db0-afc0-1c65a778c049" />

## Result
Thus, we were successfully able to write a **NumPy** program that deletes the second column from a given 2D array and inserts a new column at the same position.
