## Assignment Part-1
Q1. Why do we call Python as a general purpose and high-level programming language?

ANS:
    Python is simple and readable, It's syntax is easy to learn and understand, which makes it a popular choice for beginners and experienced programmers.

    Python is a general-purpose programming language because it can be used to build any type of software. some of the areas
    where python is commonly used include data analysis, artificial intelligent, web development, desktop application and 
    scientific computiing etc.

    Python is also considered as high level programming language because, user no need to worry about many of the details underlying software and hardware resources, which makes it easier for developer to write complex programs as they can focus on logic and functionality of the software rather than worrying about low level details.
    

Q2. Why is Python called a dynamically typed language?

ANS:
    Python is considered a dynamically typed language because it checks the type of the declared variable during runtime rather than at compile time, That means we do not need to specify the type of the variable when we declare it and we can change the type of the variable over the course of the program.    

Q3. List some pros and cons of Python programming language?

ANS:
    Pros:
        *Python is easy, simple,and understandable
        *Python is versatile
        *It is high level programing language
        *It has strong support for object oriented programsming which makes it good choice for developing large and complex software system.
    Cons:
        *It is slower than compiled languages.
        *limited support for mobile applications development.
        *Python may not be the best choice for tasks that require high computation and real-time processing.


Q4. In what all domains can we use Python?

ANS:
    1. Automation
    2. web development
    3. scientific computation
    4. data analysis
    5. Artificail intelligence
    6. Machine learning
    7. Gaming
    8. Desktop application
    7. system administration



Q5. What are variable and how can we declare them?

ANS:
    Variable is a name that refers to a value in computer's memory. It hold a data in program and it can be used to represent different data types such as integer, floats, strings ,lists, and dictionaries.
    we can declare a variable simply by assigning a value to a name

        example:
                y=5
                name='teja'
                n_list=[1,2,3,4]



Q6. How can we take an input from the user in Python?

ANS:
    We can take an input from user using input() function 
    example:
            name=input("Enter your name")
    above example asks a user to enter the name


Q7. What is the default datatype of the value that has been taken as an input using input() function?

ANS:
    Default datatype if the value that has been taken as an input using input() function is "string"

Q8. What is type casting?

ANS:
    Type casting is a changing the data type of the variable
    example:
            a=10.2 # variable 'a' is of type float
            b=int(a) # varable 'a' is type casted to integer data type

Q9. Can we take more than one input from the user using single input() function? If yes, how? If no, why?

ANS:
    Yes we can take more than one input from the user using single input() function
    For example:
                x,y,z=input("enter three values").split(',')

Q10. What are keywords?

ANS:
    Keywords are words that have a specific meaning in the language, keywords can not be used as a variable.
    There are 33 keywords in python.

Q11. Can we use keywords as a variable? Support your answer with reason.

ANS:
    We can not use keywords as a variable. Keywords are reserved words in python and they have specific meaning and purpose.
    If we use keyword as a variable then it will throw a syntax error.

Q12. What is indentation? What's the use of indentaion in Python?

ANS:
    Indentation consists of spaces or tabs. It is important in python to indicate the structure of the code. 
    Level of indentation indicates which lines of code belong to particuler block.
    It helps to visualize the code and makes it to understand the structure and flow of the program.


Q13. How can we throw some output in Python?

ANS:
    Using print() function we can throw output in python

Q14. What are operators in Python?

ANS:
    Operators are symbols in python that performs specific operation on one or more values or variables.
    they performs calculation and comparison operation on operands 


Q15. What is difference between / and // operators?

ANS:
    The '/' and '//' both performs division operation. '/' returns a float result and '//' returns a integer result
    For example:
                3/2=1.5
                3//2=1

Q16. Write a code that gives following as an output.
```
iNeuroniNeuroniNeuroniNeuron
```
ANS:
    name="iNeuron"
    name=name*4
    print(name)

Q17. Write a code to take a number as an input from the user and check if the number is odd or even.

ANS:

    x=int(input("Enter the number: "))
    if x%2==0:
        print(f"{x} is a even number")
    else:
        print(f"{x} is a odd number")

Q18. What are boolean operator?

ANS:
    Boolean operators used to perform logical operation on boolean values. There three boolean opearators
        1. and
        2. or
        3. not


Q19. What will the output of the following?
```
1 or 0

0 and 0

True and False and True

1 or 0 or 0
```
ANS:
    1 or 0 -------> 1
    0 and 0 ------> 0
    True and False and True--------> False
    1 or 0 or 0----------> 1



Q20. What are conditional statements in Python?

ANS:
    In Python, conditional statements are used to execute certain pieces of code only if certain conditions are met. 
    There are two types of conditional statements: if statements and if-else statements.


Q21. What is use of 'if', 'elif' and 'else' keywords?

ANS:
    The if, elif, and else keywords are used in Python to control the flow of a program based on different conditions.
    The if keyword is used to specify a condition, and the code block following the if statement will be executed only if the condition is True.
    The elif keyword is used to specify additional conditions to test, if the previous conditions are all False. An elif clause is like an if statement, but it is only checked if all of the previous if and elif conditions are False. 
    The else keyword is used to specify a code block to be executed if all of the previous conditions are False.

Q22. Write a code to take the age of person as an input and if age >= 18 display "I can vote". If age is < 18 display "I can't vote".

ANS:
    age=int(input("Enter your age:"))
    if age>=18:
        print("I can vote")
    else:
        print("I can't vote")


Q23. Write a code that displays the sum of all the even numbers from the given list.
```
numbers = [12, 75, 150, 180, 145, 525, 50]
```
ANS:
    sum_even=[x for x in numbers if x%2==0]
    print(sum_even)     


Q24. Write a code to take 3 numbers as an input from the user and display the greatest no as output.

ANS:
    x,y,z=input("Enter three numbers seperated by comma: ").split(',')
    x=int(x)
    y=int(y)
    z=int(z)
    print("Greates number is",max(x,y,z))

Q25. Write a program to display only those numbers from a list that satisfy the following conditions

- The number must be divisible by five

- If the number is greater than 150, then skip it and move to the next number

- If the number is greater than 500, then stop the loop
```
numbers = [12, 75, 150, 180, 145, 525, 50]
```
ANS:
```
    numbers = [12, 75, 150, 180, 145, 525, 50]
    result=[]
    for element in numbers:
        if element>500:
            break
        elif element>150:
            continue
        elif element%5==0:
            result.append(element)
    print(result)
 ```
