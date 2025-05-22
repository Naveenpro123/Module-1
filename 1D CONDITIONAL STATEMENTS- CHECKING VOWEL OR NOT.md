## Experiment No: 1d – Conditional Statements- Checking leap year or not

## AIM  
To Write a Python program to compute whether a given year is leap year or not
## ALGORITHM  


**Step 1:** Start  
**Step 2:** Input the year (let’s call it `year`)  
**Step 3:**  
&nbsp;&nbsp;&nbsp;&nbsp;If (`year % 4 == 0`) **AND** (`year % 100 != 0`)  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;→ Then it is a **leap year**  
&nbsp;&nbsp;&nbsp;&nbsp;Else if (`year % 400 == 0`)  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;→ Then it is a **leap year**  
&nbsp;&nbsp;&nbsp;&nbsp;Else  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;→ It is **not** a leap year  
**Step 4:** Display the result  
**Step 5:** Stop


 




## PROGRAM
```python
# Reg.No- 212222020029
# Name-Subashree A


year=int(input())
if((year%400==0)and(year%100==0)):
    print("Given year {} is a leap year".format(year))
elif (year%4==0) and (year%100!=0): 
    print("Given year {} is a leap year".format(year))
else :
    print("Given year {} is not a leap year".format(year))
    
```

## OUTPUT

![image](https://github.com/user-attachments/assets/96bb52ed-b9f8-4e96-ba33-16fbb78f1db1)

## RESULT
Thus the program is executed Successfully.
