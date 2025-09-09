# Exp.No:3b  
## REGEX - PATTERN MATCHING USING REGEX

### AIM  
To Write a Python program that matches a string that begins with "a" followed by zero or more b's .

### ALGORITHM

1. Begin the program.  
2. Accept a string `str1` from the user.  
3. Define the regular expression pattern as `r"[a]+b{2,3}"`.  
4. Use the `re.match()` function to check if the string `str1` matches the pattern.  
5. If a match is found, print `"Found a match!"`.  
6. If no match is found, print `"Not matched!"`.  
7. Terminate the program.

### PROGRAM

```
Reg No-212222060126
Name - kristipati Shivani

import re
str=input()
pattern='^[a(b*)]+$'
x=re.search(pattern,str)
if x:
    print("Found a match!")
else:
    print("Not matched!")
```
### OUTPUT
<img width="1229" height="362" alt="image" src="https://github.com/user-attachments/assets/38bbbaff-305e-43d7-9de4-2931cc7af40a" />

### RESULT
Thus a Python program that matches a string that begins with "a" followed by zero or more b's has been successfully implemented.
