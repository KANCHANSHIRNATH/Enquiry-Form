Assignment 1:

 Q1. Why do we call Python as a general purpose and high-level programming language?
 Ans. Python is a general-purpose programming language as for its easy readability. This language has been used to create popular websites and products, including Instagram’s backend, Google, Spotify, Netflix, and more. Alsois its high level programming language as it is not tied to a system architecture. You can write Python code as well as run it on any device or computer.

 Q2. Why is Python called a dynamically typed language?
Ans. Python doesn't have problem even if we don't declare the type of variable. It define the type of variable in the runtime of the program. Python also take cares of the memory management which is crucial in programming. So, Python is a dynamically typed language.

Q3. List some pros and cons of Python programming language?
Ans. 
Pros:
1) Python is simple and easy to understand.
2) It is Interpreted and platform-independent which makes debugging very easy.
3) Python is an open-source programming language.
4) Python provides very big library support. Some of the popular libraries include NumPy, Tensorflow, Selenium, OpenCV, etc.
5) It is possible to integrate other programming languages within python.

Cons:
1) The program is not fast when executing codes.
2) Python not being great with mobile computing
3) While using Python , you can expect to see runtime errors because of the dynamical typing feature of this programming language.
4) Python consumes a lot of memory space
5) Not easy to test.

Q4. In what all domains can we use Python?
Ans. 
1) Python is used in Data Visualization to create plots and graphical representations.
2) Python helps in Data Analytics to analyze and understand raw data for insights and trends.
3) It is used in AI and Machine Learning to simulate human behavior and to learn from past data without hard coding.
4) It is used to create web applications.
5) It can be used to handle databases.
6) It is used in business and accounting to perform complex mathematical operations along with quantitative and qualitative analysis.

Q5. What are variable and how can we declare them?
Ans.
Variable is a name given to a specific memory location which stores the information that can be manipulated and referenced later by the programmer within the code. In python, the programmer does not need to declare the variable type explicitly, we just need to assign the value to the variable.
It is always advisable to keep variable names descriptive and to follow a set of conventions while creating variables:
i) Variable name can only contain alpha-numeric characters and underscores (A-z, 0-9, and _ )
ii) Variable name must start with a letter or the underscore character.
iii) Variables are case sensitive.
iv) Variable name cannot start with a number.
Example:

Color = "yellow"    #valid variable name
cOlor = "red"       #valid variable name
_color = "blue"     #valid variable name

5color = "green"    #invalid variable name
$color = "orange"   #invalid variable name

Scope of variable - The scope of the variable is the area within which the variable has been created. Based on this a variable can either have a local scope or a global scope.
A local variable is created within a function and can be only used inside that function. Such a variable has a local scope.
A global variable is created in the main body of the code and can be used anywhere within the code. Such a variable has a global scope.

Q6. How can we take an input from the user in Python?
Ans. In Python we can take input from user using function input()

input() - This function first takes the input from the user and converts it into a string. The type of the returned object always will be <type ‘str’>. When the input function is called it stops the program and waits for the user’s input. When the user presses enter, the program resumes and returns what the user typed. 

Ex: 
val = input("Enter your value: ")
print(val)

Output: Enter your value: 165
        165
        >>>

Q7. What is the default datatype of the value that has been taken as an input using input() function?
Ans. The default datatype of the value that has been taken as an input using input() function would be the string.

Q8. What is type casting?
Ans. Similar to type conversion, type casting is done when we want to specify a type on a variable. 

Example: 
str1 = "7"          
str2 = "3.142"
str3 = "13"
num1 = 29
num2 = 6.67

print(int(str1))
print(float(str2))
print(float(str3))
print(str(num1))
print(str(num2))

Output:

7
3.142
13.0
29
6.67

Q10. What are keywords?
Ans. Keywords in Python are reserved words that can not be used as a variable name, function name, or any other identifier.

We can also get all the keyword names using the below code.

# Python code to demonstrate working of iskeyword()
  
# importing "keyword" for keyword operations
import keyword
  
# printing all keywords at once using "kwlist()"
print("The list of keywords is : ")
print(keyword.kwlist)

The list of keywords is : 

[‘False’, ‘None’, ‘True’, ‘and’, ‘as’, ‘assert’, ‘async’, ‘await’, ‘break’, ‘class’, ‘continue’, ‘def’, ‘del’, ‘elif’, ‘else’, ‘except’, ‘finally’, ‘for’, ‘from’, ‘global’, ‘if’, ‘import’, ‘in’, ‘is’, ‘lambda’, ‘nonlocal’, ‘not’, ‘or’, ‘pass’, ‘raise’, ‘return’, ‘try’, ‘while’, ‘with’, ‘yield’]

Q11. Can we use keywords as a variable? Support your answer with reason.
Ans. The keyword cannot be used as an identifier, function, and variable name.

Q17. Write a code to take a number as an input from the user and check if the number is odd or even.
Ans. 
Number which odd or even:

Number = int(input("Enter a number:"))
if ( Number % 2 == 0 ):
        print("Number is even")
else:
        print("Number is odd")

Q22. Write a code to take the age of person as an input and if age >= 18 display "I can vote". If age is < 18 display "I can't vote".
Ans.

age = int(input("Enter Age:"))
if age >= 18:
     print ("I can vote")
else:
        print ("I can't vote")

Q24. Write a code to take 3 numbers as an input from the user and display the greatest no as output.
Ans.
a = int(input('Enter first number  : '))
b = int(input('Enter second number : '))
c = int(input('Enter third number  : '))

largest = 0

if a > b and a > c:
    largest = a
