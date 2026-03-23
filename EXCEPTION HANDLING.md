# Exp.No:4c
## EXCEPTION HANDLING

---

### AIM  
To create a Python program that prompts the user for a list of grades separated by commas, splits the string into individual grades, and uses exception handling to inform the user if the values they entered cannot be converted to integers.

---

### ALGORITHM

1. Begin the program.  
2. Read a string `input_str` from the user using `input()`.  
3. Split the input string using commas (`,`) to create a list of grades.  
4. Use a `try` block to attempt converting each item in the grades list to an integer and store the result in `l1`.  
5. If the conversion is successful, print the list `l1` containing the integer values.  
6. If an error occurs during conversion (for example, if the input is not a valid number), catch the exception and print an error message: `"The grades you entered were in an invalid format."` along with the original grades list.  
7. Terminate the program.

---

### PROGRAM

```
#Reg.No: 212222060074
#Name: Hariharan K
#Add Your Code Here
try:
    a=int(input())
    b=int(input())
    print(a+b)
except:
    print("cannot add integer with string")

```

### OUTPUT
<img width="1187" height="341" alt="image" src="https://github.com/user-attachments/assets/3bae5d21-8966-4bbd-9152-23199bf7c959" />


### RESULT
Therefore, the output is the example to create a Python program that prompts the user for a list of grades separated by commas, splits the string into individual grades, and uses exception handling to inform the user if the values they entered cannot be converted to integers.
