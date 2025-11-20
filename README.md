## PYTHON PROGRAMMING MODULE 1

## NAME : SHARMILA P
## REGISTER NUMBER : 212224220094

# Conditional Statements in Python: Even or Odd Checker

##  Aim
To write a Python program to check whether the given number is **even** or **odd** using `if...else` statements.

##  Algorithm
1. Get an input from the user.
2. Convert the input to an integer and store it in a variable `a`.
3. Use the modulo operator `%` to check if `a % 2 == 0`.
   - If true, print `"EVEN"`.
   - Else, print `"ODD"`.
4. End the program.

##  Program :

```
a = int(input("Enter a number: "))
if a % 2 == 0:
    print("EVEN")
else:
    print("ODD")
```

## Output : 
<img width="390" height="315" alt="image" src="https://github.com/user-attachments/assets/2cf4719e-5edf-4f00-9971-890b6483a300" />

## Result :
Thus the program executed successfully.





# Datatypes-Boolean Expression Evaluation in Python

##  Aim
To write a Python program that evaluates and prints the results of boolean and arithmetic expressions involving `True` and `False`.

##  Algorithm
1.Compare 1 with True and store the result in variable a.

2.Compare 0 with False and store the result in variable b.

3.Add the boolean value True to the integer 5 and store the result in variable c.

4.Add the boolean value False to the integer 9 and store the result in variable d.

5.Print the value of a with the label "a is".

6.Print the value of b with the label "b is".

7.Print the value of c with the label "c:".

8.Print the value of d with the label "d:".

##  Program
```
a = (1 == True)
b = (0==False)
c = True + 5
d = False + 9
 
print("a is", a)
print("b is", b)
print("c:",c)
print("d:",d)
```


## Output
<img width="339" height="135" alt="image" src="https://github.com/user-attachments/assets/8634f435-9937-4647-a67f-830cd43e14e2" />


## Result
The program correctly evaluates the boolean and arithmetic expressions using True and False and prints their result



#  Datatypes-Character Literal in Python

##  Aim
To write a Python program that prints the characters `'v'` and `'c'` using character literals.

##  Algorithm
1. Print the character `'v'`.
2. Print the character `'c'`.

##  Program
```
str1='V'
str2='c'
print(str1)
print(str2)
```

## Output

<img width="342" height="101" alt="image" src="https://github.com/user-attachments/assets/9224db61-c82b-4008-abed-7b280dcd5e00" />



## Result
The python program successfully prints the characters 'v' and 'c' using character literals


#  Datatypes-Complex Number Creation in Python

##  Aim
To write a Python program that reads two integers, creates a complex number using them, and then prints the complex number along with its real and imaginary parts.

##  Algorithm
1. Read an integer input from the user and assign it to the variable `c1` (real part).
2. Read another integer input from the user and assign it to the variable `c2` (imaginary part).
3. Create a complex number `sum` using the `complex(c1, c2)` function.
4. Print the complex number `sum`.
5. Print the real part of `sum` using `sum.real`.
6. Print the imaginary part of `sum` using `sum.imag`.

##  Program
```
c1=2+3j
c2=4+7j
sum=c1+c2
print(sum)
```

## Output
<img width="341" height="95" alt="image" src="https://github.com/user-attachments/assets/62d36fa0-9e7e-4c64-a8f3-f2e749b7316d" />


## Result
The program successfully adds the two complex numbers c1 and c2 and prints their


# Datatypes-Read and Print a String in Python

##  Aim
To write a Python program to read a string from the user and then print it.

##  Algorithm
1. Assign a variable named `men_stepped_on_the_moon`.
2. Use `input()` to read a string from the user and store it in the variable.
3. Print the value stored in the variable.

## Program
```
men_stepped_on_the_moon=input()
print(men_stepped_on_the_moon)

```
## Output
<img width="1057" height="231" alt="image" src="https://github.com/user-attachments/assets/b98270b1-30bd-44ca-b165-f5c2cd930580" />

## Result
Therefore To write a Python program to read a string from the user and then print it is compiled and the output is verified successfully



