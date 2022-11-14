PythonAssignment-1
Name: Syed Abrar
email: smabrar04@gmail.com

-------------------------------------------------------------------------------------------

Q1. Why do we call Python as a general purpose and high-level programming language?
sol.

Python is a general purpose and high level language as It is written in human readbale format and as it can be used in developing software solutions for multiple different problems irrespective of the system configuration, operating system etc.. 

--------------------------------------------------------------------------------------------

Q2. Why is Python called a dynamically typed language?
sol.

In python the type of varibale is determined at the time of runtime hence python is a dunamically typed language 

--------------------------------------------------------------------------------------------


Q3. List some pros and cons of Python programming language?
sol.

pros:
Open Source
Easy
Plenty of Libraries
Can be used for WebDev,Iot,ML,DL etc..

cons:
slow compared to other languages
high memory consumption
complex multithreading

--------------------------------------------------------------------------------------------

Q4. In what all domains can we use Python?
sol.

Python Can be used for
software development
web development
GUI development
Testing
Machine Learning ,Deep Learning, Data Science
IOT, embedded systmes

--------------------------------------------------------------------------------------------

Q4. In what all domains can we use Python?
sol.

Python Can be used for
software development,web development,GUI development,Testing,Machine Learning ,Deep Learning, Data Science,IOT, embedded systme

--------------------------------------------------------------------------------------------

Q5. What are variable and how can we declare them?
sol.

variables are for storing data values
variables are declared
a=1
b='hello'
c=2.0
d=True

--------------------------------------------------------------------------------------------

Q6. How can we take an input from the user in Python?
sol.

to take input in python , we use input() method
the input can be typecasted as per the type required or the default input is a string

