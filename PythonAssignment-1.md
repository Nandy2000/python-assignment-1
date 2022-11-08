## Assignment Part-1
Q1. Why do we call Python as a general purpose and high-level programming language?

 Python codes are written in human readable form and Python can be used in many domains such as software developement , data domain , web developement , game developement etc. 

Q2. Why is Python called a dynamically typed language?

Pyhthon is called a dynamically typed language because the  type of the vaariable is declared during the runtime / the interpreter does type checking only as code runs, and the type of a variable is allowed to change over its lifetime.

Q3. List some pros and cons of Python programming language?

Pros: Python is easy to learn , it is a high level language , large community support , it is free , Extensive libraries 
Cons: It is slower compared to compiled languages, Occupies more memory

Q4. In what all domains can we use Python?

Python can be used in many domains such as software developement , data domain , web developement , game developement etc. 


Q5. What are variable and how can we declare them?

Variable is the name given to the memory location , it stores the value assigned to them 

int_a = 10

Q6. How can we take an input from the user in Python?

we can take an input from the user in Python using input() function 

Q7. What is the default datatype of the value that has been taken as an input using input() function?

str is the default datatype of the value that has been taken as an input using input() function?

Q8. What is type casting?

It is a method to convert the data type of a variable into a certain data type 

Q9. Can we take more than one input from the user using single input() function? If yes, how? If no, why?

yes we can take more than one input from the user using single input() function with the help of split() method 


Q10. What are keywords?

Keywords are reserved words that has a specific meaning 

Q11. Can we use keywords as a variable? Support your answer with reason.

No,we cannot use keywords as a variable because they are resserved words 

Q12. What is indentation? What's the use of indentaion in Python?

Indentation refers to the spaces at the beginning of a code line. Python uses indentation to indicate a block of code.

Q13. How can we throw some output in Python?

using print() fonction

Q14. What are operators in Python?

The operator can be defined as a symbol which is responsible for a particular operation between two operands.
operators are use to perform some mathematical,logical,relational operation in python.

Q15. What is difference between / and // operators?

Normal division (/) returns a fractional number, whereas floor division (//) truncates the decimal part and returns the quotient.

Q16. Write a code that gives following as an output.
```
iNeuroniNeuroniNeuroniNeuron
```
var_name = 'iNeuron'
print(var_name * 4)

Q17. Write a code to take a number as an input from the user and check if the number is odd or even.

def odd_or_even():
    int_num = int(input("Enter a number : "))
    if int_num % 2 == 0:
        return ("The number is even ")
    else:
        return (" the number is odd ")

print (odd_or_even())

Q18. What are boolean operator?

boolean operator is used to check wheter a condition is true or false.

Q19. What will the output of the following?
```
1 or 0 = 0

0 and 0 = 0

True and False and True = False

1 or 0 or 0 = 0
```

Q20. What are conditional statements in Python?

conditional statements are used to check for a condition in the program / used to handle a condition in a program 

types of conditional statement in python are : if , elif , else 

Q21. What is use of 'if', 'elif' and 'else' keywords?

if keyword is used to check whether the given statement satisfies the given condition / checks whether the given condition is true
elif keyword is used to check multiple conditions
else keyword is used to execute the given statement if the condition is false

Q22. Write a code to take the age of person as an input and if age >= 18 display "I can vote". If age is < 18 display "I can't vote".

age = int(input("Enter your age :"))
if age >= 18:
    print("I can vote")
else:
    print("I can't vote")

Q23. Write a code that displays the sum of all the even numbers from the given list.
```
numbers = [12, 75, 150, 180, 145, 525, 50]
```

numbers = [12, 75, 150, 180, 145, 525, 50]
sum = 0
for num in numbers:
    if num % 2 == 0:
        sum = sum + num
print("The sum of all the even numbers from the given list is : ",sum)

Q24. Write a code to take 3 numbers as an input from the user and display the greatest no as output.

a,b,c = input("Enter 3 numbers :").split()
if a>b and a>c:
    print(f'{a} is greater')
elif b>c:
    print(f'{b} is greater')
else:
    print(f'{c} is greater')

Q25. Write a program to display only those numbers from a list that satisfy the following conditions

- The number must be divisible by five

- If the number is greater than 150, then skip it and move to the next number

- If the number is greater than 500, then stop the loop

numbers = [12, 75, 150, 180, 145, 525, 50]
new_numbers = []
for num in numbers:
    if num > 500:
        break
    elif num % 5 == 0 and not(num > 150):
        new_numbers.append(num)
    else:
        pass
print(new_numbers)