if b > a and b > c:
    largest = b
if c > a and c > b:
    largest = c

print(largest, "is the largest of three numbers.")


Q12 Indentation refers to the spaces at the beginning of a code line.

Ans. Where in other programming languages the indentation in code is for readability only, the indentation in Python is very important.

Python uses indentation to indicate a block of code.

Example
if 5 > 2:
  print("Five is greater than two!")

Q13. How can we throw some output in Python?
Ans. The basic way to do output is the print statement. To end the printed line with a newline, add a print statement without any objects. This will print to any object that implements write(), which includes file objects

Q14. What are operators in Python?
These are the special symbols in python and are used to execute an Arithmetic or Logical computation. An operator alone cannot perform an activity, it needs an Operand. What is an operand? An Operand is a value that the operator needs to complete a task.
We have multiple operators in Python, and each operator is subdivided into other operators. Let’s list them down and know about each operator in detail.

Arithmetic operators
Comparison operators
Assignment operators
Logical operators
Bitwise operators
Membership operators
Special operators
Identity operators
Membership operators

Q18. What are boolean operator?
Ans. The logical operators and, or and not are also referred to as boolean operators. While and as well as or operator needs two operands, which may evaluate to true or false, not operator needs one operand evaluating to true or false.

Boolean and operator returns true if both operands return true.

>>> a=50
>>> b=25
>>> a>40 and b>40
False
>>> a>100 and b<50
False
>>> a==0 and b==0
False
>>> a>0 and b>0
True
Boolean or operator returns true if any one operand is true

>>> a=50
>>> b=25
>>> a>40 or b>40
True
>>> a>100 or b<50
True
>>> a==0 or b==0
False
>>> a>0 or b>0
True
The not operator returns true if its operand is a false expression and returns false if it is true.

>>> a=10
>>> a>10
False
>>> not(a>10)
True

Q19. What will the output of the following?
```
1 or 0

0 and 0

True and False and True

1 or 0 or 0

Ans.

True
True
False
True

Q20. What are conditional statements in Python and What is use of 'if', 'elif' and 'else' keywords

A conditional statement as the name suggests itself, is used to handle conditions in your program. These statements guide the program while making decisions based on the conditions encountered by the program.

Python has 3 key Conditional Statements that you should know:

if statement
if-else statement
if-elif-else ladder

if Statement:
A simple if statement works on following principle,
execute the block of code inside if statement if the expression evaluates True.
ignore the block of code inside if statement if the expression evaluates False and return to the code outside if statement.
applePrice = 180
budget = 200
if (applePrice <= budget):
    print("Alexa, add 1kg Apples to the cart.")

if-else Statement
An if……else statement works on the following principle,

execute the block of code inside if statement if the expression evaluates True. After execution return to the code out of the if……else block.
execute the block of code inside else statement if the expression evaluates False. After execution return to the code out of the if……else block.
 applePrice = 210
budget = 200
if (applePrice <= budget):
    print("Alexa, add 1kg Apples to the cart.")
else:
    print("Alexa, do not add Apples to the cart.")

elif Statement
Sometimes, the programmer may want to evaluate more than one condition, this can be done using an elif statement.

 

An elif statement works on the following principle,

execute the block of code inside if statement if the initial expression evaluates to True. After execution return to the code out of the if block.
execute the block of code inside the first elif statement if the expression inside it evaluates True. After execution return to the code out of the if block.
execute the block of code inside the second elif statement if the expression inside it evaluates True. After execution return to the code out of the if block.
.
.
.
execute the block of code inside the nth elif statement if the expression inside it evaluates True. After execution return to the code out of the if block.
execute the block of code inside else statement if none of the expression evaluates to True. After execution return to the code out of the if block.
 
 num = 0
if (num < 0):
    print("Number is negative.")
elif (num == 0):
    print("Number is Zero.")
else:
    print("Number is positive.")

Nested if Statement
We can use if, if….else, elif statements inside other if statements. 
Example:

num = 18
if (num < 0):
    print("Number is negative.")
elif (num > 0):
    if (num <= 10):
        print("Number is between 1-10")
    elif (num > 10 and num <= 20):
        print("Number is between 11-20")
    else:
        print("Number is greater than 20")
else:
    print("Number is zero")

Q15. What is difference between / and // operators?
Ans.
Normal Division: Divides the value on the left by the one one the right. Notice that division results in a floating-point value
divide=10/3 #Normal Division

Print(divide)

Output: 3.333333333333

Floor Division: Divides and returns the integer value.

Q16. Write a code that gives following as an output.
```
iNeuroniNeuroniNeuroniNeuron
Ans.
print("iNeuron"*4)

Q23. Write a code that displays the sum of all the even numbers from the given list.
```
numbers = [12, 75, 150, 180, 145, 525, 50]
```
Ans. int_list = [12, 75, 150, 180, 145, 525, 50]
 
# iterating each number in list
list_sum = 0
for num in int_list:
 
    # checking condition
    if num % 2 == 0:
        list_sum = list_sum + num
print("total sum of even numbers=", list_sum)
   

Q25. Write a program to display only those numbers from a list that satisfy the following conditions

- The number must be divisible by five

- If the number is greater than 150, then skip it and move to the next number

- If the number is greater than 500, then stop the loop
```
numbers = [12, 75, 150, 180, 145, 525, 50]
```
Ans.
     def func(inputs):
      inputs = [int(i) for i in inputs]
      output = []
      for i in inputs:
          if i > 150:
              if i > 500:
                break
                continue
          if i % 5 == 0:
              output.append(i)
              return output
inputs = input().split(', ')
print(func(inputs))