name=input("ENTER YOUR NAME")
age=int(input("ENTER AGE))

--------------------------------------------------------------------------------------------

Q7. What is the default datatype of the value that has been taken as an input using input() function?
sol.

In python the default input() returns a string data type


Q8. What is type casting?
sol.

Type casting is used to convert a variable of one data type to another data type as per requirement.
- Implicit Type Casting (Automatic)
- Explicit Type Casting (By theUser)

example:
a=5
b=float(a)
print(type(a)) #<class 'int'>
print(type(b)) #<class 'float'>

c=1.1
d=int(c)
print(type(c)) #<class 'float'>
print(type(d)) #<class 'int'>

--------------------------------------------------------------------------------------------

Q9. Can we take more than one input from the user using single input() function? If yes, how? If no, why?
sol.

No, input() can only take one input as a it is string data type.

--------------------------------------------------------------------------------------------

Q10. What are keywords?
sol.

Keywords are reserved words in Python that can be used while declaration of variables, identifers ..
There are 33 keywords
examples :
print,and,or,not,in,if .....

--------------------------------------------------------------------------------------------

Q11. Can we use keywords as a variable? Support your answer with reason.
sol.

NO, keywords can not be used as variables, as they are used ti define syntax and the structure of python programming language.

--------------------------------------------------------------------------------------------

Q12. What is indentation? What's the use of indentaion in Python?
sol.

Indentation is the white space added before a statement or block of code.  & formatting alignment technique to improve readability and structure.
example:

age=20
if age>18:
    print("CAN VOTE")
else:
    print("CANT VOTE")
    
--------------------------------------------------------------------------------------------

Q13. How can we throw some output in Python?
sol.

print() is the used to print or output
return also throws output given a function

--------------------------------------------------------------------------------------------

Q14. What are operators in Python?
sol.

Python operators are used to perform operation on values 
Types of operators:
* Arithmetic operators (+,-,*,/,%,**,//)
* Assignment operators (=,|=,+=,-=,*=,/=,%=,//=,**=,&=,^=,>>=,<<=)
* Comparison operators (==,!=,>,<,>=,<=)
* Logical operators (and,or,not)
* Identity operators (is,not)
* Membership operators (in,not)
* Bitwise operators (&,|,^,~,<<,>>)
* 
--------------------------------------------------------------------------------------------

Q15. What is difference between / and // operators?
sol.

/ is regular division
// is floor division

example:
x=5/2
y=5//2
print(x) # 2.5
print(y) # 2

--------------------------------------------------------------------------------------------

Q16. Write a code that gives following as an output.
```
iNeuroniNeuroniNeuroniNeuron
```
sol.
# approach 1
print("iNeuroniNeuroniNeuroniNeuron")
# approach 2
print("iNeuron"*4)

--------------------------------------------------------------------------------------------

Q17. Write a code to take a number as an input from the user and check if the number is odd or even.
sol.
# even or odd
myNumber=int(input("ENTER NUMBER: "))
if myNumber%2==0:
    print(f"{myNumber} is even")
else:
    print(f"{myNumber} is odd")
    
--------------------------------------------------------------------------------------------

Q18. What are boolean operator?
sol.

Boolean operators take Boolean input and return Boolean output
True,False,not,and,or 
# examples
True or True # True
True or False # True
True and True # True
True and False # False

--------------------------------------------------------------------------------------------

Q19. What will the output of the following?
```
1 or 0

0 and 0

True and False and True

1 or 0 or 0
```
sol.
1
0
False
1

--------------------------------------------------------------------------------------------

Q20. What are conditional statements in Python?
sol.
Conditional Statements are used to control the flow of execution of programs. THey are the decision making statements
Type:
* if
* if-else
* elif
* nested if and if-else
* elif ladder

#IF
if age>18:
    print('VOTER')

#IF-ELSE
if age>18:
    print('VOTER')
else:
    print('NOT VOTER')

#ELIF
#ELIF LADDER
if (marks>91 && marks<=100):
    print('A grade')
elif (marks>81 && marks<=90):
    print('B grade')
else:
    print('NO GRADE')

#NESTED IF and IF-ELSE
if (num>0):
    print("POSITIVE")
    if(num%2==0):
        print("EVEN")
    else:
        print("ODD")
elif (num<0):
    print("NEGATIVE")
    if(num%2==0):
        print("EVEN")
    else:
        print("ODD")
else:
    print("ZERO")

--------------------------------------------------------------------------------------------

Q21. What is use of 'if', 'elif' and 'else' keywords?
sol.

if,elif,else are used to control the flow of the program,they are decision making statements
#examples in Q20.

--------------------------------------------------------------------------------------------

Q22. Write a code to take the age of person as an input and if age >= 18 display "I can vote". If age is < 18 display "I can't vote".
sol.

# VOTER
myAge=int(input("ENTER AGE: "))
if myAge>=18:
    print("I can vote")
else:
    print("I can't vote")
    
--------------------------------------------------------------------------------------------

Q23. Write a code that displays the sum of all the even numbers from the given list.
```
numbers = [12, 75, 150, 180, 145, 525, 50]
```
sol.
numbers = [12, 75, 150, 180, 145, 525, 50]
sum=0
for i in range(len(numbers)):
    if numbers[i]%2==0:
        sum+=numbers[i]
print(f"SUM of even numbers from {numbers} is {sum}")
#SUM of even numbers from [12, 75, 150, 180, 145, 525, 50] is 392

--------------------------------------------------------------------------------------------

Q24. Write a code to take 3 numbers as an input from the user and display the greatest no as output.
sol.

num1 = int(input("Enter first number: "))
num2 = int(input("Enter second number: "))
num3 = int(input("Enter third number: "))

if (num1 >= num2) and (num1 >= num3):
   largest = num1
elif (num2 >= num1) and (num2 >= num3):
   largest = num2
else:
   largest = num3

print(f"The largest number is {largest}")
'''
Enter first number: 5
Enter second number: 10
Enter third number: 7
The largest number is 10
'''

--------------------------------------------------------------------------------------------

Q25. Write a program to display only those numbers from a list that satisfy the following conditions

- The number must be divisible by five

- If the number is greater than 150, then skip it and move to the next number

- If the number is greater than 500, then stop the loop
```
numbers = [12, 75, 150, 180, 145, 525, 50]
```
sol.

numbers = [12, 75, 150, 180, 145, 525, 50]
for i in numbers:
    if i>500:
        break
    elif i%5==0:
        if i>150:
            continue
        print(i)
        
--------------------------------------------------------------------------------------------   
