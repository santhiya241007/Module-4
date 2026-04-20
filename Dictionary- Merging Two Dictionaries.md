## Dictionary Operations in Python: Merging Two Dictionaries

## 🎯 Aim
To write a Python program that merges **two dictionaries** and combines their key-value pairs.

## 🧠 Algorithm
1. Define two dictionaries `dict1` and `dict2` with some key-value pairs.
2. Define a function `merge()` that merges the two dictionaries using the `**` unpacking operator.
   - The merged result will combine keys from both dictionaries. If a key exists in both, the value from `dict2` will overwrite that from `dict1`.
3. Call the `merge()` function and print the merged dictionary.

## 🧾 Program

a=eval(input())
b=eval(input())
c=a.copy()
c.update(b)
print(c)

## Output
<img width="867" height="231" alt="image" src="https://github.com/user-attachments/assets/d986dbd3-c564-4c82-a64e-9dde31d00352" />


## Result
Thus the prgram has been successfully executed.
