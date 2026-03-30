# Exp.No:3e
## SEB - STRING SLICING

---

### AIM  
To write a Python function that accepts a string and forms a new string by reversing the characters from the **4th position to the 10th position** with **alternate characters**, and then prints the new string.

---

### ALGORITHM

1. Begin the program.  
2. Accept a string as input.  
3. Take a slice of the input string from index **2** to **10** (Python uses 0-based indexing, so index 2 refers to the 3rd character, i.e., the 4th character in natural terms).  
4. Reverse the sliced substring.  
5. Extract every second character from the reversed substring using slicing (`[::2]`).  
6. Print the final processed string.  
7. Terminate the program.

---

### PROGRAM

```
t = eval(input())
print("Initially the tuple is :", t)
d = {}
for item in t:
    if item[0] in d:
        d[item[0]] += item[1:]
    else:
        d[item[0]] = list(item)
result = tuple(tuple(v) for v in d.values())
print("Joined tuple :", result)
```

### OUTPUT
<img width="1340" height="157" alt="image" src="https://github.com/user-attachments/assets/8da5c86f-4a72-4d47-9763-a30b5a3984de" />

### RESULT
Thus, the Python program to join tuples with similar initial elements has been successfully executed and the output is verified.
