# Exp.No:2b  
## FUNCTIONS - # AVERAGE OF THREE NUMBERS

## Aim
To create a Python program that defines a function to accept three values and return their average.

## Algorithm
1. Begin the program.
2. Define a function `result(a, b, c)` that:
   - Calculates the average of the three values.
   - Returns the average.
3. Read three integer values from the user.
4. Call the function with the three input values.
5. Print the returned average.
6. Terminate the program.

## Program
```python
def result(a, b, c):
    avg = (a + b + c) / 3
    return avg

a = int(input("Enter first number: "))
b = int(input("Enter second number: "))
c = int(input("Enter third number: "))

average = result(a, b, c)
print(f"Average is {average}")
```

### OUTPUT
![image](https://github.com/user-attachments/assets/0e472376-458e-4f7a-9028-2b39997241cf)

### RESULT
Thus, the Python program was successfully executed to define a function that accepts three values and returns their average.


