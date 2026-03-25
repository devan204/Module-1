## Experiment No: 1d – Conditional Statements- Checking Number Type

## AIM  
To write a Python program that reads a number from the user and checks whether it is zero, positive, or negative using the if-elif-else statement.

## ALGORITHM  
1.Start the program.

2.Read a number from the user and store it in a variable (say num).

3.Check if the number is equal to 0 if True, print "Number is 0".

4.Else if the number is greater than 0,print that it is a positive number.

5.Else (the number is less than 0),print that it is a negative number.

6.End the program.

## PROGRAM
```python
# Write your code here

num = int(input())
if num>0:
    print(f"{num} is a Positive number")
elif num<0:
    print(f"{num} is a Negative number")
elif num==0:
    print("Number is 0")
else:
    print("invalid number")
```

## OUTPUT
![Screenshot (211)](https://github.com/user-attachments/assets/362f7e22-f505-4c4a-bfef-a25626d6e09a)

## RESULT
Thus the python program for Checking Number Type was implemented and executed successfully.
