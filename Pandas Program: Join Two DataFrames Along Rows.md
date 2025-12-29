# 🧪 Pandas Program: Join Two DataFrames Along Rows

## 🎯 AIM

To write a Python program using Pandas to **join two DataFrames along rows** (row-wise concatenation) and assign all data to a new DataFrame.

---

## 🧠 ALGORITHM

1. **Import Libraries**: Import the `pandas` library.
2. **Create First DataFrame**: Use a dictionary to create `student_data1`.
3. **Create Second DataFrame**: Use another dictionary to create `student_data2`.
4. **Concatenate DataFrames**: Use `pd.concat()` with `axis=0` to concatenate both DataFrames row-wise.
5. **Display Result**: Print the new combined DataFrame.

---

## 💻 Program
```
import pandas as pd 

student_data1 = pd.DataFrame({ 
'student_id': ['S1', 'S2', 'S3', 'S4', 'S5'], 
'name': ['Vecna', 'Lucas', 'Will', 'Mike', 'Dustin'],  
'marks': [13, 32, 90, 25, 19]}) 

student_data2 = pd.DataFrame({ 
'student_id': ['S4', 'S5', 'S6', 'S7', 'S8'], 
'name': ['Max', 'Hopper', 'Steve', 'Nancy', 'Jonathan'], 
'marks': [21, 92, 98, 21, 21]}) 

result_data = pd.concat([student_data1, student_data2]) 
print(result_data)
```
## Output
<img width="586" height="262" alt="image" src="https://github.com/user-attachments/assets/99c15e38-caec-44b3-86ee-51a4d5a3a3f4" />

## Result
Thus we were successfully able to write a Python program using Pandas to **join two DataFrames along rows** (row-wise concatenation) and assign all data to a new DataFrame.
