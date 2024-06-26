[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/WfNmjXUk)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15315193&assignment_repo_type=AssignmentRepo)
# SE-Assignment-6
 Assignment: Introduction to Python
Instructions:
Answer the following questions based on your understanding of Python programming. Provide detailed explanations and examples where appropriate.

 Questions:

1. Python Basics:
   - What is Python, and what are some of its key features that make it popular among developers? Provide examples of use cases where Python is particularly effective.

   Python is an intergrated, object-oriented, high level programming language that can be used to create applications for different uses.
   Some of the key features include:
          .It's easy to use.
          .it has a rich ecosystem of libraries
          .it's easy to learn
          .it's free
          it's simple and readable
          it has built-in data structures

   Python is particularly effective to build websites and software, automate tasks and conduct data analysis.

2. Installing Python:
   - Describe the steps to install Python on your operating system (Windows, macOS, or Linux). Include how to verify the installation and set up a virtual environment.

   Installing Python on Windows Operating system

   visit https://www.python.org/downloads/
   download the latest python release, currently python 3.12.4
   ![alt text](<python org.PNG>)
   click download
   once the download is complete, double click on the downloaded file.
   click on the Add Path check box
   select install now 
   set up will begin

   To verify the installation, go to command prompt. type the command python -version

   
   
3. Python Syntax and Semantics:
   - Write a simple Python program that prints "Hello, World!" to the console. Explain the basic syntax elements used in the program.
 
      print("Hello, world!")
      Basic syntax elements used in python inculde:
         .comments- start with #.They are ignored by python interpreter
      
         .Data types- Python supports various data types including integers, float,string,boolean,lists, turples
         .functions - defined by the def keyword 

4. Data Types and Variables:
   - List and describe the basic data types in Python. Write a short script that demonstrates how to create and use variables of different data types.

   Data types:
     Text type: str. (surrounded by either 'single' or "double" qoutation marks)
                      x = str "my assignment" 

     Numeric types:  int  (Represent a whole number) 
                      x = int(50)

                     float     x =float(30.4)

      Sequence type: list (used to store multiple items in a single variable)
                     x =list [ 1,2,3,4,]    

                     turple ( A list which is ordered and unchangeable)   
                     x = turple (monday, tuesday, wednesday,thursday,friday)

      Dictionary :    dict     x = { "name": "loice", "age":21 }


5. Control Structures:
   - Explain the use of conditional statements and loops in Python. Provide examples of an `if-else` statement and a `for` loop.

   A 'for'loop is used to execute a set of statements, once for each item in a sequence. 
   example  -  for x in "apple"
               print(x) 
                 a
                 p
                 p
                 l
                 e
   if else 
   example x = 50
           y = 43
           if y > x:
           print("y is greater than x") 
           else:
           print("y is not greater than x") 




6. Functions in Python:
   - What are functions in Python, and why are they useful? Write a Python function that takes two arguments and returns their sum. Include an example of how to call this function.

   A function in Python is a block of code which only runs when it is called to perform a task or a set of tasks. Functions are  defined by the def keyword. Functions are important because they play a crucial role in structuring programs, promoting code reuse, and enhance readability and maintainability.
   
   def sum_two_numbers(x,y):
      return x+y

   result = sum_two_numbers(5,7)
   print result
    output will be 12

7. Lists and Dictionaries:
   - Describe the differences between lists and dictionaries in Python. Write a script that creates a list of numbers and a dictionary with some key-value pairs, then demonstrates basic operations on bo  

   Differences between lists and didtionaries
   LISTS
    - are ordered collections
    - are accessed by index
    - are typically used for ordered collectionsof items where the position of each matters

   Dictionaries 
   - are accessed by key
   - do not guarantee any specific order
   - are used when you need to store data as key-value pairs and need fast look up by keys  
   
   Initialization
    LIsts                my_list = [5,6,7,8,9]
                         empty_list = []

    Dict          my_dict ={'name': 'joy', 'age':'54', 'city':'lydenburg' }
                  empty_dict = {}

8. Exception Handling:
   - What is exception handling in Python? Provide an example of how to use `try`, `except`, and `finally` blocks to handle errors in a Python script.

Exception handling is a mechanism that allows you to hanlde errors in a controlled manner, preventing abrupt termination of your program.
Example
 try:
   print (hello)
 except:
   print("an exception occurred")
 finally:
   print("the 'try except'is finished")
    
9. Modules and Packages:
   - Explain the concepts of modules and packages in Python. How can you import and use a module in your script? Provide an example using the `math` module.

  Modules and packages are mechanisms for organizing and structuring code into reusable units.modules are files containing Python definitions, functions, classes, and variables.
  A package is a way of structuring modules hierachically.
  To import a module into your Python scripts, you can use the import statement, then you can use its functions,classes or variables

10. File I/O:
    - How do you read from and write to files in Python? Write a script that reads the content of a file and prints it to the console, and another script that writes a list of strings to a file.

    To read from a file, open it using the open() function.The function opens two arguments, the file path and the mode( 'r'for reading)

    with open ( file_path. 'r')as file:
       content = file.read()
       print(content)

    To write to a file, open it with 'w'mode. Use the write() method to write data to a file

# Submission Guidelines:
- Your answers should be well-structured, concise, and to the point.
- Provide code snippets or complete scripts where applicable.
- Cite any references or sources you use in your answers.
- Submit your completed assignment by [due date].


