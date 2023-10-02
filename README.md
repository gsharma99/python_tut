# python_tut
Contains material for learning the python



# 01-Day1-Intro-to-Python
# Day 1 - What is Programming and Python?
## What is Programming
Programming is a way for us to tell computers what to do. Computer is a very dumb machine and it only does what we tell it to do. Hence we learn programming and tell computers to do what we are very slow at - computation. 
If I ask you to calculate 5+6, you will immediately say 11. 
How about 23453453 X 56456?

You will start searching for a calculator or jump to a new tab to calculate the same. 
This 100 days of code series will help you learn python from starting to the end. We will start from 0 and by the time we end this course, I promise you will be a Job ready Python developer!

## What is Python?

-   Python is a dynamically typed, general purpose programming language that supports an object-oriented programming approach as well as a functional programming approach.
-   Python is an interpreted and a high-level programming language.
-   It was created by Guido Van Rossum in 1989. 

## Features of Python

-   Python is simple and easy to understand.
-   It is Interpreted and platform-independent which makes debugging very easy.
-   Python is an open-source programming language.
-   Python provides very big library support. Some of the popular libraries include NumPy, Tensorflow, Selenium, OpenCV, etc.
-   It is possible to integrate other programming languages within python.

## What is Python used for

-   Python is used in Data Visualization to create plots and graphical representations.
-   Python helps in Data Analytics to analyze and understand raw data for insights and trends.
-   It is used in AI and Machine Learning to simulate human behavior and to learn from past data without hard coding.
-   It is used to create web applications.
-   It can be used to handle databases.
-   It is used in business and accounting to perform complex mathematical operations along with quantitative and qualitative analysis.

## Why Replit?
- Replit is very easy to share tutorials and code.
- You can easily fork this repl and continue learning in your own style. Video, code as well as text tutorial on the same page which makes things easy!
- For fellow teachers out there, you create a .tutorial folder to create tutorials using replit.

## [Next Lesson>>](https://replit.com/@codewithharry/02-Day2-Application-of-Python#.tutorial/Tutorial.md)

# 02-Day2-Application-of-Python
# Day 2 - My Python Success Story
# Why I love python (And you will too...)
Welcome to Day 2 of 100 days of code. Let me start with a story! 
Back in my college, I used to learn C and C++ programming in depth, used to score good marks. I created a bunch of printing, conditionals and loop program. Now what? I wanted to benefit from the same
In my second year of college, I started working (I mean actually working in the industry) with the python programming language. I was not so good with it but I used to write code for a singaporean client and actually make good money without having to actually master Python. Harry then got curious and started working on his Python skills even more.
I then got into web scraping and trust me I made some good easy money on Fiverr just by writing some python programs and charging on per webpage basis to my clients ( I used to automate scraping)

I then learnt flask and got to work with Flask with a university professor abroad. Long story short, Python made a huge impact in my career.

## What can Python do for you?

I want to show you some python programs I created which will surely inspire you to create your own versions of the same as we progress through this tutorial. 
Do not try to recreate them just yet if you are a beginner and just started working on Python. We will make progress gradually trust me

## [Next Lesson>>](https://replit.com/@codewithharry/03-Day3-Modules-and-Pip#main.py)

# 03-Day3-Modules-and-Pip
# Day 3 - Modules and pip in Python!

Module is like a code library which can be used to borrow code written by somebody else in our python program. There are two types of modules in python:
1. Built in Modules - These modules are ready to import and use and ships with the python interpreter. there is no need to install such modules explicitly.
2. External Modules - These modules are imported from a third party file or can be installed using a package manager like pip or conda. Since this code is written by someone else, we can install different versions of a same module with time.

## The pip command

