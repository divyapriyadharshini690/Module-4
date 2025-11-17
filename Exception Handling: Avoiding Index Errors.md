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
```python
try:

n=int(input())

a = []

for i in range(1,n+1):

  n1=int(input()) 
  a.append(n1) 
  print(a) 
print(a[6])

except IndexError: print("6 is not accepted")
```

## Output

<img width="521" height="294" alt="489414061-55c21def-5965-4530-8151-bfcb8d67bdc3" src="https://github.com/user-attachments/assets/93187108-de38-4b98-94cb-d1c00c4666b4" />


## Result
Thus, To write a Python program that handles an IndexError when trying to access an element beyond the available range of a list is verified.
