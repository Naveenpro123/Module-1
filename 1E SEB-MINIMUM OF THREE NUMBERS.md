# Experiment No: 1e – SEB-Maximum of Three Numbers

## AIM  
To write a Python program to find the maximum between three integer numbers using a conditional expression (Ternary operator).

## ALGORITHM  
**Step 1:** Begin the program  
**Step 2:** Read three numbers: `num1`, `num2`, and `num3`  
**Step 3:** Compare the three numbers to find the minimum:  
&nbsp;&nbsp;&nbsp;&nbsp;- If `num1` is less than or equal to both `num2` and `num3`, then `num1` is the minimum  
&nbsp;&nbsp;&nbsp;&nbsp;- Else if `num2` is less than or equal to both `num1` and `num3`, then `num2` is the minimum  
&nbsp;&nbsp;&nbsp;&nbsp;- Else, `num3` is the minimum  
**Step 4:** Print the minimum value in the format: 

## PROGRAM
```python
# Reg.No-212222020029
# Name-SubashreeA
# Write your code here

num1 = int(input())
num2 = int(input())
num3 = int(input())

min_num = num1 if (num1 <= num2 and num1 <= num3) else num2 if (num2 <= num1 and num2 <= num3) else num3

print(f"The maximum of {num1}, {num2}, {num3} is {min_num}")
```

## OUTPUT
![image](https://github.com/user-attachments/assets/fd7d1550-cb69-4a2c-ab78-03c3f739bde0)


## RESULT
Thus the program is executed Successfully.
