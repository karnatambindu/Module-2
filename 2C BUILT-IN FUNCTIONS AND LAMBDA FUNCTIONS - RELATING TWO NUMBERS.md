# Exp.No:2c BUILT-IN FUNCTIONS AND LAMBDA FUNCTIONS - RELATING TWO NUMBERS
# AIM
To write a Python program to check the relation between two numbers — whether one number is greater than, equal to, or lesser than another — using a lambda function.

# ALGORITHM
1. Begin the program.
2. Read two numbers input1 and input2 from the user using input().
3. Convert the inputs to integers using int(). Define a lambda function compare that takes two arguments a and b.
4. The lambda function performs the following comparisons: If a > b, it returns the string: "a is greater than b".
5. Else if a < b, it returns the string: "a is smaller than b". Else, it returns: "a is equal to b".
6. Call the compare function with input1 and input2 as arguments. Print the result of the comparison.
7. Terminate the program.

# PROGRAM
212223060113-Karnatam Bindu
```
result = lambda x,y : f"{x} is smaller than {y}" if x < y else (f"{x} is greater than {y}" if x > y                else f"{x} is equal to {y}")
a=int(input()) 
b=int(input()
print(result(a, b))
```
# OUTPUT
<img width="1175" height="321" alt="image" src="https://github.com/user-attachments/assets/d15c4ba3-4f19-4da2-9072-534e1d34e7a2" />

# RESULT
Thus the program to check the relation between two number using lambda function has been implemented and executed successfully.