It can be used as a package manager [pip](https://pip.pypa.io/en/stable/) to install a python module.
Lets install a module called pandas using the following command

```bash
pip install pandas
```

## Using a module in Python (Usage)
We use the import syntax to import a module in Python. Here is an example code:

```python
import pandas

# Read and work with a file named 'words.csv'
df = pandas.read_csv('words.csv')
print(df) # This will display first few rows from the words.csv file
 
```

Similarly we can install other modules and look into their documentations for usage instructions.\
We will find ourselved doing this often in the later part of this course

## [Next Lesson>>](https://replit.com/@codewithharry/04-Day4-Our-First-Program)

# 04-Day4-Our-First-Program
# Day 4 - Our First Program

Today we will write our first ever python program from scratch. It will consist of a bunch of print statements.
print can be used to print something on the console in python

## Quick Quiz

Write a program to print a poem in Python. Choose the poem of your choice and publish your repl


```python
print("---Your poem here---")

```

Please make sure you attempt this. Might be easy for some of you but please finish each and every task

## [Next Lesson>>](https://replit.com/@codewithharry/05-Day5-Comments-and-Print#main.py)

# 05-Day5-Comments-and-Print
# Day 5 - Comments, Escape sequence & Print in Python

Welcome to Day 5 of 100DaysOfCode. Today we will talk about Comments, Escape Sequences and little bit more about print statement in Python.
We will also throw some light on Escape Sequences

# Python Comments
A comment is a part of the coding file that the programmer does not want to execute, rather the programmer uses it to either explain a block of code or to avoid the execution of a specific part of code while testing.

## Single-Line Comments:

To write a comment just add a ‘#’ at the start of the line.

### Example 1

```python
#This is a 'Single-Line Comment'
print("This is a print statement.")
``` 

Output:

```markup
This is a print statement. 
``` 

### Example 2

```python
print("Hello World !!!") #Printing Hello World
```

Output:

```markup
Hello World !!!
``` 

### Example 3:

```python
print("Python Program")
#print("Python Program")
``` 

### Output: 

```markup
Python Program
``` 
## Multi-Line Comments:

To write multi-line comments you can use ‘#’ at each line or you can use the multiline string.

**Example 1:** The use of ‘#’.

```python
#It will execute a block of code if a specified condition is true.
#If the condition is false then it will execute another block of code.
p = 7
if (p > 5):
    print("p is greater than 5.")
else:
    print("p is not greater than 5.")
```


Output:

```markup
p is greater than 5.
```


**Example 2:** The use of multiline string.

```python
"""This is an if-else statement.
It will execute a block of code if a specified condition is true.
If the condition is false then it will execute another block of code."""
p = 7
if (p > 5):
    print("p is greater than 5.")
else:
    print("p is not greater than 5.")
```


### Output

```markup
p is greater than 5.
```

# Escape Sequence Characters

To insert characters that cannot be directly used in a string, we use an escape sequence character.

An escape sequence character is a backslash  `\`  followed by the character you want to insert.

An example of a character that cannot be directly used in a string is a double quote inside a string that is surrounded by double quotes:

```python
print("This doesnt "execute")
print("This will \" execute")
```

# More on Print statement
The syntax of a print statement looks something like this:

```python
print(object(s), sep=separator, end=end, file=file, flush=flush)
```

## Other Parameters of Print Statement 
1. object(s): Any object, and as many as you like. Will be converted to string before printed
2. sep='separator': Specify how to separate the objects, if there is more than one. Default is ' '
3. end='end': Specify what to print at the end. Default is '\n' (line feed)
4. file: An object with a write method. Default is sys.stdout

Parameters 2 to 4 are optional

## [Next Lesson>>](https://replit.com/@codewithharry/06-Day6-Variables-and-Data-Types)

# 06-Day6-Variables-and-Data-Types

# Day 6 - Variables and Data Types
## What is a variable?
Variable is like a container that holds data. Very similar to how our containers in kitchen holds sugar, salt etc
Creating a variable is like creating a placeholder in memory and assigning it some value. In Python its as easy as writing:
```python
a = 1
b = True
c = "Harry"
d = None
```

These are four variables of different data types.

## What is a Data Type?
Data type specifies the type of value a variable holds. This is required in programming to do various operations without causing an error. \
In python, we can print the type of any operator using type function:
```python
a = 1
print(type(a))
b = "1"
print(type(b))
```
By default, python provides the following built-in data types:

## 1. Numeric data: int, float, complex


 - int: 3, -8, 0
 -    float: 7.349, -9.0, 0.0000001
 -  complex: 6 + 2i 

 ## 2. Text data: str
    

str: "Hello World!!!", "Python Programming"

## 3. Boolean data:
    

Boolean data consists of values True or False.

## 4. Sequenced data: list, tuple
    

**list:**  A list is an ordered collection of data with elements separated by a comma and enclosed within square brackets. Lists are mutable and can be modified after creation.

**Example:**

```python
list1 = [8, 2.3, [-4, 5], ["apple", "banana"]]
print(list1)
```


Output:

```markup
[8, 2.3, [-4, 5], ['apple', 'banana']]
```


**Tuple:**  A tuple is an ordered collection of data with elements separated by a comma and enclosed within parentheses. Tuples are immutable and can not be modified after creation. 

**Example:**

```python
tuple1 = (("parrot", "sparrow"), ("Lion", "Tiger"))
print(tuple1)
```


Output:

```python
(('parrot', 'sparrow'), ('Lion', 'Tiger'))
```


## 5. Mapped data: dict
    

**dict:** A dictionary is an unordered collection of data containing a key:value pair. The key:value pairs are enclosed within curly brackets.

**Example:**

```python
dict1 = {"name":"Sakshi", "age":20, "canVote":True}
print(dict1)
```


Output:

```python
{'name': 'Sakshi', 'age': 20, 'canVote': True}
```

## [Next Lesson>>](https://replit.com/@codewithharry/07-Day7-Exercise-1-Create-a-Calculator)

# 08-Day8-Exercise-1-Create-a-Calculator-Solution
## Exercise 1 - Create a Calculator Solution
Create a calculator capable of performing addition, subtraction, multiplication and division operations on two numbers. Your program should format the output in a readable manner!

## [Next Lesson>>](https://replit.com/@codewithharry/09-Day9-Typecasting-in-Python)

# 09-Day9-Typecasting-in-Python
# Typecasting in python
The conversion of one data type into the other data type is known as type casting in python or type conversion in python.

Python supports a wide variety of functions or methods like: int(), float(), str(), ord(), hex(), oct(), tuple(), set(), list(), dict(), etc. for the type casting in python.


## Two Types of Typecasting:

1. Explicit Conversion (Explicit type casting in python)
2. Implicit Conversion (Implicit type casting in python).
### Explicit typecasting:
The conversion of one data type into another data type, done via developer or programmer's intervention or manually as per the requirement, is known as explicit type conversion. 

It can be achieved with the help of Python’s built-in type conversion functions such as int(), float(), hex(), oct(), str(), etc .
### Example of explicit typecasting:
```python
string = "15"
number = 7
string_number = int(string) #throws an error if the string is not a valid integer
sum= number + string_number
print("The Sum of both the numbers is: ", sum)
```
### Output:
```
The Sum of both the numbers is 22
```
### Implicit type casting:
Data types in Python do not have the same level i.e. ordering of data types is not the same in Python. Some of the data types have higher-order, and some have lower order. While performing any operations on variables with different data types in Python, one of the variable's data types will be changed to the higher data type. According to the level, one data type is converted into other by the Python interpreter itself (automatically). This is called, implicit typecasting in python.

Python converts a smaller data type to a higher data type to prevent data loss.
### Example of implicit type casting:
```python
# Python automatically converts
# a to int
a = 7
print(type(a))
 
# Python automatically converts b to float
b = 3.0
print(type(b))
 
# Python automatically converts c to float as it is a float addition
c = a + b
print(c)
print(type(c))
```
### Ouput:
```
<class 'int'>
<class 'float'>
10.0
<class 'float'>
```

## [Next Lesson>>](https://replit.com/@codewithharry/10-Day10-Taking-User-Input#main.py`)

# 10-Day10-Taking-User-Input
# Day 10 - Taking User Input in python
In python, we can take user input directly by using input() function.This input function gives a return value as string/character hence we have to pass that into a variable
## Syntax:
```python
variable=input()
```
But input function returns the value as string. Hence we have to typecast them whenever required to another datatype.
## Example:
```python
variable=int(input())
variable=float(input())
```

We can also display a text using input function. This will make input() function take user input and display a message as well
## Example:
```python
a=input("Enter the name: ")
print(a)
```
## Output:
```
Enter the name: Harry
Harry
```
## [Next Lesson>>](https://replit.com/@codewithharry/11-Day11-Strings#main.py)

# 12-Day12-Strings-Slicing
# String Slicing & Operations on String
# Length of a String
We can find the length of a string using len() function.

## Example:
```python
fruit = "Mango"
len1 = len(fruit)
print("Mango is a", len1, "letter word.")
```
## Output:
Mango is a 5 letter word.
# String as an array
A string is essentially a sequence of characters also called an array. Thus we can access the elements of this array. 

## Example:
```python
pie = "ApplePie"
print(pie[:5])
print(pie[6])	#returns character at specified index
```
## Output:
```
Apple
i
```
 

Note: This method of specifying the start and end index to specify a part of a string is called slicing. 
## Slicing Example:
```python
pie = "ApplePie"
print(pie[:5])      #Slicing from Start
print(pie[5:])      #Slicing till End
print(pie[2:6])     #Slicing in between
print(pie[-8:])     #Slicing using negative index
```
## Output:
```
Apple
Pie
pleP
ApplePie
```
# Loop through a String:
Strings are arrays and arrays are iterable. Thus we can loop through strings.
## Example:
```python
alphabets = "ABCDE"
for i in alphabets:
    print(i)
  ```
## Output:
```
A
B
C
D
E
```

## [Next Lesson>>](https://replit.com/@codewithharry/13-Day13-String-Methods)

# 13-Day13-String-Methods
# String methods
Python provides a set of built-in methods that we can use to alter and modify the strings.


## upper() :
The upper() method converts a string to upper case.

### Example:
```python
str1 = "AbcDEfghIJ"
print(str1.upper())
```
### Output:
```
ABCDEFGHIJ
 ```

## lower()
The lower() method converts a string to lower case.
### Example:
```python
str1 = "AbcDEfghIJ"
print(str1.lower())
```
### Output:
```
abcdefghij
 ```

## strip() :
The strip() method removes any white spaces before and after the string.
### Example:
```python
str2 = " Silver Spoon "
print(str2.strip)
```
### Output:
```
Silver Spoon
``` 

## rstrip() : 
the rstrip() removes any trailing characters.
Example:
```python
str3 = "Hello !!!"
print(str3.rstrip("!"))
```
### Output:
```
Hello
 ```

## replace() : 
The replace() method replaces all occurences of a string with another string.
Example:
```python
str2 = "Silver Spoon"
print(str2.replace("Sp", "M"))
```
### Output:
```
Silver Moon
 ```

## split() :
The split() method splits the given string at the specified instance and returns the separated strings as list items.
### Example:
```python
str2 = "Silver Spoon"
print(str2.split(" "))      #Splits the string at the whitespace " ".
```
### Output:
```
['Silver', 'Spoon']
There are various other string methods that we can use to modify our strings.
```
 

## capitalize() : 
The capitalize() method turns only the first character of the string to uppercase and the rest other characters of the string are turned to lowercase. The string has no effect if the first character is already uppercase.
### Example:
```python
str1 = "hello"
capStr1 = str1.capitalize()
print(capStr1)
str2 = "hello WorlD"
capStr2 = str2.capitalize()
print(capStr2)
```
### Output:
```
Hello
Hello world
```

## center() : 
The center() method aligns the string to the center as per the parameters given by the user.
### Example:
```python
str1 = "Welcome to the Console!!!"
print(str1.center(50))
```
### Output:
```
            Welcome to the Console!!!
 ```

We can also provide padding character. It will fill the rest of the fill characters provided by the user.

### Example:
```python
str1 = "Welcome to the Console!!!"
print(str1.center(50, "."))
```
### Output:
```
............Welcome to the Console!!!.............
 ```

## count() :
The count() method returns the number of times the given value has occurred within the given string.
### Example:
```python
str2 = "Abracadabra"
countStr = str2.count("a")
print(countStr)
```
### Output:
```
4
```
 

## endswith() : 
The endswith() method checks if the string ends with a given value. If yes then return True, else return False. 
### Example :
```python
str1 = "Welcome to the Console !!!"
print(str1.endswith("!!!"))
```
### Output:
```
True
```
We can even also check for a value in-between the string by providing start and end index positions.

### Example:
```python
str1 = "Welcome to the Console !!!"
print(str1.endswith("to", 4, 10))
```
### Output:
```
True
 ```

## find() : 
The find() method searches for the first occurrence of the given value and returns the index where it is present. If given value is absent from the string then return -1.
### Example:
```python
str1 = "He's name is Dan. He is an honest man."
print(str1.find("is"))
```
### Output:
```
10
 ```

As we can see, this method is somewhat similar to the index() method. The major difference being that index() raises an exception if value is absent whereas find() does not.

### Example:
```python
str1 = "He's name is Dan. He is an honest man."
print(str1.find("Daniel"))
```
### Output:
```
-1
 ```

## index() :
The index() method searches for the first occurrence of the given value and returns the index where it is present. If given value is absent from the string then raise an exception.
### Example:
```python
str1 = "He's name is Dan. Dan is an honest man."
print(str1.index("Dan"))
```
### Output:
```
13
 ```

As we can see, this method is somewhat similar to the find() method. The major difference being that index() raises an exception if value is absent whereas find() does not.

### Example:
```python
str1 = "He's name is Dan. Dan is an honest man."
print(str1.index("Daniel"))
```
### Output:
```
ValueError: substring not found
 ```

## isalnum() :
The isalnum() method returns True only if the entire string only consists of A-Z, a-z, 0-9. If any other characters or punctuations are present, then it returns False.
### Example 1:
```python
str1 = "WelcomeToTheConsole"
print(str1.isalnum())
```
Output:
```
True
 ```
## isalpha() :
The isalnum() method returns True only if the entire string only consists of A-Z, a-z. If any other characters or punctuations or numbers(0-9) are present, then it returns False.
### Example :
```python
str1 = "Welcome"
print(str1.isalpha())
```
### Output:
```
True
 ```

## islower() :
The islower() method returns True if all the characters in the string are lower case, else it returns False. 
### Example:
```python
str1 = "hello world"
print(str1.islower())
```
### Output:
```
True
 ```

## isprintable() :
The isprintable() method returns True if all the values within the given string are printable, if not, then return False.
### Example :
```python
str1 = "We wish you a Merry Christmas"
print(str1.isprintable())
```
### Output:
```
True
 ```
## isspace() :
The isspace() method returns True only and only if the string contains white spaces, else returns False.
### Example:
```python
str1 = "        "       #using Spacebar
print(str1.isspace())
str2 = "        "       #using Tab
print(str2.isspace())
```
### Output:
```
True
True
 ```

## istitle() : 
The istitile() returns True only if the first letter of each word of the string is capitalized, else it returns False.
### Example:
```python
str1 = "World Health Organization" 
print(str1.istitle())
```
### Output:
```
True
 ```

### Example:
```python
str2 = "To kill a Mocking bird"
print(str2.istitle())
```
### Output:
```
False
 ```

## isupper() :
The isupper() method returns True if all the characters in the string are upper case, else it returns False. 
### Example :
```python
str1 = "WORLD HEALTH ORGANIZATION" 
print(str1.isupper())
```
### Output:
```
True
 ```
  

## startswith() :
The endswith() method checks if the string starts with a given value. If yes then return True, else return False. 
### Example :
```python
str1 = "Python is a Interpreted Language" 
print(str1.startswith("Python"))
```
### Output:
```
True
 ```

## swapcase() : 
The swapcase() method changes the character casing of the string. Upper case are converted to lower case and lower case to upper case.
### Example:
```python
str1 = "Python is a Interpreted Language" 
print(str1.swapcase())
```
### Output:
```
pYTHON IS A iNTERPRETED lANGUAGE
 ```

### title() :
The title() method capitalizes each letter of the word within the string.
### Example:
```python
str1 = "He's name is Dan. Dan is an honest man."
print(str1.title())
```
### Output:
```
He'S Name Is Dan. Dan Is An Honest Man.
```

## [Next Lesson>>](https://replit.com/@codewithharry/14-Day14-If-Else-Conditionals#04%20nested.py)

# 15-Day15-Exercise-2-Good-Morning-Sir
# Excersice 2: Good Morning Sir
Create a python program capable of greeting you with Good Morning, Good Afternoon and Good Evening. Your program should use time module to get the current hour. Here is a sample program and documentation link for you:
```python
import time
timestamp = time.strftime('%H:%M:%S')
print(timestamp)
timestamp = time.strftime('%H')
print(timestamp)
timestamp = time.strftime('%M')
print(timestamp)
timestamp = time.strftime('%S')
print(timestamp)
# https://docs.python.org/3/library/time.html#time.strftime
```
## [Next Lesson>>](https://replit.com/@codewithharry/16-Day-16-Match-Case)

# 16-Day-16-Match-Case
# Match Case Statements
To implement switch-case like characteristics very similar to if-else functionality, we use a match case in python. If you are coming from a C, C++ or Java like language, you must have heard of switch-case statements. If this is your first language, dont worry as I will tell you everything you need to know about match case statements in this video!

A match statement will compare a given variable’s value to different shapes, also referred to as the pattern. The main idea is to keep on comparing the variable with all the present patterns until it fits into one.

The match case consists of three main entities :

1. The match keyword
2. One or more case clauses
3. Expression for each case

The case clause consists of a pattern to be matched to the variable, a condition to be evaluated if the pattern matches, and a set of statements to be executed if the pattern matches.
## Syntax:
```python
match variable_name:
            case ‘pattern1’ : //statement1
            case ‘pattern2’ : //statement2
            …            
            case ‘pattern n’ : //statement n
```
### Example:
```python
x = 4
# x is the variable to match
match x:
    # if x is 0
    case 0:
        print("x is zero")
    # case with if-condition
    case 4 if x % 2 == 0:
        print("x % 2 == 0 and case is 4")
    # Empty case with if-condition
    case _ if x < 10:
        print("x is < 10")
    # default case(will only be matched if the above cases were not matched)
    # so it is basically just an else:
    case _:
        print(x)
```
### Output:
```
x % 2 == 0 and case is 4
```
## [Next Lesson>>](https://replit.com/@codewithharry/17-Day17-For-Loops)

# 17-Day17-For-Loops
# Introduction to Loops
Sometimes a programmer wants to execute a group of statements a certain number of times. This can be done using loops. Based on this loops are further classified into following main types; 
- for loop
- while loop 
# The for Loop
for loops can iterate over a sequence of iterable objects in python. Iterating over a sequence is nothing but iterating over strings, lists, tuples, sets and dictionaries.

## Example: iterating over a string:

```python 
name = 'Abhishek'
for i in name:
    print(i, end=", ")
```
## Output:

A, b, h, i, s, h, e, k,
 

## Example: iterating over a list:

``` python 
colors = ["Red", "Green", "Blue", "Yellow"]
for x in colors:
    print(x)
```
## Output:

Red\
Green\
Blue\
Yellow

Similarly, we can use loops for lists, sets and dictionaries.
## range():
What if we do not want to iterate over a sequence? What if we want to use for loop for a specific number of times?

Here, we can use the range() function.

## Example:
```python
for k in range(5):
    print(k)
```
## Output:

0\
1\
2\
3\
4\
Here, we can see that the loop starts from 0 by default and increments at each iteration.

 

But we can also loop over a specific range.

## Example:
```python
for k in range(4,9):
    print(k)
```
## Output:

4\
5\
6\
7\
8

## Quick Quiz
Explore about third parameter of range (ie range(x, y, z))
## [Next Lesson>>](https://replit.com/@codewithharry/18-Day18-While-Loops)

# 21-Day-21-Function-Arguments
# Function Arguments and return statement
There are four types of arguments that we can provide in a function:

- Default Arguments
- Keyword Arguments
- Variable length Arguments
- Required Arguments
### Default arguments:
We can provide a default value while creating a function. This way the function assumes a default value even if a value is not provided in the function call for that argument.

Example:
```python
def name(fname, mname = "Jhon", lname = "Whatson"):
    print("Hello,", fname, mname, lname)

name("Amy")
```
Output:
```
Hello, Amy Jhon Whatson
 ```

### Keyword arguments:
We can provide arguments with key = value, this way the interpreter recognizes the arguments by the parameter name. Hence, the the order in which the arguments are passed does not matter.

Example:
```python
def name(fname, mname, lname):
    print("Hello,", fname, mname, lname)

name(mname = "Peter", lname = "Wesker", fname = "Jade")
```
Output:
```
Hello, Jade Peter Wesker
 ```

### Required arguments:
In case we don’t pass the arguments with a key = value syntax, then it is necessary to pass the arguments in the correct positional order and the number of arguments passed should match with actual function definition.

Example 1: when number of arguments passed does not match to the actual function definition.
```python
def name(fname, mname, lname):
    print("Hello,", fname, mname, lname)

name("Peter", "Quill")
```
Output:
```
name("Peter", "Quill")\
TypeError: name() missing 1 required positional argument: 'lname'
 ```

Example 2: when number of arguments passed matches to the actual function definition.
```python
def name(fname, mname, lname):
    print("Hello,", fname, mname, lname)

name("Peter", "Ego", "Quill")
```
Output:
```
Hello, Peter Ego Quill
 ```

### Variable-length arguments:
Sometimes we may need to pass more arguments than those defined in the actual function. This can be done using variable-length arguments.

There are two ways to achieve this:

#### Arbitrary Arguments:
While creating a function, pass a * before the parameter name while defining the function. The function accesses the arguments by processing them in the form of tuple.

Example:
```python
def name(*name):
    print("Hello,", name[0], name[1], name[2])

name("James", "Buchanan", "Barnes")
```
Output:
```
Hello, James Buchanan Barnes
 ```

#### Keyword Arbitrary Arguments:
While creating a function, pass a * before the parameter name while defining the function. The function accesses the arguments by processing them in the form of dictionary.

Example:
```python
def name(**name):
    print("Hello,", name["fname"], name["mname"], name["lname"])

name(mname = "Buchanan", lname = "Barnes", fname = "James")
```
Output:
```
Hello, James Buchanan Barnes
```

## return Statement
The return statement is used to return the value of the expression back to the calling function.

 

Example:
```python
def name(fname, mname, lname):
    return "Hello, " + fname + " " + mname + " " + lname

print(name("James", "Buchanan", "Barnes"))
 ```

Output:
```
Hello, James Buchanan Barnes
```
## [Next Lesson>>](https://replit.com/@codewithharry/22-Day-22-Introduction-to-Lists)



# 26-Day-26-Exercise-2-Solution
# Excersice 2: Good Morning Sir
Create a python program capable of greeting you with Good Morning, Good Afternoon and Good Evening. Your program should use time module to get the current hour. Here is a sample program and documentation link for you:
```python
import time
timestamp = time.strftime('%H:%M:%S')
print(timestamp)
timestamp = time.strftime('%H')
print(timestamp)
timestamp = time.strftime('%M')
print(timestamp)
timestamp = time.strftime('%S')
print(timestamp)
# https://docs.python.org/3/library/time.html#time.strftime
```
## [Next Lesson>>](https://replit.com/@codewithharry/27-Day27-Exercise-3)

# 27-Day27-Exercise-3
Create a program capable of displaying questions to the user like KBC. 
Use List data type to store the questions and their correct answers.
Display the final amount the person is taking home after playing the game.
## [Next Lesson>>](https://replit.com/@codewithharry/28-Day28-f-strings)

# 28-Day28-f-strings
# String formatting in python
String formatting can be done in python using the format method.
```python
txt = "For only {price:.2f} dollars!"
print(txt.format(price = 49))
```
# f-strings in python
It is a new string formatting mechanism introduced by the PEP 498. It is also known as Literal String Interpolation or more commonly as F-strings (f character preceding the string literal). The primary focus of this mechanism is to make the interpolation easier.

When we prefix the string with the letter 'f', the string becomes the f-string itself. The f-string can be formatted in much same as the str.format() method. The f-string offers a convenient way to embed Python expression inside string literals for formatting.

## Example
```python
val = 'Geeks'  
print(f"{val}for{val} is a portal for {val}.")  
name = 'Tushar'  
age = 23  
print(f"Hello, My name is {name} and I'm {age} years old.")  
```
## Output:
```
Hello, My name is Tushar and I'm 23 years old.
```
In the above code, we have used the f-string to format the string. It evaluates at runtime; we can put all valid Python expressions in them.

We can use it in a single statement as well.
## Example
```python
print(f"{2 * 30})"  
```
## Output:
```
60
```
## [Next Lesson>>](https://replit.com/@codewithharry/29-Day29-Docstrings)

# 30-Day30-Recursion
# Recursion in python
Recursion is the process of defining something in terms of itself.

## Python Recursive Function
In Python, we know that a function can call other functions. It is even possible for the function to call itself. These types of construct are termed as recursive functions.
## Example:
```python
def factorial(num): 
    if (num == 1 or num == 0):
        return 1
    else:
        return (num * factorial(num - 1)) 
  
# Driver Code 
num = 7; 
print("Number: ",num)
print("Factorial: ",factorial(num))
 ```

## Output:
```
number:  7
Factorial:  5040
```
## [Next Lesson>>](https://replit.com/@codewithharry/31-Day31-Sets)

# 31-Day31-Sets
# Python Sets
Sets are unordered collection of data items. They store multiple items in a single variable. Set items are separated by commas and enclosed within curly brackets {}. Sets are unchangeable, meaning you cannot change items of the set once created. Sets do not contain duplicate items.



#### Example:
```python
info = {"Carla", 19, False, 5.9, 19}
print(info)
```
#### Output:
```
{False, 19, 5.9, 'Carla'}
 ```

Here we see that the items of set occur in random order and hence they cannot be accessed using index numbers. Also sets do not allow duplicate values.

 **Quick Quiz:** Try to create an empty set. Check using the type() function whether the type of your variable is a set

## Accessing set items:
 

### Using a For loop
You can access items of set using a for loop. 

#### Example:
```python
info = {"Carla", 19, False, 5.9}
for item in info:
    print(item)
  ```
#### Output:
```
False
Carla
19
5.9
```
## [Next Lesson>>](https://replit.com/@codewithharry/32-Day32-Set-Methods)

# 35-Day-35-For-loop-with-else
# Python - else in Loop
As you have learned before, the else clause is used along with the if statement.

Python allows the else keyword to be used with the for and while loops too. The else block appears after the body of the loop. The statements in the else block will be executed after all iterations are completed. The program exits the loop only after the else block is executed.
## Syntax
```
for counter in sequence:
    #Statements inside for loop block
else:
    #Statements inside else block
```
## Example:
```
for x in range(5):
    print ("iteration no {} in for loop".format(x+1))
else:
    print ("else block in loop")
print ("Out of loop")
```
## Output:
```
iteration no 1 in for loop
iteration no 2 in for loop
iteration no 3 in for loop
iteration no 4 in for loop
iteration no 5 in for loop
else block in loop
Out of loop
```
## [Next Lesson>>](https://replit.com/@codewithharry/36-Day36-Exception-Handling)


# 36-Day36-Exception-Handling
# Exception Handling
Exception handling is the process of responding to unwanted or unexpected events when a computer program runs. Exception handling deals with these events to avoid the program or system crashing, and without this process, exceptions would disrupt the normal operation of a program.
# Exceptions in Python
Python has many built-in exceptions that are raised when your program encounters an error (something in the program goes wrong).

When these exceptions occur, the Python interpreter stops the current process and passes it to the calling process until it is handled. If not handled, the program will crash.

# Python try...except
try….. except blocks are used in python to handle errors and exceptions. The code in try block runs when there is no error. If the try block catches the error, then the except block is executed. 

 ## Syntax:
 ```python
 try:
      #statements which could generate 
      #exception
except:
      #Soloution of generated exception
```
## Example:
```python
try:
    num = int(input("Enter an integer: "))
except ValueError:
    print("Number entered is not an integer.")
 ```

## Output:
```
Enter an integer: 6.022
Number entered is not an integer.
```

## [Next Lesson>>](https://replit.com/@codewithharry/37-Day37-Finally-keyword)

# 37-Day37-Finally-keyword
# Finally Clause
The finally code block is also a part of exception handling. When we handle exception using the try and except block, we can include a finally block at the end. The finally block is always executed, so it is generally used for doing the concluding tasks like closing file resources or closing database connection or may be ending the program execution with a delightful message.
# Syntax:
```
try:
   #statements which could generate 
   #exception
except:
   #solution of generated exception
finally:
    #block of code which is going to 
    #execute in any situation
    
   
```
The finally block is executed irrespective of the outcome of try……except…..else blocks\
One of the important use cases of finally block is in a function which returns a value.
# Example:
```python
try:
    num = int(input("Enter an integer: "))
except ValueError:
    print("Number entered is not an integer.")
else:
    print("Integer Accepted.")
finally:
    print("This block is always executed.")
 ```

## Output 1:
```
Enter an integer: 19
Integer Accepted.
This block is always executed.
```
## Output 2:
```
Enter an integer: 3.142
Number entered is not an integer.
This block is always executed.
```
## [Next Lesson>>](https://replit.com/@codewithharry/38-Day38-Custom-Errors)

# 38-Day38-Custom-Errors
## Raising Custom errors 
In python, we can raise custom errors by using the `raise`  keyword. 
```python
salary = int(input("Enter salary amount: "))
if not 2000 < salary < 5000:
    raise ValueError("Not a valid salary")
```

In the previous tutorial, we learned about different built-in exceptions in Python and why it is important to handle exceptions. However, sometimes we may need to create our own custom exceptions that serve our purpose.

## Defining Custom Exceptions
In Python, we can define custom exceptions by creating a new class that is derived from the built-in Exception class.

Here's the syntax to define custom exceptions:
```python
class CustomError(Exception):
  # code ...
  pass

try:
  # code ...

except CustomError:
  # code...
```

This is useful because sometimes we might want to do something when a particular exception is raised. For example, sending an error report to the admin, calling an api, etc.
## [Next Lesson>>](https://replit.com/@codewithharry/39-Day39-Exercise-3-Solution)

# 39-Day39-Exercise-3-Solution
Create a program capable of displaying questions to the user like KBC. 
Use List data type to store the questions and their correct answers.
Display the final amount the person is taking home after playing the game.

## [Next Lesson>>](https://replit.com/@codewithharry/40-Day40-Exercise-4)

# 39-Day39-Exercise-3-Solution (1)
Create a program capable of displaying questions to the user like KBC. 
Use List data type to store the questions and their correct answers.
Display the final amount the person is taking home after playing the game.

## [Next Lesson>>](https://replit.com/@codewithharry/40-Day40-Exercise-4)

# 41-Day41-Short-Hand-if-else
## If ... Else in One Line
There is also a shorthand syntax for the if-else statement that can be used when the condition being tested is simple and the code blocks to be executed are short. Here's an example:
```python
a = 2
b = 330
print("A") if a > b else print("B")
```

You can also have multiple else statements on the same line:

## Example
One line if else statement, with 3 conditions:
```python
a = 330
b = 330
print("A") if a > b else print("=") if a == b else print("B")
```

## Another Example
```python
result = value_if_true if condition else value_if_false

```

This syntax is equivalent to the following if-else statement:
```python
if condition:
    result = value_if_true
else:
    result = value_if_false

```
## Conclusion
The shorthand syntax can be a convenient way to write simple if-else statements, especially when you want to assign a value to a variable based on a condition. \
However, it's not suitable for more complex situations where you need to execute multiple statements or perform more complex logic. In those cases, it's best to use the full if-else syntax.
## [Next Lesson>>](https://replit.com/@codewithharry/42-Day-42-Enumerate)

# 42-Day-42-Enumerate
# Enumerate function in python
The enumerate function is a built-in function in Python that allows you to loop over a sequence (such as a list, tuple, or string) and get the index and value of each element in the sequence at the same time. Here's a basic example of how it works:
```python
# Loop over a list and print the index and value of each element
fruits = ['apple', 'banana', 'mango']
for index, fruit in enumerate(fruits):
    print(index, fruit)

```

The output of this code will be:

```python
0 apple
1 banana
2 mango

```
As you can see, the enumerate function returns a tuple containing the index and value of each element in the sequence. You can use the for loop to unpack these tuples and assign them to variables, as shown in the example above.
# Changing the start index
By default, the enumerate function starts the index at 0, but you can specify a different starting index by passing it as an argument to the enumerate function:


```python
# Loop over a list and print the index (starting at 1) and value of each element
fruits = ['apple', 'banana', 'mango']
for index, fruit in enumerate(fruits, start=1):
    print(index, fruit)

```

This will output:
```python
1 apple
2 banana
3 mango

```

The enumerate function is often used when you need to loop over a sequence and perform some action with both the index and value of each element. For example, you might use it to loop over a list of strings and print the index and value of each string in a formatted way:

```python
fruits = ['apple', 'banana', 'mango']
for index, fruit in enumerate(fruits):
    print(f'{index+1}: {fruit}')

```
This will output:
```python
1: apple
2: banana
3: mango

```

In addition to lists, you can use the enumerate function with any other sequence type in Python, such as tuples and strings. Here's an example with a tuple:

```python
# Loop over a tuple and print the index and value of each element
colors = ('red', 'green', 'blue')
for index, color in enumerate(colors):
    print(index, color)

```
And here's an example with a string:
```python
# Loop over a string and print the index and value of each character
s = 'hello'
for index, c in enumerate(s):
    print(index, c)

```
## [Next Lesson>>](https://replit.com/@codewithharry/43-Day43-Virtual-Environment)


# 44-Day44-How-import-works
## How importing in python works
Importing in Python is the process of loading code from a Python module into the current script. This allows you to use the functions and variables defined in the module in your current script, as well as any additional modules that the imported module may depend on.

To import a module in Python, you use the import statement followed by the name of the module. For example, to import the math module, which contains a variety of mathematical functions, you would use the following statement:

```python
import math
```
Once a module is imported, you can use any of the functions and variables defined in the module by using the dot notation. For example, to use the sqrt function from the math module, you would write:

```python
import math

result = math.sqrt(9)
print(result)  # Output: 3.0
```

## from keyword
You can also import specific functions or variables from a module using the from keyword. For example, to import only the sqrt function from the math module, you would write:

```python
from math import sqrt

result = sqrt(9)
print(result)  # Output: 3.0
```
You can also import multiple functions or variables at once by separating them with a comma:

```python
from math import sqrt, pi

result = sqrt(9)
print(result)  # Output: 3.0

print(pi)  # Output: 3.141592653589793
```

## importing everything
It's also possible to import all functions and variables from a module using the * wildcard. However, this is generally not recommended as it can lead to confusion and make it harder to understand where specific functions and variables are coming from.

```python
from math import *

result = sqrt(9)
print(result)  # Output: 3.0

print(pi)  # Output: 3.141592653589793
```
Python also allows you to rename imported modules using the as keyword. This can be useful if you want to use a shorter or more descriptive name for a module, or if you want to avoid naming conflicts with other modules or variables in your code.

## The "as" keyword
```python
import math as m

result = m.sqrt(9)
print(result)  # Output: 3.0

print(m.pi)  # Output: 3.141592653589793
```
## The dir function
Finally, Python has a built-in function called dir that you can use to view the names of all the functions and variables defined in a module. This can be helpful for exploring and understanding the contents of a new module.

```python
import math

print(dir(math))
```
This will output a list of all the names defined in the math module, including functions like sqrt and pi, as well as other variables and constants.

In summary, the import statement in Python allows you to access the functions and variables defined in a module from within your current script. You can import the entire module, specific functions or variables, or use the * wildcard to import everything. You can also use the as keyword to rename a module, and the dir function to view the contents of a module.
## [Next Lesson>>](https://replit.com/@codewithharry/45-Day45-if-name-main-in-Python)

# 45-Day45-if-name-main-in-Python
## `if "__name__ == "__main__"` in Python
The if `__name__ == "__main__"` idiom is a common pattern used in Python scripts to determine whether the script is being run directly or being imported as a module into another script.

In Python, the `__name__` variable is a built-in variable that is automatically set to the name of the current module. When a Python script is run directly, the `__name__` variable is set to the string `__main__` When the script is imported as a module into another script, the `__name__` variable is set to the name of the module.

Here's an example of how the if `__name__` == `__main__` idiom can be used:

```python
def main():
    # Code to be run when the script is run directly
    print("Running script directly")

if __name__ == "__main__":
    main()
```
In this example, the main function contains the code that should be run when the script is run directly. The if statement at the bottom checks whether the `__name__` variable is equal to `__main__`. If it is, the main function is called.
## Why is it useful?
This idiom is useful because it allows you to reuse code from a script by importing it as a module into another script, without running the code in the original script. For example, consider the following script:

```python
def main():
    print("Running script directly")

if __name__ == "__main__":
    main()
```
If you run this script directly, it will output "Running script directly". However, if you import it as a module into another script and call the main function from the imported module, it will not output anything:

```python
import script

script.main()  # Output: "Running script directly"
```
This can be useful if you have code that you want to reuse in multiple scripts, but you only want it to run when the script is run directly and not when it's imported as a module.

## Is it a necessity?
It's important to note that the `if __name__ == "__main__"` idiom is not required to run a Python script. You can still run a script without it by simply calling the functions or running the code you want to execute directly. However, the `if __name__ == "__main__"` idiom can be a useful tool for organizing and separating code that should be run directly from code that should be imported and used as a module.

In summary, the `if __name__ == "__main__"` idiom is a common pattern used in Python scripts to determine whether the script is being run directly or being imported as a module into another script. It allows you to reuse code from a script by importing it as a module into another script, without running the code in the original script.
## [Next Lesson>>](https://replit.com/@codewithharry/46-Day-46-os-Module)

# 46-Day-46-os-Module
# os Module in Python
The os module in Python is a built-in library that provides functions for interacting with the operating system. It allows you to perform a wide variety of tasks, such as reading and writing files, interacting with the file system, and running system commands.

Here are some common tasks you can perform with the os module:

Reading and writing files
The os module provides functions for opening, reading, and writing files. For example, to open a file for reading, you can use the open function:

```python
import os

# Open the file in read-only mode
f = os.open("myfile.txt", os.O_RDONLY)

# Read the contents of the file
contents = os.read(f, 1024)

# Close the file
os.close(f)
```
To open a file for writing, you can use the os.O_WRONLY flag:

```python
import os

# Open the file in write-only mode
f = os.open("myfile.txt", os.O_WRONLY)

# Write to the file
os.write(f, b"Hello, world!")

# Close the file
os.close(f)
```
## Interacting with the file system
The os module also provides functions for interacting with the file system. For example, you can use the os.listdir function to get a list of the files in a directory:

```python
import os

# Get a list of the files in the current directory
files = os.listdir(".")
print(files)  # Output: ['myfile.txt', 'otherfile.txt']
```
You can also use the os.mkdir function to create a new directory:

```python
import os

# Create a new directory
os.mkdir("newdir")
```
## Running system commands
Finally, the os module provides functions for running system commands. For example, you can use the os.system function to run a command and get the output:

```python
import os

# Run the "ls" command and print the output
output = os.system("ls")
print(output)  # Output: ['myfile.txt', 'otherfile.txt']
```
You can also use the os.popen function to run a command and get the output as a file-like object:

```python
import os

# Run the "ls" command and get the output as a file-like object
f = os.popen("ls")

# Read the contents of the output
output = f.read()
print(output)  # Output: ['myfile.txt', 'otherfile.txt']

# Close the file-like object
f.close()
```
In summary, the os module in Python is a built-in library that provides a wide variety of functions for interacting with the operating system. It allows you to perform tasks such as reading and writing files, interacting with the file system, and running system commands.
## [Next Lesson>>](https://replit.com/@codewithharry/47-Day47-Exercise-4-Solution)

# 47-Day47-Exercise-4-Solution
# Write a python program to translate a message into secret code language. Use the rules below to translate normal English into secret code language

# Coding:
if the word contains atleast 3 characters, remove the first letter and append it at the end
now append three random characters at the starting and the end
else:
simply reverse the string

# Decoding:
if the word contains less than 3 characters, reverse it
else:
remove 3 random characters from start and end. Now remove the last letter and append it to the beginning

## Your program should ask whether you want to code or decode
```
st = input("Enter message")
words = st.split(" ")
coding = input("1 for Coding or 0 for Decoding")
coding = True if (coding=="1") else False
print(coding)
if(coding):
  nwords = []
  for word in words:
    if(len(word)>=3):
      r1 = "dsf"
      r2 = "jkr"
      stnew = r1+ word[1:] + word[0] + r2
      nwords.append(stnew)
    else:
      nwords.append(word[::-1])
  print(" ".join(nwords))

else:
  nwords = []
  for word in words:
    if(len(word)>=3): 
      stnew = word[3:-3]
      stnew = stnew[-1] + stnew[:-1]
      nwords.append(stnew)
    else:
      nwords.append(word[::-1])
  print(" ".join(nwords))
```
  
## [Next Lesson>>](https://replit.com/@codewithharry/48-Day48-local-vs-global-variables)

# 48-Day48-local-vs-global-variables
# local and global variables
Before we dive into the differences between local and global variables, let's first recall what a variable is in Python.

A variable is a named location in memory that stores a value. In Python, we can assign values to variables using the assignment operator =. For example:
```python 
x = 5
y = "Hello, World!"

```

Now, let's talk about local and global variables.

A local variable is a variable that is defined within a function and is only accessible within that function. It is created when the function is called and is destroyed when the function returns.

On the other hand, a global variable is a variable that is defined outside of a function and is accessible from within any function in your code.

Here's an example to help clarify the difference:
```python
x = 10 # global variable

def my_function():
  y = 5 # local variable
  print(y)

my_function()
print(x)
print(y) # this will cause an error because y is a local variable and is not accessible outside of the function

```
In this example, we have a global variable x and a local variable y. We can access the value of the global variable x from within the function, but we cannot access the value of the local variable y outside of the function.
# The global keyword
Now, what if we want to modify a global variable from within a function? This is where the global keyword comes in.

The global keyword is used to declare that a variable is a global variable and should be accessed from the global scope. Here's an example:
```python 
x = 10 # global variable

def my_function():
  global x
  x = 5 # this will change the value of the global variable x
  y = 5 # local variable

my_function()
print(x) # prints 5
print(y) # this will cause an error because y is a local variable and is not accessible outside of the function

```

In this example, we used the global keyword to declare that we want to modify the global variable x from within the function. As a result, the value of x is changed to 5.

It's important to note that it's generally considered good practice to avoid modifying global variables from within functions, as it can lead to unexpected behavior and make your code harder to debug.

I hope this tutorial has helped clarify the differences between local and global variables and how to use the global keyword in Python. Thank you for watching!
## [Next Lesson>>](https://replit.com/@codewithharry/49-Day49-File-IO)

# 49-Day49-File-IO
Python provides several ways to manipulate files. Today, we will discuss how to handle files in Python.
## Opening a File
Before we can perform any operations on a file, we must first open it. Python provides the open() function to open a file. It takes two arguments: the name of the file and the mode in which the file should be opened. The mode can be 'r' for reading, 'w' for writing, or 'a' for appending.

Here's an example of how to open a file for reading:
```python
f = open('myfile.txt', 'r')
```
By default, the open() function returns a file object that can be used to read from or write to the file, depending on the mode.
## Modes in file
There are various modes in which we can open files.

1. read (r): This mode opens the file for reading only and gives an error if the file does not exist. This is the default mode if no mode is passed as a parameter.
2. write (w): This mode opens the file for writing only and creates a new file if the file does not exist.
3. append (a): This mode opens the file for appending only and creates a new file if the file does not exist.
4. create (x): This mode creates a file and gives an error if the file already exists.
 
5. text (t): 
Apart from these modes we also need to specify how the file must be handled. t mode is used to handle text files. t refers to the text mode. There is no difference between r and rt or w and wt since text mode is the default. The default mode is 'r' (open for reading text, synonym of 'rt' ).
6. binary (b): used to handle binary files (images, pdfs, etc).
## Reading from a File
Once we have a file object, we can use various methods to read from the file.

The read() method reads the entire contents of the file and returns it as a string.
```python 
f = open('myfile.txt', 'r')
contents = f.read()
print(contents)
```


## Writing to a File
To write to a file, we first need to open it in write mode.
```python
f = open('myfile.txt', 'w')

```
We can then use the write() method to write to the file.
```python
f = open('myfile.txt', 'w')
f.write('Hello, world!')

```
Keep in mind that writing to a file will overwrite its contents. If you want to append to a file instead of overwriting it, you can open it in append mode.

```python 
f = open('myfile.txt', 'a')
f.write('Hello, world!')
```
## Closing a File
It is important to close a file after you are done with it. This releases the resources used by the file and allows other programs to access it.

To close a file, you can use the close() method.
```python 
f = open('myfile.txt', 'r')
# ... do something with the file
f.close()

```
## The 'with' statement
Alternatively, you can use the with statement to automatically close the file after you are done with it.

```python
with open('myfile.txt', 'r') as f:
    # ... do something with the file

```
## [Next Lesson>>](https://replit.com/@codewithharry/50-Day50-read-readlines-and-other-methods)

# 50-Day50-read-readlines-and-other-methods
# readlines() method
The readline() method reads a single line from the file. If we want to read multiple lines, we can use a loop.

```python
f = open('myfile.txt', 'r')
while True:
    line = f.readline()
    if not line:
        break
    print(line)

```
The readlines() method reads all the lines of the file and returns them as a list of strings.

# writelines() method
The writelines() method in Python writes a sequence of strings to a file. The sequence can be any iterable object, such as a list or a tuple.

Here's an example of how to use the writelines() method:
```python
f = open('myfile.txt', 'w')
lines = ['line 1\n', 'line 2\n', 'line 3\n']
f.writelines(lines)
f.close()
```
This will write the strings in the lines list to the file myfile.txt. The \n characters are used to add newline characters to the end of each string.

Keep in mind that the writelines() method does not add newline characters between the strings in the sequence. If you want to add newlines between the strings, you can use a loop to write each string separately:
```python
f = open('myfile.txt', 'w')
lines = ['line 1', 'line 2', 'line 3']
for line in lines:
    f.write(line + '\n')
f.close()
```
It is also a good practice to close the file after you are done with it.
## [Next Lesson>>](https://replit.com/@codewithharry/51-Day51-seek-and-tell-functions)

# 51-Day51-seek-and-tell-functions
# seek() and tell() functions
In Python, the seek() and tell() functions are used to work with file objects and their positions within a file. These functions are part of the built-in io module, which provides a consistent interface for reading and writing to various file-like objects, such as files, pipes, and in-memory buffers.
## seek() function
The seek() function allows you to move the current position within a file to a specific point. The position is specified in bytes, and you can move either forward or backward from the current position. For example:
```python
with open('file.txt', 'r') as f:
  # Move to the 10th byte in the file
  f.seek(10)

  # Read the next 5 bytes
  data = f.read(5)
```
## tell() function
The tell() function returns the current position within the file, in bytes. This can be useful for keeping track of your location within the file or for seeking to a specific position relative to the current position. For example:

```python
with open('file.txt', 'r') as f:
  # Read the first 10 bytes
  data = f.read(10)

  # Save the current position
  current_position = f.tell()

  # Seek to the saved position
  f.seek(current_position)
```
## truncate() function
When you open a file in Python using the open function, you can specify the mode in which you want to open the file. If you specify the mode as 'w' or 'a', the file is opened in write mode and you can write to the file. However, if you want to truncate the file to a specific size, you can use the truncate function.

Here is an example of how to use the truncate function:

```python
with open('sample.txt', 'w') as f:
  f.write('Hello World!')
  f.truncate(5)

with open('sample.txt', 'r') as f:
  print(f.read())

```
## [Next Lesson>>](https://replit.com/@codewithharry/52-Day52-Lambda-Functions)


# 52-Day52-Lambda-Functions
# Lambda Functions in Python
In Python, a lambda function is a small anonymous function without a name. It is defined using the lambda keyword and has the following syntax:

```python
lambda arguments: expression
```
Lambda functions are often used in situations where a small function is required for a short period of time. They are commonly used as arguments to higher-order functions, such as map, filter, and reduce.

Here is an example of how to use a lambda function:

```python
# Function to double the input
def double(x):
  return x * 2

# Lambda function to double the input
lambda x: x * 2
```
The above lambda function has the same functionality as the double function defined earlier. However, the lambda function is anonymous, as it does not have a name.

Lambda functions can have multiple arguments, just like regular functions. Here is an example of a lambda function with multiple arguments:

```python
# Function to calculate the product of two numbers
def multiply(x, y):
    return x * y

# Lambda function to calculate the product of two numbers
lambda x, y: x * y
```
Lambda functions can also include multiple statements, but they are limited to a single expression. For example:

```python
# Lambda function to calculate the product of two numbers,
# with additional print statement
lambda x, y: print(f'{x} * {y} = {x * y}')
```
In the above example, the lambda function includes a print statement, but it is still limited to a single expression.

Lambda functions are often used in conjunction with higher-order functions, such as map, filter, and reduce which we will look into later.
## [Next Lesson>>](https://replit.com/@codewithharry/53-Day53-Map-Filter-and-Reduce)

# 53-Day53-Map-Filter-and-Reduce
# Map, Filter and Reduce
In Python, the map, filter, and reduce functions are built-in functions that allow you to apply a function to a sequence of elements and return a new sequence. These functions are known as higher-order functions, as they take other functions as arguments.

## map
The map function applies a function to each element in a sequence and returns a new sequence containing the transformed elements. The map function has the following syntax:

```python
map(function, iterable)
```
The function argument is a function that is applied to each element in the iterable argument. The iterable argument can be a list, tuple, or any other iterable object.

Here is an example of how to use the map function:

```python
# List of numbers
numbers = [1, 2, 3, 4, 5]

# Double each number using the map function
doubled = map(lambda x: x * 2, numbers)

# Print the doubled numbers
print(list(doubled))
```
In the above example, the lambda function lambda x: x * 2 is used to double each element in the numbers list. The map function applies the lambda function to each element in the list and returns a new list containing the doubled numbers.

## filter
The filter function filters a sequence of elements based on a given predicate (a function that returns a boolean value) and returns a new sequence containing only the elements that meet the predicate. The filter function has the following syntax:

```python
filter(predicate, iterable)
```
The predicate argument is a function that returns a boolean value and is applied to each element in the iterable argument. The iterable argument can be a list, tuple, or any other iterable object.

Here is an example of how to use the filter function:

```python
# List of numbers
numbers = [1, 2, 3, 4, 5]

# Get only the even numbers using the filter function
evens = filter(lambda x: x % 2 == 0, numbers)

# Print the even numbers
print(list(evens))
```
In the above example, the lambda function lambda x: x % 2 == 0 is used to filter the numbers list and return only the even numbers. The filter function applies the lambda function to each element in the list and returns a new list containing only the even numbers.

## reduce
The reduce function is a higher-order function that applies a function to a sequence and returns a single value. It is a part of the functools module in Python and has the following syntax:
```python
reduce(function, iterable)
```
The function argument is a function that takes in two arguments and returns a single value. The iterable argument is a sequence of elements, such as a list or tuple.

The reduce function applies the function to the first two elements in the iterable and then applies the function to the result and the next element, and so on. The reduce function returns the final result.

Here is an example of how to use the reduce function:

```python
from functools import reduce

# List of numbers
numbers = [1, 2, 3, 4, 5]

# Calculate the sum of the numbers using the reduce function
sum = reduce(lambda x, y: x + y, numbers)

# Print the sum
print(sum)
```
In the above example, the reduce function applies the lambda function lambda x, y: x + y to the elements in the numbers list. The lambda function adds the two arguments x and y and returns the result. The reduce function applies the lambda function to the first two elements in the list (1 and 2), then applies the function to the result (3) and the next element (3), and so on. The final result is the sum of all the elements in the list, which is 15.

It is important to note that the reduce function requires the functools module to be imported in order to use it.

## [Next Lesson>>](https://replit.com/@codewithharry/54-Day54-is-vs-in-Python)

# 54-Day54-is-vs-in-Python
# 'is' vs '==' in Python
In Python, is and == are both comparison operators that can be used to check if two values are equal. However, there are some important differences between the two that you should be aware of.

The is operator compares the identity of two objects, while the == operator compares the values of the objects. This means that is will only return True if the objects being compared are the exact same object in memory, while == will return True if the objects have the same value.

For example:

```python
a = [1, 2, 3]
b = [1, 2, 3]

print(a == b)  # True
print(a is b)  # False
```
In this case, a and b are two separate lists that have the same values, so == returns True. However, a and b are not the same object in memory, so is returns False.

One important thing to note is that, in Python, strings and integers are immutable, which means that once they are created, their value cannot be changed. This means that, for strings and integers, is and == will always return the same result:

```python
a = "hello"
b = "hello"

print(a == b)  # True
print(a is b)  # True

a = 5
b = 5

print(a == b)  # True
print(a is b)  # True
```
In these cases, a and b are both pointing to the same object in memory, so is and == both return True.

For mutable objects such as lists and dictionaries, is and == can behave differently. In general, you should use == when you want to compare the values of two objects, and use is when you want to check if two objects are the same object in memory.

I hope this helps clarify the difference between is and == in Python!
## [Next Lesson>>](https://replit.com/@codewithharry/55-Day55-Exercise-5)

# 55-Day55-Exercise-5
# Snake Water Gun
Snake, Water and Gun is a variation of the children's game "rock-paper-scissors" where players use hand gestures to represent a snake, water, or a gun. The gun beats the snake, the water beats the gun, and the snake beats the water.
Write a python program to create a Snake Water Gun game in Python using if-else statements. Do not create any fancy GUI. Use proper functions to check for win.

## [Next Lesson>>](https://replit.com/@codewithharry/56-Day56-Intro-to-oops)


# 56-Day56-Intro-to-oops
# Introduction to Object-oriented programming
Introduction to Object-Oriented Programming in Python: In programming languages, mainly there are two approaches that are used to write program or code.
- 1). Procedural Programming
- 2). Object-Oriented Programming

