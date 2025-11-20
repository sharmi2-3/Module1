## PYTHON PROGRAMMING MODULE 1

## NAME : SHARMILA P
## REGISTER NUMBER : 212224220094


# 1a.Printing multiline strings in Python using triple quotes.

##  Aim
To write a Python program that prints a multiline string using triple single quotes and triple double quotes.


##  Algorithm
1.Create a multiline string using triple single quotes (''' ... ''').

2.Print the multiline string.

3.Create another multiline string using triple double quotes (""" ... """).

4.Print the second multiline string.

##  Program
```
str1='''I am a string literal
... has more than one
... line
....placed inside triple single quotes'''
str2="""I am a string literal
... has more than one 
... line
....placed inside triple double quotes"""
print(str1)
print(str2)
```

## Output

<img width="447" height="202" alt="image" src="https://github.com/user-attachments/assets/6e6b59e9-f096-47fd-8b19-9749db7fffef" />

## Result
The program successfully prints the multiline strings using both triple single quotes and triple double quotes.


# 1b.Datatypes-Boolean Expression Evaluation in Python

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



# 1c. Datatypes-Character Literal in Python

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


# 1d. Datatypes-Complex Number Creation in Python

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



# 1e.Datatypes-Printing vowels in Python using character literals.

##  Aim
To write a Python program that reads a character input and prints the vowel using a character literal.

##  Algorithm
1.Accept a character from the user.

2.Check if the character is one of the vowels (A, E, I, O, U, a, e, i, o, u).

3.If it is a vowel, print the same character.

4.End the program.

##  Program
```
a=input()
b=input()
a=a.upper()
b=b.upper()
if a in 'AEIOU':
    print(a)
if b in 'AEIOU':
    print(b)
```

## Output

<img width="439" height="112" alt="image" src="https://github.com/user-attachments/assets/4b6e751d-a0e9-4a75-9bfe-def92dc87cb0" />


## Result
The program successfully accepts a character from the user, checks whether it is a vowel, and prints the vowel as required.


