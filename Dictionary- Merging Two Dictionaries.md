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
dict2 = {'b': 20, 'c': 30, 'd': 40}
def merge(d1, d2):
    return {**d1, **d2}  
merged_dict = merge(dict1, dict2)
print("Merged dictionary:", merged_dict)
```

## Output
![439086636-43f379b1-bb6e-4b5b-9dcd-5fc4f0566b85](https://github.com/user-attachments/assets/654c8485-ec11-4dbd-8185-6d5cd1a15674)

## Result
Hence the program executed successfully!