The procedure we are following till now is the “Procedural Programming” approach. So, in this session, we will learn about Object Oriented Programming (OOP).
The basic idea of object-oriented programming (OOP) in Python is to use classes and objects to represent real-world concepts and entities.

A class is a blueprint or template for creating objects. It defines the properties and methods that an object of that class will have. Properties are the data or state of an object, and methods are the actions or behaviors that an object can perform.

An object is an instance of a class, and it contains its own data and methods. For example, you could create a class called "Person" that has properties such as name and age, and methods such as speak() and walk(). Each instance of the Person class would be a unique object with its own name and age, but they would all have the same methods to speak and walk.

One of the key features of OOP in Python is encapsulation, which means that the internal state of an object is hidden and can only be accessed or modified through the object's methods. This helps to protect the object's data and prevent it from being modified in unexpected ways.

Another key feature of OOP in Python is inheritance, which allows new classes to be created that inherit the properties and methods of an existing class. This allows for code reuse and makes it easy to create new classes that have similar functionality to existing classes.

Polymorphism is also supported in Python, which means that objects of different classes can be treated as if they were objects of a common class. This allows for greater flexibility in code and makes it easier to write code that can work with multiple types of objects.

In summary, OOP in Python allows developers to model real-world concepts and entities using classes and objects, encapsulate data, reuse code through inheritance, and write more flexible code through polymorphism.
 ## [Next Lesson>>](https://replit.com/@codewithharry/57-Day57-Classes-and-Objects)


