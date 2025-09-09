# Exp.No:3a STRING - ACCEPT AND JOIN CHARACTERS OF STRING
# AIM
To write a Python program to Count the common characters in the Two Inputted Strings "mobile" and "laptop".

# ALGORITHM
Start Input the first string → str1 Input the second string → str2 Initialize an empty list or set → common_chars For each character ch in str1: If ch is also present in str2 And ch is not already in common_chars Then add ch to common_chars Display all characters in common_chars as common characters. End

# PROGRAM

212222060126-kristipati shivani

def cc(s1,s2):
    ccc=[char for char in s1 if char in s2]
    for char in ccc:
        print(char)
    if ccc:
        print("are the common characters")
    else:
        print("There are no common characters")
s1=input()
s2=input()
cc(s1,s2)
# OUTPUT
<img width="1213" height="544" alt="image" src="https://github.com/user-attachments/assets/1b84544e-1f24-4c75-8fa5-ced49d551c81" />

# Result:
Thus the program that defines a function to Count the common characters in the Two Inputted Strings has been implemented and executed successfully.

# Exp.No:3b REGEX - PATTERN MATCHING USING REGEX
# AIM
To write a Python program that matches a string containing only a certain set of characters (in this case a-z, A-Z and 0-9) using regular expressions.

# ALGORITHM
Start Input the string → str1 Define the allowed character set → allowed = [a–z, A–Z, 0–9] For each character ch in str1: If ch is not in the allowed set → Return False (string contains invalid characters) If loop completes without invalid characters → Return True End

# PROGRAM
# 212222060126- Kristipati shivani

import re 
s=input()
if re.search(r'^[a-zA-Z0-9]+$',s):
    print(True)
else:
    print(False)
# OUTPUT
<img width="1192" height="347" alt="image" src="https://github.com/user-attachments/assets/ada17e52-34d1-4245-8d36-cfdee4e73182" />

# RESULT
Thus the program matches a string containing only a certain set of characters (in this case a-z, A-Z and 0-9) using regular expressions has been implemented and executed successfully.

# Exp.No:3c LIST - EVEN NUMBERS LIST
# AIM
To write a Python function that creates a list of even numbers from 12 to n and prints the list and its sum.

# ALGORITHM
Start the program. Define a function named createlist that accepts a single parameter n. Initialize an empty list l. Iterate from 12 to n-1 using a for loop: For each number i in the range: Check if i is even using the condition i % 2 == 0. If the condition is true, append i to the list l. After the loop ends, print the list using print("List =", l). Calculate the sum of the list using sum(l) and print the result. End the function. Terminate the program.

# PROGRAM
# 212222060126-kristipati shivani


def createlist(n):
    l=[]
    for i in range(12,n):
        if i%2==0:
            l.append(i)
    print("List =",l)
    print("Sum of the list",sum(l))
# OUTPUT
<img width="1256" height="312" alt="image" src="https://github.com/user-attachments/assets/dcd8bd63-5c89-4db4-81c8-eadded3ff5eb" />

# RESULT
Thus the program that creates a list of even numbers from 12 to n and prints the list and its sum has been implemented and executed successfully.

# Exp.No:3d TUPLES - A TUPLE WITH MULTIPLES OF 3
# AIM
To create a tuple of multiples of 3 up to N and print the tuple and its length.

# ALGORITHM
Start the program. Accept input from the user for the value of N. Initialize an empty list a. Loop from 1 to N - 1: For each number i, check if it is divisible by 3 using i % 3 == 0. If true, append i to the list a. Convert the list a into a tuple b. Print the tuple b. Print the length of the tuple using len(b). End the program.

# PROGRAM
# 212222060126-kristipati shivani


n=int(input())
a=[]
sum=0
for i in range(3,n):
    if(i%3==0):
        a.append(i)
        sum+=i
b=tuple(a)
print(b)
print(f"Sum is",sum)
# OUTPUT
<img width="1187" height="354" alt="image" src="https://github.com/user-attachments/assets/cea36869-4871-47bf-be6d-7e41ea48f2be" />

# RESULT
Thus the program to create a tuple of multiples of 9 up to N and print the tuple and its length has been implemented and executed successfully.

# Exp.No:3e SEB - STRING SPLITTING
# AIM
To write a Python function that splits an email ID string into two parts using the "@" symbol.

# ALGORITHM
Start the program. Define a function named splitstring that accepts one argument a. Inside the function, use the built-in split('@') method to split the string at the "@" symbol. Store the result in a variable x. Print the resulting list x. Call the function with a test email ID. End the program.

# PROGRAM
# 212222060126-kristipati shivani

def splitstring(a): x=a.split('@') print(x)
# OUTPUT
<img width="1223" height="344" alt="image" src="https://github.com/user-attachments/assets/40517395-c9ca-4961-a280-7f1faea4310e" />

# RESULT
Thus the program that splits an email ID string into two parts using the "@" symbol has been implemented and executed successfully.
