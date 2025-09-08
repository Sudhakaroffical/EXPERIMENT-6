## NAME: SUDHAKAR K
## REGNO: 212222240107
# EXPERIMENT-6

## AIM:To write a Python program for checking Palindrome and to write test cases for ir. 

## ALGORITHM
Step 1: Start

Step 2: Get an input from the user by prompting

Step 3: Run a loop form 0 to len/2.

Step 4: Check if the characters are the same both from the start and the end till len/2.

Step 5: If it is, return the result that it is a palindrome.

Step 6: Else, return that it is not a palindrome.

Step 7: Stop. 

## PROGRAM
```python
def Palindrome(string): 
    for i in range(0, int(len(string)/2)): 
        if(string[i]!=string[len(string)-i-1]):
            return False 
        return True
print("Enter a valid string") 
s = input() 
c = 1 
for i in s: 
    if not(i.isalpha()):  
        c = 0 
if(c==0):   
    answer = Palindrome(s)  
    if(answer == True): 
        print("The given string is a palindrome") 
    else: 
        print("The given string is not a palindrome") 
else:
    print("Entered string is not valid") 

```

## OUTPUT

![image](https://github.com/user-attachments/assets/34d6937b-de78-4871-b1d3-901b113b8c8b)

![image](https://github.com/user-attachments/assets/1dc116a5-2e9f-4bfd-86a4-67331838cb5a)

![image](https://github.com/user-attachments/assets/ac255c59-eacf-4fb4-8dfa-155c40daa2d6)

![image](https://github.com/user-attachments/assets/4cab7ff9-3e44-4785-99bf-2d9492f8bf6f)

![image](https://github.com/user-attachments/assets/e5c6698d-558d-4d05-9a9c-0c49f7203160)

## RESULT
Thus, a program to check palindrome has been written and test cases have been written and verified
successfully. 