# 58-Day58-Constructors
# Constructors
A constructor is a special method in a class used to create and initialize an object of a class. There are different types of constructors. Constructor is invoked automatically when an object of a class is created.

A constructor is a unique function that gets called automatically when an object is created of a class. 
The main purpose of a constructor is to initialize or assign values to the data members of that class. It cannot return any value other than None.
## Syntax of Python Constructor
```python
def __init__(self):
	# initializations
 ```
init is one of the reserved functions in Python. In Object Oriented Programming, it is known as a constructor.

 ## Types of Constructors in Python
1. Parameterized Constructor
2. Default Constructor
  
### Parameterized Constructor in Python
When the constructor accepts arguments along with self, it is known as parameterized constructor.

These arguments can be used inside the class to assign the values to the data members. 
#### Example:
``` python
class Details:
    def __init__(self, animal, group):
        self.animal = animal
        self.group = group

obj1 = Details("Crab", "Crustaceans")
print(obj1.animal, "belongs to the", obj1.group, "group.")
```
#### Output:
```
Crab belongs to the Crustaceans group.
```
### Default Constructor in Python
When the constructor doesn't accept any arguments from the object and has only one argument, self, in the constructor, it is known as a Default constructor.
#### Example:
```python
class Details:
  def __init__(self):
    print("animal Crab belongs to Crustaceans group")
obj1=Details()
```
#### Output:
```
animal Crab belongs to Crustaceans group
```
## [Next Lesson>>](https://replit.com/@codewithharry/59-Day-59-Decorators-in-Python)

