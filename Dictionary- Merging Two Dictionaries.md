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
dict1 = eval(input())
dict2 = eval(input())
def merge(d1, d2):
    merged_dict = {**d1, **d2}
    return merged_dict
result = merge(dict1, dict2)
print(result)
```
## Output
<img width="1207" height="355" alt="568912168-b587beb2-3afd-4179-b4d3-8aa3d5a86160" src="https://github.com/user-attachments/assets/0f5a8ed1-790b-4723-bf90-e96371773a24" />


## Result
Thus the program executed successfully.

