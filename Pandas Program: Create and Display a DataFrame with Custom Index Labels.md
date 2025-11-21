# Pandas Program: Create and Display a DataFrame with Custom Index Labels

## 🎯 Aim

To create and display a **DataFrame** using the **Pandas** library in Python from a given dictionary, and apply specific index labels to the rows.

---

## 🧠 Algorithm

1. **Import Libraries**: Import the required libraries – `pandas` and `numpy`.
2. **Create Dictionary**: Define a dictionary `exam_data` with keys: `'name'`, `'score'`, `'attempts'`, and `'qualify'`.
3. **Index Labels**: Create a list of custom index labels called `labels`.
4. **Create DataFrame**: Use `pd.DataFrame()` to create the DataFrame by passing the dictionary and index labels.
5. **Display Output**: Display the DataFrame using `print()` or by simply calling the DataFrame variable.

---

## 💻 Program
```
import numpy as np
import pandas as pd
exam_data=eval(input())
lab=np.array(eval(input()))
df=pd.DataFrame(exam_data,index=lab)
print(df)
```

## Output
<img width="802" height="201" alt="image" src="https://github.com/user-attachments/assets/22da09e7-25d7-4948-9733-643b522f1c43" />

## Result
Thus,the program has been executed successfully.