# 59-Day-59-Decorators-in-Python
# Python Decorators
Python decorators are a powerful and versatile tool that allow you to modify the behavior of functions and methods. They are a way to extend the functionality of a function or method without modifying its source code.

A decorator is a function that takes another function as an argument and returns a new function that modifies the behavior of the original function. The new function is often referred to as a "decorated" function. The basic syntax for using a decorator is the following:
```python
@decorator_function
def my_function():
    pass
```

The @decorator_function notation is just a shorthand for the following code:
```python
def my_function():
    pass
my_function = decorator_function(my_function)
```
Decorators are often used to add functionality to functions and methods, such as logging, memoization, and access control.

## Practical use case
One common use of decorators is to add logging to a function. For example, you could use a decorator to log the arguments and return value of a function each time it is called:
```python
import logging

def log_function_call(func):
    def decorated(*args, **kwargs):
        logging.info(f"Calling {func.__name__} with args={args}, kwargs={kwargs}")
        result = func(*args, **kwargs)
        logging.info(f"{func.__name__} returned {result}")
        return result
    return decorated

@log_function_call
def my_function(a, b):
    return a + b
```

In this example, the log_function_call decorator takes a function as an argument and returns a new function that logs the function call before and after the original function is called.

## Conclusion
Decorators are a powerful and flexible feature in Python that can be used to add functionality to functions and methods without modifying their source code. They are a great tool for separating concerns, reducing code duplication, and making your code more readable and maintainable.

