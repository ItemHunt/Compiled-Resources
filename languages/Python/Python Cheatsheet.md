# **Python Cheatsheet**
## **Notice**
This cheatsheet will be revised, this will take awhile
<!--
## **Introduction**
This repository is a place where you can view a cheatsheet for the Python programming language. You can also find useful pieces of information here (especially for beginners) and learning resources which are related to Python in one way or another. This repository is a mini-project for a much bigger project called the [*Learning-Hub Project*](https://github.com/ItemHunt/Learning-Hub). 

## **What is Python?**
Python, an interpreted general purpose object-oriented high level programming language that is designed to be very friendly even to beginners. It takes code readability very seriously. You can use Python for things like the data science basics, machine learning, and deep learning as well as database development, backend development and many more. 

## **Current Status of the Python Cheatsheet**
Currently, the Python cheatsheet only covers beginner-level Python code. For people who are already familiar with beginner-level Python, the only useful section of this cheatsheet might be the Learning Resources List section. I recommend that you check that out, it might prove helpful. 

## **How to Contribute**
I welcome any contributors to this mini-project. Feel free to fork the project and add/edit stuff here and send out a pull request for review. If all is good, I should approve the pull request. In case you are new to GitHub, refer to [CONTRIBUTING](CONTRIBUTING.md) for a more detailed guide.

## **Contributors**
<a href="https://github.com/ItemHunt/Python-Cheatsheet/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=ItemHunt/Python-Cheatsheet" />
</a>
<!-- Contributors section made with [contrib.rocks](https://contrib.rocks). -->

<!--

## **Table of Contents**
### **Modules**
- [Math Module](https://github.com/ItemHunt/Python-Cheatsheet#Math-Module-Cheatsheet)
- [Random Module](https://github.com/ItemHunt/Python-Cheatsheet#Random-Module-Cheatsheet)

### **Cheatsheet**
- [Input and Output](https://github.com/ItemHunt/Python-Cheatsheet#Input-and-Output)
- [Mathematical Operators](https://github.com/ItemHunt/Python-Cheatsheet#Mathematical-Operators)
- [Mathematical Functions](https://github.com/ItemHunt/Python-Cheatsheet#Mathematical-Functions)
- [Very Useful Codes](https://github.com/ItemHunt/Python-Cheatsheet#Very-Useful-Codes)
- [Data Types](https://github.com/ItemHunt/Python-Cheatsheet#Data-Types)
- [String Codes](https://github.com/ItemHunt/Python-Cheatsheet#String-Codes)
- [Data Structures and Data Structure Functions](https://github.com/ItemHunt/Python-Cheatsheet#Data-Structures-and-Data-Structure-Functions)
- [Loops and Related Codes](https://github.com/ItemHunt/Python-Cheatsheet#Loops-and-Related-Codes)
- [Conditions](https://github.com/ItemHunt/Python-Cheatsheet#Conditions)
- [Functions](https://github.com/ItemHunt/Python-Cheatsheet#Functions)
- [Classes and Objects](https://github.com/ItemHunt/Python-Cheatsheet#Classes-and-Objects)
- [Other Codes](https://github.com/ItemHunt/Python-Cheatsheet#Other-Codes)

### **Additional Information For Python & Learning Resources List**
- [Additional Information For Python](https://github.com/ItemHunt/Python-Cheatsheet#Additional-Information-For-Python)
- [Learning Resources List](https://github.com/ItemHunt/Python-Cheatsheet#Learning-Resources-List)


## **Cheatsheet**
### **Modules**
A Python module is a Python file that contains useful tools or functions. It can either be modules that already come with Python or custom ones you or some other person made. There are two ways to access a module. Either use ``module import`` or ``from module import *``. ``module import`` gives you access to the module however you need to reference the module every time you use a function from it. ``from module import *`` allows you to use the functions without referencing the module. Example with ``math import`` the square root function is math.sqrt(4). With ``from math import *`` the function gets typed as sqrt(4).

#### **Math Module Cheatsheet**
Module name: *math*
- **``floor(number)`` -** Used to round down a number.
- **``ceil(number)`` -** Used to round up a number.
- **``sqrt(number)`` -** Used to get the squareroot of a number.

#### **Random Module Cheatsheet**
Module name: *random*

### **Input and Output**
- **``print ("Text")`` -** Outputs a string of characters
- **``variable_name = input("Text")`` -** Used to obtain user input, put it in a variable, and add text where you can ask the user for the input you want which is by default in string form

### **Math Operators**
- **``+ (addition)`` -** operator for adding any form of values in things like variables, conditions, and print.
- **``- (subtraction)`` -** operator for subtracting values
- **``* (multiplication)`` -** operator for multiplying values
- **``/ (division)`` -** operator for dividing values
- **``() (parens)`` -** Used for creating groups in a mathematical problem
- **``% (remainder/mod operator)`` -** used to get the remainder of a problem after division
- **``= (assignment)`` -** used to assign a value to a variable
- **``< (less than)`` -** used for creating conditions
- **``> (greater than)`` -** used for creating conditions
- **``<= (less than or equal to)`` -** used for creating conditions
- **``>= (greater than or equal to)`` -** used for creating conditions
- **``== (equals)`` -** used to describe equal
- **``!= (not equals)`` -** negates a condition's output
- **``operator=`` -** used as a shortcut to change the value of variables by using variables to interact with another variable. Examples of operator= are +=, -=, *=, and /=.
- **``#1**#2`` -** Used to raise number 1 by a given number

### **Math Functions**
- **``int(value)`` -** Used to convert anything inside into an integer
- **``float(value)`` -** Used to convert anything inside into a float value(integers/decimal numbers)
- **``abs(variable_name)`` -** Converts number values to its absolute value equivalent
- **``pow(base_number, exponent_number)`` -** Used to calculate for the power of a number
- **``max(number1, number2)`` -** Used to select the largest number
- **``min(number1, number2)`` -** Used to select the smallest number
- **``round(number)`` -** Used to round off a number

### **Very Useful Codes**
- **``\n`` -** allows you to skip another line
- **``\*`` -** allows you to place quotations inside of print commands
- **``# Comment`` -** creates a comment line
- **``""" comment box """`` -** creates a comment box
- **``and`` -** and operator, used for making conditions
- **``or`` -** or operator, used for making conditions
- **``not()`` -** not operator, used for making conditions and negating a condition within the parens


### **Data Types**
- **``variable_name = number_value`` -** used to create variables for any numbers (integers and decimals)
- **``variable_name = "string"`` -** used to create variables for strings. You can use *''* too instead of *""*
- **``variable_name = boolean_value`` -** used to create variables for boolean

### **String Codes**
- **``print (variable_name.upper())`` -** Converts all string variable values into uppercase characters
- **``print (variable_name.isupper())`` -** Returns the boolean value true if all characters in the variable are uppercase characters
- **``print (variable_name.lower())`` -** Converts all string variable values into lowercase characters
- **``print (variable_name.islower())`` -** Returns the boolean value true if all characters in the variable are lowercase characters
- **``print (len(variable_name))`` -** Returns the length of the string variable or the number of characters inside of the string variable.
- **``print (variable_name[index position])`` -** Returns the character present in the specified index position
- **``print (variable_name.index("character that belongs to the string"))`` -** Returns the index position of the specified character or the starting index position of the substring
- **``print (variable_name.replace("what you want to replace", "what you want to replace it with"))`` -**  Replaces the target part of the string variable with a input of your choice
- **``print (str(variable_name))`` -** Converts non-string variables into string variables
- **``print (array_name.index(element))`` -** Used to get the index position of an element inside of an already existing array or list
- **``print (array_name.count(element))`` -** Used to count how many times an element repeats in an already existing array or list

### **Data Structures and Data Structure Functions**
- **``array_name = [element1, element2, elementN]`` -** Used to create an array which can contain many different variables/more arrays
- **``array_name[index_position]`` -** Returns a value from the specified index position. Use positive numbers to go to the right or use negative numbers to go to the left.
- **``array_name[index_position:]`` -** Returns a value from the specified index position as well as all of the next values after the index position.
- **``array_name[index_position1:index_position2]`` -** Returns a range of values from an array. Going from index_position1 to the index before index-position2
- **``array1.extend(array2)`` -** *Extend function*, used to take an array or list and append it to another
- **``array_name.append(new_element)`` -** *Append function*, used to add a new element into an existing array or list
- **``array_name.insert(index_position, element)`` -**  *insert function*, used to insert a new element into the specified index position in an already existing array or list
- **``array_name.remove(element)`` -** *Remove function*, used to remove an existing element inside of an existing array. 
- **``array_name.clear()`` -** *Clear function*, used to remove all elements inside of an already existing array or list.
- **``array_name.pop()`` -** *Pop function*, used to remove the last element of an existing array or list. 
- **``array_name.sort()`` -** *Sort function*, used to sort an array in ascending order
- **``array_name.reverse()`` -** *Reverse function*, reverse the order of an array
- **``len(array_name)`` -** Returns the number of elements inside of the specified array
- **``new_array_name = existing_array_name.copy()`` -** *Copy function*, used to create a new array and have it copy the contents of an already existing array
- **``tuple_name = ()`` -** *Tuple data structure*, an immutable Python code.
- **``Dictionary_name = {Key1:Value1, Key2:Value2, KeyN:ValueN  }`` -** *Dictionary*, also known as an *assosiative array*, contains pairs of keys that correspond or associates itself to a value. Keys cannot have the same value as other keys.
- **``dictionary_name[key]`` -** Returns the value that corresponds to the given key
- **``dictionary_name.get(key, default_value)`` -** Returns the value that corresponds to the given key. *, default_value* is not necessary but it provides a value to be presented in case the key doesn't exist in the dictionary

### **Loops and Related Codes**
- **``while condition: indented_code_block`` -** Creates a while loop
- **``for new_variable_name in value: indented_code_block`` -** Creates a for loop. Value can also be in the form of variable, data structure, *range(#)*, or *range(#1, #2)* where # is any number. 

### **Conditions**
- **``if condition: indented_code_block`` -** Creates an if statement.
- **``elif condition: indented_code_block`` -**  Creates an else if statement. Can only be used after an if statement.
- **``else: indented_code_block`` -** Creates an else statement. Can only be used after an if statement or elif.

### **Functions**
- **``def function_name(parameter1, parameter2, parameterN): indented_code `` -**  Creates a function, the code is indented. Parameters (or variables needed to use the function) are optional, you can leave it blank
- **``return value `` -** Used to have the function return a value. The 'value' should be a variable or math problem that involves a variable. You can't put code after the *return statement*
- **``function_name() `` -** Calls a specified function. The output uses its own lines

### **Classes and Objects**
- **`` `` -**
- **`` `` -**
- **`` `` -**

### **Other Codes**
- **``try: indented_code except: indented_code`` -** Used to run code and when an error pops out, the code under *except* will run instead. 
- **``try: indented_code except add_error: indented_code`` -** Used to run code and when a specified error pops out, the code under *except* will run instead. 
- **``try: indented_code except add_error as variable: indented_code`` -** Used to run code and when a specified error pops out, the code under *except* will run instead and the error will be placed into the new variable. 
- **``open("file", "r||w||a||r+")`` -** Used to open a file and perform a certain action. (r = read, w = write, a = append, r+ = read and write)
- **``variable.readable()`` -** Used to check if a file is readable or not: it outputs a boolean value
- **``variable.read()`` -** Used to read a file
- **``variable.readline()`` -** Used to read the first line of a file or next lines if this code was used before on the same file
- **``variable.readlines()`` -** Used to read all lines in a file and put them into an array
- **``variable.write()`` -** Used to write in a open file
- **``variable.close()`` -** Used to close the file that was opened


## **Additional Information For Python**
- Python website where you can download Python https://www.python.org/
- Dedicated Python IDE https://www.jetbrains.com/pycharm/ (Note that you don't need to restrict yourself to this, you can use other stuff like notepad, vim, nano, neovim, vscodium, vscode, emacs, or any other text editor/IDE)
- String codes can be used in conjunction with each other. In other words, you can use multiple of them in the same print statement line. 
- By adding [number] to the right of a string variable name or array name, you can obtain a specific character or element which matches the number/index position
- You can put tupples inside of arrays and the other way around too
- You can find a list of all the standard Python modules via this link https://docs.python.org/3/py-modindex.html
-->
## **Learning Resources**
- FCC Python Course for Beginners (video) https://www.youtube.com/watch?v=rfscVS0vtbw
- FCC Python Intermediate Course (video) https://www.youtube.com/watch?v=HGOBQPFzWKo
- FCC Python Full University Course (video) https://www.youtube.com/watch?v=8DvywoWv6fI
- FCC Automate with Python for Beginners (video) https://www.youtube.com/watch?v=PXMJ6FS7llk
- FCC 12 Beginner Python Projects Crash Course (video) https://www.youtube.com/watch?v=8ext9G7xspg
- FCC Tkinter Course - Creating a Graphic User Interface in Python (video) https://www.youtube.com/watch?v=YXPyB4XeYLA
- Tech With Tim 3 Mini Python Projects for intermediates (video) https://www.youtube.com/watch?v=txKBWtvV99Y
- Tech With Tim 5 Mini Python Projects for beginners (video) https://www.youtube.com/watch?v=DLn3jOsNRVE
- Tech With Tim Creating a Full Website with Python (video) https://www.youtube.com/watch?v=dam0GPOAvVI
- Tech With Tim Creating an Online Game with Python Livestream (video) https://www.youtube.com/watch?v=wDIQ17T3sRk
- Backend development with Django (video) https://www.youtube.com/watch?v=sm1mokevMWk
- Backend Development with FastAPI (website) https://fastapi.tiangolo.com/ 
- Databases with python (mongoDB) (website) https://www.w3schools.com/python/python_mongodb_getstarted.asp
- Data Science - Basics (video) https://www.youtube.com/watch?v=JL_grPUnXzY&list=PLeo1K3hjS3us_ELKYSj_Fth2tIEkdKXvV
- Data Science - Machine Learning (video)  https://www.youtube.com/watch?v=gmvvaobm7eQ&list=PLeo1K3hjS3uvCeTYTeyfe0-rN5r8zn9rw
- Data Science - Deep Learning (video) https://www.youtube.com/watch?v=Mubj_fqiAv8&list=PLeo1K3hjS3uu7CxAacxVndI4bE_o3BDtO
- Speedrun Python Course (video) https://www.youtube.com/watch?v=VchuKL44s6E
- Python Documentation (website) https://www.w3schools.com/python/default.asp
- Advance Python Concepts (video) https://www.youtube.com/watch?v=p15xzjzR9j0
- Expert Python Tutorial (playlist) https://www.youtube.com/watch?v=mclfteWlT2Q&list=PLzMcBGfZo4-kwmIcMDdXSuy_wSqtU-xDP 


