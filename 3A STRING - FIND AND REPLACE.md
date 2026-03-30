# Exp.No:3a
## STRING - FIND AND REPLACE

---

### AIM  
To write a Python function to accept a string, identify a word to be replaced, and replace it with a new word provided by the user.

---

### ALGORITHM

1. Begin the program.  
2. Input the original string `str1` and the word to be replaced `replace_str`.  
3. Ask the user to input the new replacement word `str2`.  
4. Use the `replace()` method in Python to replace all occurrences of `replace_str` in `str1` with `str2`.  
5. Store the modified string in `str3`.  
6. Display the original string (`str1`) and the modified string (`str3`).  
7. Terminate the program.

---

### PROGRAM

```
# Reg.No- 212222060008
# Name- AISHWARYA K
s = input()
n = len(s)
is_palindrome = True
for i in range(n // 2):
    if s[i] != s[n - 1 - i]:
        is_palindrome = False
        break
if is_palindrome:
    print("The entered string is palindrome")
else:
    print("The entered string is not palindrome")
```

### OUTPUT
<img width="856" height="200" alt="image" src="https://github.com/user-attachments/assets/f0a3be8e-aa63-4f25-8e94-4376b7f2a077" />

### RESULT
Thus, the Python program to check whether an entered string is a palindrome or not without using built-in functions has been successfully executed and the output is verified.