In conclusion, python decorators are a way to extend the functionality of functions and methods, by modifying its behavior without modifying the source code. They are used for a variety of purposes, such as logging, memoization, access control, and more. They are a powerful tool that can be used to make your code more readable, maintainable, and extendable.
## [Next Lesson>>](https://replit.com/@codewithharry/60-Day-60-Getters-and-Setters)


# 60-Day-60-Getters-and-Setters
# Getters
Getters in Python are methods that are used to access the values of an object's properties. They are used to return the value of a specific property, and are typically defined using the @property decorator.
Here is an example of a simple class with a getter method:
```python
class MyClass:
    def __init__(self, value):
        self._value = value

    @property
    def value(self):
        return self._value
```
In this example, the MyClass class has a single property, _value, which is initialized in the __init__ method. The value method is defined as a getter using the @property decorator, and is used to return the value of the _value property.

To use the getter, we can create an instance of the MyClass class, and then access the value property as if it were an attribute:
```python
>>> obj = MyClass(10)
>>> obj.value
10
```
# Setters
It is important to note that the getters do not take any parameters and we cannot set the value through getter method.For that we need setter method which can be added by decorating method with @property_name.setter

Here is an example of a class with both getter and setter:

```python
class MyClass:
    def __init__(self, value):
        self._value = value

    @property
    def value(self):
        return self._value

    @value.setter
    def value(self, new_value):
        self._value = new_value
```
We can use setter method like this:
```python
>>> obj = MyClass(10)
>>> obj.value = 20
>>> obj.value
20
```
In conclusion, getters are a convenient way to access the values of an object's properties, while keeping the internal representation of the property hidden. This can be useful for encapsulation and data validation.
## [Next Lesson>>](https://replit.com/@codewithharry/61-Day-61-Inheritance-in-Python)

# 63-Day-63-Exercise-5-Solution
## Snake Water Gun
Snake, Water and Gun is a variation of the children's game "rock-paper-scissors" where players use hand gestures to represent a snake, water, or a gun. The gun beats the snake, the water beats the gun, and the snake beats the water. Write a python program to create a Snake Water Gun game in Python using if-else statements. Do not create any fancy GUI. Use proper functions to check for win.
## [Next Lesson>>](https://replit.com/@codewithharry/64-Day-64-Exercise-6)

# 64-Day-64-Exercise-6
Write a Library class with no_of_books and books as two instance variables. Write a program to create a library from this Library class and show how  you can print all books, add a book and get the number of books using  different methods. Show that your program doesnt persist the books after the program is stopped!
## [Next Lesson>>](https://replit.com/@codewithharry/65-Day-65-Static-Methods)

# 65-Day-65-Static-Methods
Static methods in Python are methods that belong to a class rather than an instance of the class. They are defined using the @staticmethod decorator and do not have access to the instance of the class (i.e. self). They are called on the class itself, not on an instance of the class. Static methods are often used to create utility functions that don't need access to instance data.

```python
class Math:
    @staticmethod
    def add(a, b):
        return a + b

result = Math.add(1, 2)
print(result) # Output: 3
```
In this example, the add method is a static method of the Math class. It takes two parameters a and b and returns their sum. The method can be called on the class itself, without the need to create an instance of the class.
## [Next Lesson>>](https://replit.com/@codewithharry/66-Day-66-Instance-vs-Class-variables)

# 66-Day-66-Instance-vs-Class-variables
# Instance vs class variables
In Python, variables can be defined at the class level or at the instance level. Understanding the difference between these types of variables is crucial for writing efficient and maintainable code.

## Class Variables
Class variables are defined at the class level and are shared among all instances of the class. They are defined outside of any method and are usually used to store information that is common to all instances of the class. For example, a class variable can be used to store the number of instances of a class that have been created.
```python
class MyClass:
    class_variable = 0
    
    def __init__(self):
        MyClass.class_variable += 1
        
    def print_class_variable(self):
        print(MyClass.class_variable)
        

obj1 = MyClass()
obj2 = MyClass()

obj1.print_class_variable() # Output: 2
obj2.print_class_variable() # Output: 2

```

In the example above, the class_variable is shared among all instances of the class MyClass. When we create new instances of MyClass, the value of class_variable is incremented. When we call the print_class_variable method on obj1 and obj2, we get the same value of class_variable.

## Instance Variables
Instance variables are defined at the instance level and are unique to each instance of the class. They are defined inside the __init__ method and are usually used to store information that is specific to each instance of the class. For example, an instance variable can be used to store the name of an employee in a class that represents an employee.
```python
class MyClass:
    def __init__(self, name):
        self.name = name
        
    def print_name(self):
        print(self.name)

obj1 = MyClass("John")
obj2 = MyClass("Jane")

obj1.print_name() # Output: John
obj2.print_name() # Output: Jane
```

In the example above, each instance of the class MyClass has its own value for the name variable. When we call the print_name method on obj1 and obj2, we get different values for name.

## Summary
In summary, class variables are shared among all instances of a class and are used to store information that is common to all instances. Instance variables are unique to each instance of a class and are used to store information that is specific to each instance. Understanding the difference between class variables and instance variables is crucial for writing efficient and maintainable code in Python.

It's also worth noting that, in python, class variables are defined outside of any methods and don't need to be explicitly declared as class variable. They are defined in the class level and can be accessed via classname.varibale_name or self.class.variable_name. But instance variables are defined inside the methods and need to be explicitly declared as instance variable by using self.variable_name.
## [Next Lesson>>](https://replit.com/@codewithharry/67-Day-67-Exercise-6-Solution)

# 67-Day-67-Exercise-6-Solution
Write a Library class with no_of_books and books as two instance variables. Write a program to create a library from this Library class and show how you can print all books, add a book and get the number of books using different methods. Show that your program doesnt persist the books after the program is stopped!
## [Next Lesson>>](https://replit.com/@codewithharry/68-Day-68-Exercise-7)


# 68-Day-68-Exercise-7
Write a program to clear the clutter inside a folder on your computer. 
You should use os module to rename all the png images from 1.png all the way till n.png where n is the number of png files in that folder. Do the same for other file formats. For example:
- sfdsf.png --> 1.png
- vfsf.png --> 2.png
- this.png --> 3.png
- design.png --> 4.png
- name.png --> 5.png
## [Next Lesson>>](https://replit.com/@codewithharry/69-Day-69-Class-Methods)

# 69-Day-69-Class-Methods
# Python Class Methods
## Python Class Methods: An Introduction

In Python, classes are a way to define custom data types that can store data and define functions that can manipulate that data. One type of function that can be defined within a class is called a "method." In this blog post, we will explore what Python class methods are, why they are useful, and how to use them.

## What are Python Class Methods?

A class method is a type of method that is bound to the class and not the instance of the class. In other words, it operates on the class as a whole, rather than on a specific instance of the class. Class methods are defined using the "@classmethod" decorator, followed by a function definition. The first argument of the function is always "cls," which represents the class itself.

## Why Use Python Class Methods?

Class methods are useful in several situations. For example, you might want to create a factory method that creates instances of your class in a specific way. You could define a class method that creates the instance and returns it to the caller. Another common use case is to provide alternative constructors for your class. This can be useful if you want to create instances of your class in multiple ways, but still have a consistent interface for doing so.

## How to Use Python Class Methods

To define a class method, you simply use the "@classmethod" decorator before the method definition. The first argument of the method should always be "cls," which represents the class itself. Here is an example of how to define a class method:
```python
class ExampleClass:
    @classmethod
    def factory_method(cls, argument1, argument2):
        return cls(argument1, argument2)
```

In this example, the "factory_method" is a class method that takes two arguments, "argument1" and "argument2." It creates a new instance of the class "ExampleClass" using the "cls" keyword, and returns the new instance to the caller.

It's important to note that class methods cannot modify the class in any way. If you need to modify the class, you should use a class level variable instead.

## Conclusion

Python class methods are a powerful tool for defining functions that operate on the class as a whole, rather than on a specific instance of the class. They are useful for creating factory methods, alternative constructors, and other types of methods that operate at the class level. With the knowledge of how to define and use class methods, you can start writing more complex and organized code in Python.
## [Next Lesson>>](https://replit.com/@codewithharry/70-Day-70-Class-methods-as-alternative-constructors)

# 70-Day-70-Class-methods-as-alternative-constructors
# Class Methods as Alternative Constructors

In object-oriented programming, the term "constructor" refers to a special type of method that is automatically executed when an object is created from a class. The purpose of a constructor is to initialize the object's attributes, allowing the object to be fully functional and ready to use.

However, there are times when you may want to create an object in a different way, or with different initial values, than what is provided by the default constructor. This is where class methods can be used as alternative constructors.

A class method belongs to the class rather than to an instance of the class. One common use case for class methods as alternative constructors is when you want to create an object from data that is stored in a different format, such as a string or a dictionary. For example, consider a class named "Person" that has two attributes: "name" and "age". The default constructor for the class might look like this:

```python
class Person:
    def __init__(self, name, age):
        self.name = name
        self.age = age
```

But what if you want to create a Person object from a string that contains the person's name and age, separated by a comma? You can define a class method named "from_string" to do this:
```python
class Person:
    def __init__(self, name, age):
        self.name = name
        self.age = age

    @classmethod
    def from_string(cls, string):
        name, age = string.split(',')
        return cls(name, int(age))
```
Now you can create a Person object from a string like this:
```python 
person = Person.from_string("John Doe, 30")
```

Another common use case for class methods as alternative constructors is when you want to create an object with a different set of default values than what is provided by the default constructor. For example, consider a class named "Rectangle" that has two attributes: "width" and "height". The default constructor for the class might look like this:
```python
class Rectangle:
    def __init__(self, width, height):
        self.width = width
        self.height = height

```
But what if you want to create a Rectangle object with a default width of 10 and a default height of 5? You can define a class method named "square" to do this:
```python
class Rectangle:
  def __init__(self, width, height):
    self.width = width
    self.height = height

  @classmethod
  def square(cls, size):
    return cls(size, size)
```
Now you can create a square rectangle like this:

```python
rectangle = Rectangle.square(10)
```
## [Next Lesson>>](https://replit.com/@codewithharry/71-Day-71-dir-dict-and-help-methods)

