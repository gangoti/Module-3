# Exp.No:3b  
## REGEX - PATTERN MATCHING USING REGEX

---

### AIM  
To write a Python program that matches a string containing an `'a'` followed by **two to three `'b'` characters** using regular expressions.

---

### ALGORITHM

1. Begin the program.  
2. Accept a string `str1` from the user.  
3. Define the regular expression pattern as `r"[a]+b{2,3}"`.  
4. Use the `re.match()` function to check if the string `str1` matches the pattern.  
5. If a match is found, print `"Found a match!"`.  
6. If no match is found, print `"Not matched!"`.  
7. Terminate the program.

---

### PROGRAM
```
import re
str1 = input()
if re.match(r"^ab*$", str1):
    print("Found a match!")
else:
    print("Not matched!")
```
### OUTPUT
<img width="684" height="276" alt="image" src="https://github.com/user-attachments/assets/21bdea44-b196-4036-871f-5fb66648cc13" />

### RESULT
Thus, the Python program that matches a string beginning with "a" followed by zero or more b's using regular expressions has been successfully executed and the output is verified.

