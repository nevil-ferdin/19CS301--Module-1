- **Name:** Nevil Joe Ferdin P  
- **Registration Number:** 212222050041
# 19CS301-Module-1
# Experiment No: 1a Python Basics- convert tuple to list.

## AIM  
To create a python program to read a tuple and convert it into a list.

## ALGORITHM  
**Step 1:** Start  
**Step 2:** Take a tuple as input from the user  
**Step 3:** Convert the tuple to a list  
**Step 4:** Use `filter()` to keep only the even numbers  
**Step 5:** Convert the filtered result to a list  
**Step 6:** Print the filtered list  
**Step 7:** End

## PROGRAM

# Reg no-212222050041
# Name-Nevil Joe Ferdin P

```python
tuple = eval(input("Enter a tuple: ")) 
T = list(tuple)
print(f"List={T}")


## OUTPUT

(https://github.com/user-attachments/assets/23afffaf-26cd-41d0-bf84-a00947eefbc0)


## RESULT 
Thus python program to read a tuple and convert it into a list was executed successfully.



# Experiment No: 1B- Data Types – Printing Complex Number.

## AIM  
Write a python program to read two numbers and convert and print them into a complex number.
## ALGORITHM  
**Step 1:** Start  
**Step 2:** Read an integer and store it in variable `a` (real part)  
**Step 3:** Read another integer and store it in variable `b` (imaginary part)  
**Step 4:** Create a complex number `c` using `a` and `b`  
**Step 5:** Print the complex number `c`  
**Step 6:** End

## PROGRAM
```python
# Reg.No-212222050041
# Name-Nevil Joe Ferdin P

a=int(input())
b=int(input())
c=complex(a,b)
print(c)

```
## OUTPUT ![image](https://github.com/user-attachments/assets/c6353a96-82e2-468b-bb42-5c3a1f0d5e0f)


## RESULT 
Thus python program to read two numbers and convert and print them into a complex number is successfully completed.


# Experiment No: 1c-Varibles and Expressions, Operators - using Assignment Operators

## AIM
To Write a python program using the assignment operator /=,%= on the given values.

## ALGORITHM
**Step 1:** Start  
**Step 2:** Read an integer `a` (denominator)  
**Step 3:** Read an integer `b` (numerator)  
**Step 4:** Read an integer `c`  
**Step 5:** Check if `a` is not zero  
&nbsp;&nbsp;&nbsp;&nbsp;→ **If yes**, go to Step 6  
&nbsp;&nbsp;&nbsp;&nbsp;→ **If no**, display an error message and **stop**  
**Step 6:** Calculate `d = b / a`  
**Step 7:** Print the value of `d`  
**Step 8:** Print the value of `c`  
**Step 9:** Stop

## PROGRAM
```python
# Reg.No-212222050041
# Name-Nevil Joe Ferdin

a=int(input())
b=int(input())
c=int(input())
d=b/a
print(d)
print(c)

```

## OUTPUT ![image](https://github.com/user-attachments/assets/7dc1b5d4-7935-44a9-9faa-ecbe2077b1dd)



## RESULT
Thus the python program using the assignment operator /=,%= on the given values executed successfully.


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
# Reg.No- 212222050041
# Name-Nevil Joe Ferdin P


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

# Experiment No: 1e – SEB-Maximum of Three Numbers

## AIM  
To write a Python program to find the maximum between three integer numbers using a conditional expression (Ternary operator).

## ALGORITHM  

**Step 1:** Begin the program  
**Step 2:** Read three numbers: `num1`, `num2`, and `num3`  
**Step 3:** Compare the three numbers to find the maximum:  
&nbsp;&nbsp;&nbsp;&nbsp;- If `num1` is greater than or equal to both `num2` and `num3`, then `num1` is the maximum  
&nbsp;&nbsp;&nbsp;&nbsp;- Else if `num2` is greater than or equal to both `num1` and `num3`, then `num2` is the maximum  
&nbsp;&nbsp;&nbsp;&nbsp;- Else, `num3` is the maximum  
**Step 4:** Print the maximum value in the format:  

## PROGRAM
```python
# Reg.No-21222205009
# Name-Nevil Joe Ferdin P
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