# 71-Day-71-dir-dict-and-help-methods
# `dir()`, `__dict__` and `help()` methods in python
We must look into `dir()`,  `__dict__()` and `help()` attribute/methods in python. They make it easy for us to understand how classes resolve various functions and executes code. 
In Python, there are three built-in functions that are commonly used to get information about objects: dir(), __dict__, and help(). Let's take a look at each of them:
## The `dir()` method
`dir()`: The dir() function returns a list of all the attributes and methods (including dunder methods) available for an object. It is a useful tool for discovering what you can do with an object.
Example:

```python
>>> x = [1, 2, 3]
>>> dir(x)
['__add__', '__class__', '__contains__', '__delattr__', '__delitem__', '__dir__', '__doc__', '__eq__', '__format__', '__ge__', '__getattribute__', '__getitem__', '__gt__', '__hash__', '__iadd__', '__imul__', '__init__', '__init_subclass__', '__iter__', '__le__', '__len__', '__lt__', '__mul__', '__ne__', '__new__', '__reduce__', '__reduce_ex__', '__repr__', '__reversed__', '__rmul__', '__setattr__', '__setitem__', '__sizeof__', '__str__', '__subclasshook__', 'append', 'clear', 'copy', 'count', 'extend', 'index', 'insert', 'pop', 'remove', 'reverse', 'sort']
```

## The `__dict__` attribute
``__dict__``: The `__dict__` attribute returns a dictionary representation of an object's attributes. It is a useful tool for introspection.
Example:

```python
>>> class Person:
...     def __init__(self, name, age):
...         self.name = name
...         self.age = age
...
>>> p = Person("John", 30)
>>> p.__dict__
```
### Output
```
{'name': 'John', 'age': 30}
```
## The help() mehthod
`help()`: The help() function is used to get help documentation for an object, including a description of its attributes and methods.
Example:

```python
>>> help(str)
Help on class str in module builtins:

class str(object)
 |  str(object='') -> str
 |  str(bytes_or_buffer[, encoding[, errors]]) -> str
 |
 |  Create a new string object from the given object. If encoding or
 |  errors is specified, then the object must expose a data buffer
 |  that will be decoded using the given encoding and error handler.
 |  Otherwise, returns the result of object.__str__() (if defined)
 |  or repr(object).
 |  encoding defaults to sys.getdefaultencoding().
 |  errors defaults to 'strict'.
   ```
In conclusion, dir(), __dict__, and help() are useful built-in functions in Python that can be used to get information about objects. They are valuable tools for introspection and discovery.
## [Next Lesson>>](https://replit.com/@codewithharry/72-Day-72-super-Keyword)

# 72-Day-72-super-Keyword
# Super keyword in Python 
The super() keyword in Python is used to refer to the parent class. It is especially useful when a class inherits from multiple parent classes and you want to call a method from one of the parent classes.

When a class inherits from a parent class, it can override or extend the methods defined in the parent class. However, sometimes you might want to use the parent class method in the child class. This is where the super() keyword comes in handy.


Here's an example of how to use the super() keyword in a simple inheritance scenario:

```python
class ParentClass:
    def parent_method(self):
        print("This is the parent method.")

class ChildClass(ParentClass):
    def child_method(self):
        print("This is the child method.")
        super().parent_method()

child_object = ChildClass()
child_object.child_method()
```
## Output:

```python 
This is the child method.
This is the parent method.
  ```
In this example, we have a ParentClass with a parent_method and a ChildClass that inherits from ParentClass and overrides the child_method. When the child_method is called, it first prints "This is the child method." and then calls the parent_method using the super() keyword.

The super() keyword is also useful when a class inherits from multiple parent classes. In this case, you can specify the parent class from which you want to call the method.

Here's an example:

```python
class ParentClass1:
    def parent_method(self):
        print("This is the parent method of ParentClass1.")

class ParentClass2:
    def parent_method(self):
        print("This is the parent method of ParentClass2.")

class ChildClass(ParentClass1, ParentClass2):
    def child_method(self):
        print("This is the child method.")
        super().parent_method()

child_object = ChildClass()
child_object.child_method()
```
### Output:
```python 
This is the child method.
This is the parent method of ParentClass1.
```
In this example, the ChildClass inherits from both ParentClass1 and ParentClass2. The child_method calls the parent_method of the first parent class using the super() keyword.

In conclusion, the super() keyword is a useful tool in Python when you want to call a parent class method in a child class. It can be used in inheritance scenarios with a single parent class or multiple parent classes.
## [Next Lesson>>](https://replit.com/@codewithharry/73-Day-73-MagicDunder-Methods)

# 73-Day-73-MagicDunder-Methods
# Magic/Dunder Methods in Python
These are special methods that you can define in your classes, and when invoked, they give you a powerful way to manipulate objects and their behaviour.

Magic methods, also known as “dunders” from the double underscores surrounding their names, are powerful tools that allow you to customize the behaviour of your classes. They are used to implement special methods such as the addition, subtraction and comparison operators, as well as some more advanced techniques like descriptors and properties.

Let’s take a look at some of the most commonly used magic methods in Python.
## `__init__ method`
The __init__ method is a special method that is automatically invoked when you create a new instance of a class. This method is responsible for setting up the object’s initial state, and it is where you would typically define any instance variables that you need.
Also called "constructor", we have discussed this method already
## `__str__ and __repr__ methods`
The __str__ and __repr__ methods are both used to convert an object to a string representation. The __str__ method is used when you want to print out an object, while the __repr__ method is used when you want to get a string representation of an object that can be used to recreate the object.
## `__len__ method`

The __len__ method is used to get the length of an object. This is useful when you want to be able to find the size of a data structure, such as a list or dictionary.


## `__call__ method`
The __call__ method is used to make an object callable, meaning that you can pass it as a parameter to a function and it will be executed when the function is called. This is an incredibly powerful tool that allows you to create objects that behave like functions.

These are just a few of the many magic methods available in Python. They are incredibly powerful tools that allow you to customize the behaviour of your objects, and can make your code much cleaner and easier to understand. So if you’re looking for a way to take your Python code to the next level, take some time to learn about these magic methods.
## [Next Lesson>>](https://replit.com/@codewithharry/74-Day-74-Method-Overriding)

# 74-Day-74-Method-Overriding
# Method Overriding in Python

Method overriding is a powerful feature in object-oriented programming that allows you to redefine a method in a derived class. The method in the derived class is said to override the method in the base class. When you create an instance of the derived class and call the overridden method, the version of the method in the derived class is executed, rather than the version in the base class.

In Python, method overriding is a way to customize the behavior of a class based on its specific needs. For example, consider the following base class:

```python
class Shape:
    def area(self):
        pass
```
In this base class, the area method is defined, but does not have any implementation. If you want to create a derived class that represents a circle, you can override the area method and provide an implementation that calculates the area of a circle:

```python
class Circle(Shape):
    def __init__(self, radius):
        self.radius = radius

    def area(self):
        return 3.14 * self.radius * self.radius
```
In this example, the Circle class inherits from the Shape class, and overrides the area method. The new implementation of the area method calculates the area of a circle, based on its radius.

It's important to note that when you override a method, the new implementation must have the same method signature as the original method. This means that the number and type of arguments, as well as the return type, must be the same.

Another way to customize the behavior of a class is to call the base class method from the derived class method. To do this, you can use the super function. The super function allows you to call the base class method from the derived class method, and can be useful when you want to extend the behavior of the base class method, rather than replace it.

For example, consider the following base class:

```python
class Shape:
    def area(self):
        print("Calculating area...")
```
In this base class, the area method prints a message indicating that the area is being calculated. If you want to create a derived class that represents a circle, and you also want to print a message indicating the type of shape, you can use the super function to call the base class method, and add your own message:

```python
class Circle(Shape):
    def __init__(self, radius):
        self.radius = radius

    def area(self):
        print("Calculating area of a circle...")
        super().area()
        return 3.14 * self.radius * self.radius
```
In this example, the Circle class overrides the area method, and calls the base class method using the super function. This allows you to extend the behavior of the base class method, while still maintaining its original behavior.

In conclusion, method overriding is a powerful feature in Python that allows you to customize the behavior of a class based on its specific needs. By using method overriding, you can create more robust and reliable code, and ensure that your classes behave in the way that you need them to. Additionally, by using the super function, you can extend the behavior of a base class method, rather than replace it, giving you even greater flexibility and control over the behavior of your classes.
## [Next Lesson>>](https://replit.com/@codewithharry/75-Day-75-Exercise-7-Solution)

# 76-Day-76-Exercise-8
Write a program to manipulate pdf files using pyPDF. Your programs should be able to merge multiple pdf files into a single pdf. You are welcome to add more functionalities

pypdf is a free and open-source pure-python PDF library capable of splitting, merging, cropping, and transforming the pages of PDF files. It can also add custom data, viewing options, and passwords to PDF files. pypdf can retrieve text and metadata from PDFs as well.
## [Next Lesson>>](https://replit.com/@codewithharry/77-Day-77-Operator-Overloading)

# 77-Day-77-Operator-Overloading
# Operator Overloading in Python: An Introduction

Operator Overloading is a feature in Python that allows developers to redefine the behavior of mathematical and comparison operators for custom data types. This means that you can use the standard mathematical operators (+, -, *, /, etc.) and comparison operators (>, <, ==, etc.) in your own classes, just as you would for built-in data types like int, float, and str.

## Why do we need operator overloading?

Operator overloading allows you to create more readable and intuitive code. For instance, consider a custom class that represents a point in 2D space. You could define a method called 'add' to add two points together, but using the + operator makes the code more concise and readable:

```python
p1 = Point(1, 2)
p2 = Point(3, 4)
p3 = p1 + p2
print(p3.x, p3.y) # prints 4, 6
```

### How to overload an operator in Python?

You can overload an operator in Python by defining special methods in your class. These methods are identified by their names, which start and end with double underscores (__). Here are some of the most commonly overloaded operators and their corresponding special methods:
```
+ : __add__
- : __sub__
* : __mul__
/ : __truediv__
< : __lt__
> : __gt__
== : __eq__
```
For example, if you want to overload the + operator to add two instances of a custom class, you would define the __add__ method:

```python
class Point:
    def __init__(self, x, y):
        self.x = x
        self.y = y

    def __add__(self, other):
        return Point(self.x + other.x, self.y + other.y)
```
It's important to note that operator overloading is not limited to the built-in operators, you can overload any user-defined operator as well.

## Conclusion

Operator overloading is a powerful feature in Python that allows you to create more readable and intuitive code. By redefining the behavior of mathematical and comparison operators for custom data types, you can write code that is both concise and expressive. However, it's important to use operator overloading wisely, as overloading the wrong operator or using it inappropriately can lead to confusing or unexpected behavior.
## [Next Lesson>>](https://replit.com/@codewithharry/78-Day-78-Single-Inheritance)

# 82-Day-82-Exercise-8-Solution
Write a program to manipulate pdf files using pyPDF. Your programs should be able to merge multiple pdf files into a single pdf. You are welcome to add more functionalities

pypdf is a free and open-source pure-python PDF library capable of splitting, merging, cropping, and transforming the pages of PDF files. It can also add custom data, viewing options, and passwords to PDF files. pypdf can retrieve text and metadata from PDFs as well.
## [Next Lesson>>](https://replit.com/@codewithharry/83-Day-83-Exercise-9)

# 83-Day-83-Exercise-9
Write a program to pronounce list of names using win32 API. 
If you are given a list l as follows:
```python
l = ["Rahul", "Nishant", "Harry"]
```
Your program should pronouce:
```
Shoutout to Rahul
Shoutout to Nishant
Shoutout to Harry
```
Note: If you are not using windows, try to figure out how to do the same thing using some other package
## [Next Lesson>>](https://replit.com/@codewithharry/84-Day-84-Time-Module)


# 85-Day-85-Command-Line-Utility
# Creating Command Line Utilities in Python
Command line utilities are programs that can be run from the terminal or command line interface, and they are an essential part of many development workflows. In Python, you can create your own command line utilities using the built-in `argparse` module.

## Syntax
Here is the basic syntax for creating a command line utility using `argparse` in Python:
```python
import argparse

parser = argparse.ArgumentParser()

# Add command line arguments
parser.add_argument("arg1", help="description of argument 1")
parser.add_argument("arg2", help="description of argument 2")

# Parse the arguments
args = parser.parse_args()

# Use the arguments in your code
print(args.arg1)
print(args.arg2)
```
## Examples
Here are a few examples to help you get started with creating command line utilities in Python:

