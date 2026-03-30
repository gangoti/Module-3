# Exp.No:3d  
## TUPLES - A TUPLE WITH MULTIPLES OF 5

---

### AIM  
To write a Python program to create a tuple containing all multiples of 5 up to a given number **N**.

---

### ALGORITHM

1. Begin the program.  
2. Accept an integer `N` from the user.  
3. Use a generator expression inside the `tuple()` function to create a tuple `multiples_of_5` with values starting from `5` up to `N - 1`, stepping by `5`.  
4. Return the tuple `multiples_of_5`.  
5. Print the resulting tuple.  
6. Terminate the program.

---

### PROGRAM

```
N = int(input())
multiples_of_5 = tuple(i for i in range(5, N, 5))
print(multiples_of_5)
```

### OUTPUT
<img width="778" height="197" alt="image" src="https://github.com/user-attachments/assets/b708adee-fef6-4c4f-b115-64e1ff931ba8" />

### RESULT
Thus, the Python program to create a tuple containing all multiples of 5 up to a given number N has been successfully executed and the output is verified
