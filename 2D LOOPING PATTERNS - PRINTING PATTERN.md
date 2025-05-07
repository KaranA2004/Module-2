# Exp.No:2d
## LOOPING PATTERNS - PRINTING PATTERN

# Alternate Number Pattern in Python

## Aim
To write a Python program to print an alternate number pattern, where each row contains repeated odd numbers.

## Algorithm
1. Begin the program.
2. Use `input()` to get the number of rows.
3. Use a `for` loop to iterate from 1 to `rows`.
4. For each row `i`, calculate the value `2 * i - 1`.
5. Print this value `i` times separated by spaces.
6. Terminate the program.

## Program
```python
rows = int(input("Enter number of rows: "))
for i in range(1, rows + 1):
    print(' '.join([str(2 * i - 1)] * i))

```

### OUTPUT
![image](https://github.com/user-attachments/assets/ee4b73db-8979-4a6a-bf8d-926e5589db57)

### RESULT
Thus, the Python program was successfully executed to print an alternate number pattern based on the number of rows entered by the user.