### Adding optional arguments
The following example shows how to add an optional argument to your command line utility:
```python
import argparse

parser = argparse.ArgumentParser()

parser.add_argument("-o", "--optional", help="description of optional argument", default="default_value")

args = parser.parse_args()

print(args.optional)
```
### Adding positional arguments
The following example shows how to add a positional argument to your command line utility:
```python
import argparse

parser = argparse.ArgumentParser()

parser.add_argument("positional", help="description of positional argument")

args = parser.parse_args()

print(args.positional)
```
### Adding arguments with type
The following example shows how to add an argument with a specified type:
```python
import argparse

parser = argparse.ArgumentParser()

parser.add_argument("-n", type=int, help="description of integer argument")

args = parser.parse_args()

print(args.n)
```
## Conclusion
Creating command line utilities in Python is a straightforward and flexible process thanks to the `argparse` module. With a few lines of code, you can create powerful and customizable command line tools that can make your development workflow easier and more efficient. Whether you're working on small scripts or large applications, the `argparse` module is a must-have tool for any Python developer.
## [Next Lesson>>](https://replit.com/@codewithharry/86-Day-86-Walrus-Operator)

# 86-Day-86-Walrus-Operator
# The Walrus Operator in Python
The Walrus Operator is a new addition to Python 3.8 and allows you to assign a value to a variable within an expression. This can be useful when you need to use a value multiple times in a loop, but don't want to repeat the calculation.

The Walrus Operator is represented by the `:=` syntax and can be used in a variety of contexts including while loops and if statements.

Here's an example of how you can use the Walrus Operator in a while loop:
```python
numbers = [1, 2, 3, 4, 5]

while (n := len(numbers)) > 0:
    print(numbers.pop())
```
In this example, the length of the `numbers` list is assigned to the variable n using the Walrus Operator. The value of `n` is then used in the condition of the while loop, so that the loop will continue to execute until the `numbers` list is empty.

Another example of using the Walrus Operator in an if statement:
```python
names = ["John", "Jane", "Jim"]

if (name := input("Enter a name: ")) in names:
    print(f"Hello, {name}!")
else:
    print("Name not found.")
```
Here is another example 
```python
# walrus operator :=

# new to Python 3.8
# assignment expression aka walrus operator
# assigns values to variables as part of a larger expression

# happy = True
# print(happy)

# print(happy := True)

# foods = list()
# while True:
#   food = input("What food do you like?: ")
#       if food == "quit":
#           break
#   foods.append(food)

foods = list()
while (food := input("What food do you like?: ")) != "quit":
    foods.append(food)
```
In this example, the user input is assigned to the variable `name` using the Walrus Operator. The value of `name` is then used in the if statement to determine whether it is in the names list. If it is, the corresponding message is printed, otherwise, a different message is printed.

It is important to note that the Walrus Operator should be used sparingly as it can make code less readable if overused.

In conclusion, the Walrus Operator is a useful tool for Python developers to have in their toolkit. It can help streamline code and reduce duplication, but it should be used with care to ensure code readability and maintainability.

## [Next Lesson>>](https://replit.com/@codewithharry/87-Day-87-Shutil-Module)

# 87-Day-87-Shutil-Module
# Shutil Module in Python
Shutil is a Python module that provides a higher level interface for working with file and directories. The name "shutil" is short for shell utility. It provides a convenient and efficient way to automate tasks that are commonly performed on files and directories. In this repl, we'll take a closer look at the shutil module and its various functions and how they can be used in Python.

## Importing shutil
The syntax for importing the shutil module is as follows:
```python
import shutil
```

## Functions
The following are some of the most commonly used functions in the shutil module:

- `shutil.copy(src, dst)`: This function copies the file located at src to a new location specified by dst. If the destination location already exists, the original file will be overwritten.

- `shutil.copy2(src, dst)`: This function is similar to shutil.copy, but it also preserves more metadata about the original file, such as the timestamp.

- `shutil.copytree(src, dst)`: This function recursively copies the directory located at src to a new location specified by dst. If the destination location already exists, the original directory will be merged with it.

- `shutil.move(src, dst)`: This function moves the file located at src to a new location specified by dst. This function is equivalent to renaming a file in most cases.

- `shutil.rmtree(path)`: This function recursively deletes the directory located at path, along with all of its contents. This function is similar to using the rm -rf command in a shell.

## Examples
Here are some examples of how you can use the shutil module in your Python code:

```python
import shutil

# Copying a file
shutil.copy("src.txt", "dst.txt")

# Copying a directory
shutil.copytree("src_dir", "dst_dir")

# Moving a file
shutil.move("src.txt", "dst.txt")

# Deleting a directory
shutil.rmtree("dir")
```
As you can see, the shutil module provides a simple and efficient way to perform common file and directory-related tasks in Python. Whether you need to copy, move, delete, or preserve metadata about files and directories, the shutil module has you covered.

In conclusion, the shutil module is a powerful tool for automating file and directory-related tasks in Python. Whether you are a beginner or an experienced Python developer, the shutil module is an essential tool to have in your toolbox.
## [Next Lesson>>](https://replit.com/@codewithharry/88-Day-88-Exercise-9-Solution)

# 88-Day-88-Exercise-9-Solution
Write a program to pronounce list of names using win32 API. 
If you are given a list l as follows:
```python
l = ["Rahul", "Nishant", "Harry"]
```
Your program should pronouce:
```
Shoutout to Rahul
Shoutout to Nishant
Shoutout to Harry
```
Note: If you are not using windows, try to figure out how to do the same thing using some other package
## [Next Lesson>>](https://replit.com/@codewithharry/89-Day-89-Requests-Module)


# 89-Day-89-Requests-Module
# Requests module in python
The Python Requests module is an HTTP library that enables developers to send HTTP requests in Python. This module enables you to send HTTP requests using Python code and makes it possible to interact with APIs and web services.
## Installation 
```bash
pip install requests
```
## Get Request
Once you have installed the Requests module, you can start using it to send HTTP requests. Here is a simple example that sends a GET request to the Google homepage:
```python
import requests
response = requests.get("https://www.google.com")
print(response.text)
```
## Post Request
Here is another example that sends a POST request to a web service and includes a custom header:
```python
import requests

url = "https://api.example.com/login"
headers = {
    "User-Agent": "Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/58.0.3029.110 Safari/537.36",
    "Content-Type": "application/json"
}
data = {
    "username": "myusername",
    "password": "mypassword"
}

response = requests.post(url, headers=headers, json=data)

print(response.text)
```

In this example, we send a POST request to a web service to authenticate a user. We include a custom User-Agent header and a JSON payload with the user's credentials.

## bs4 Module
There is another module called BeautifulSoup which is used for web scraping in Python. I have personally used bs4 module to finish a lot of freelancing task.
## [Next Lesson>>](https://replit.com/@codewithharry/90-Day-90-Exercise-10)


# 90-Day-90-Exercise-10
# Exercise 10
Use the NewsAPI and the requests module to fetch the daily news related to different topics. 
Go to: https://newsapi.org/
and explore the various options to build you application
## [Next Lesson>>](https://replit.com/@codewithharry/91-Day-91-Generators-in-Python)

# 91-Day-91-Generators-in-Python
# Generators in Python
Generators in Python are special type of functions that allow you to create an iterable sequence of values. A generator function returns a generator object, which can be used to generate the values one-by-one as you iterate over it. Generators are a powerful tool for working with large or complex data sets, as they allow you to generate the values on-the-fly, rather than having to create and store the entire sequence in memory.

## Creating a Generator
In Python, you can create a generator by using the `yield` statement in a function. The `yield` statement returns a value from the generator and suspends the execution of the function until the next value is requested. Here's an example:
```python
def my_generator():
    for i in range(5):
        yield i

gen = my_generator()
print(next(gen))
print(next(gen))
print(next(gen))
print(next(gen))
print(next(gen))
# Output:
# 0
# 1
# 2
# 3
# 4
```
As you can see, the generator function `my_generator()` returns a generator object, which can be used to generate the values in the range 0 to 4. The `next()` function is used to request the next value from the generator, and the generator resumes its execution until it encounters another `yield` statement or until it reaches the end of the function.

## Using a Generator
Once you have created a generator, you can use it in a variety of ways, such as in a for loop, a list comprehension, or a generator expression. Here's an example:
```python
gen = my_generator()
for i in gen:
    print(i)
# Output:
# 0
# 1
# 2
# 3
# 4
```
As you can see, the generator can be used in a for loop, just like any other iterable sequence. The generator is used to generate the values one-by-one as the loop iterates over it.

## Benefits of Generators
Generators offer several benefits over other types of sequences, such as lists, tuples, and sets. One of the main benefits of generators is that they allow you to generate the values on-the-fly, rather than having to create and store the entire sequence in memory. This makes generators a powerful tool for working with large or complex data sets, as you can generate the values as you need them, rather than having to store them all in memory at once.

Another benefit of generators is that they are lazy, which means that the values are generated only when they are requested. This allows you to generate the values in a more efficient and memory-friendly manner, as you don't have to generate all the values up front.

## Conclusion
Generators in Python are a powerful tool for working with large or complex data sets, allowing you to generate the values on-the-fly and store only what you need in memory. Whether you are working with a large dataset, performing complex calculations, or generating a sequence of values, generators are a must-have tool in your programming toolkit. So, if you haven't already, be sure to check out generators in Python and see how they can help you write better, more efficient code.
## [Next Lesson>>](https://replit.com/@codewithharry/92-Day-92-Function-Caching)


# 92-Day-92-Function-Caching
# Function Caching in Python 
Function caching is a technique for improving the performance of a program by storing the results of a function call so that you can reuse the results instead of recomputing them every time the function is called. This can be particularly useful when a function is computationally expensive, or when the inputs to the function are unlikely to change frequently.

In Python, function caching can be achieved using the functools.lru_cache decorator. The functools.lru_cache decorator is used to cache the results of a function so that you can reuse the results instead of recomputing them every time the function is called. Here's an example:

```python
import functools

@functools.lru_cache(maxsize=None)
def fib(n):
    if n < 2:
        return n
    return fib(n-1) + fib(n-2)

print(fib(20))
# Output: 6765
```
As you can see, the `functools.lru_cache` decorator is used to cache the results of the `fib` function. The `maxsize` parameter is used to specify the maximum number of results to cache. If `maxsize` is set to `None`, the cache will have an unlimited size.

## Benefits of Function Caching
Function caching can have a significant impact on the performance of a program, particularly for computationally expensive functions. By caching the results of a function, you can avoid having to recompute the results every time the function is called, which can save a significant amount of time and computational resources.

Another benefit of function caching is that it can simplify the code of a program by removing the need to manually cache the results of a function. With the `functools.lru_cache` decorator, the caching is handled automatically, so you can focus on writing the core logic of your program.

## Conclusion
Function caching is a technique for improving the performance of a program by storing the results of a function so that you can reuse the results instead of recomputing them every time the function is called. In Python 3, function caching can be achieved using the `functools.lru_cache` decorator, which provides an easy and efficient way to cache the results of a function. Whether you're writing a computationally expensive program, or just want to simplify your code, function caching is a great technique to have in your toolbox.
## [Next Lesson>>](https://replit.com/@codewithharry/93-Day-93-Exercise-10-Solution)

# 93-Day-93-Exercise-10-Solution
#Exercise 10
Use the NewsAPI and the requests module to fetch the daily news related to different topics. Go to: https://newsapi.org/ and explore the various options to build you application
## [Next Lesson>>](https://replit.com/@codewithharry/94-Day-94-Exercise-11)

# 94-Day-94-Exercise-11
## Exercise 11 - Drink Water Reminder
Write a python program which reminds you of drinking water every hour or two. Your program can either beep or send desktop notifications for a specific operating system
## [Next Lesson>>](https://replit.com/@codewithharry/95-Day-95-Regular-Expressions)

# 99-Day-99-Exercise-11-Solution
## Exercise 11 - Drink Water Reminder (Solution)
Write a python program which reminds you of drinking water every hour or two. Your program can either beep or send desktop notifications for a specific operating system
## [Next Lesson>>](https://replit.com/@codewithharry/100-Day-100-Conclusion-Where-to-go-from-here)
