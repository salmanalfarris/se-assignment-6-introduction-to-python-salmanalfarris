[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/WfNmjXUk)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15306726&assignment_repo_type=AssignmentRepo)
# SE-Assignment-6
 Assignment: Introduction to Python
Instructions:
Answer the following questions based on your understanding of Python programming. Provide detailed explanations and examples where appropriate.

 Questions:

1. Python Basics:
   - What is Python, and what are some of its key features that make it popular among developers? Provide examples of use cases where Python is particularly effective.

   -python is a high-level, intergrated programming language created by Guido Van Rossum and first released in 1991.
   Its features includes
   -Easy to learn and use.
   -versatile and powerful.
   -extensive libraries and framework.
   -community support.
   It is particularly effective and widely used in web development.
   Source: PLP python slides by Chakin.

2. Installing Python:
   - Describe the steps to install Python on your operating system (Windows, macOS, or Linux). Include how to verify the installation and set up a virtual environment.

   step 1: select the python version to download, python3.8.6(64-bit) set up is prefered.
   step 2: click on install now and double-click to executable file.
   step 3: installation process,try to run python on the command prompt.
   -once downloaded in the download section, click on the downloaded file then select bin option and copy the address.
   -open environment variables click and click path then create new path then paste the bin copied link of the downloaded python file,excute and finish.
   -Source ;Mr Dave lecturer class on python installation recap.

3. Python Syntax and Semantics:
   - Write a simple Python program that prints "Hello, World!" to the console. Explain the basic syntax elements used in the program.

   ![alt text](image.png)
   -it can use element like "Hello, World" directly in the command line. 

4. Data Types and Variables:
   - List and describe the basic data types in Python. Write a short script that demonstrates how to create and use variables of different data types.

   ![alt text](image-1.png)


5. Control Structures:
   - Explain the use of conditional statements and loops in Python. Provide examples of an `if-else` statement and a `for` loop.

   -conditional statement is used to provide a choice for the control flow based on a condition.
   -loops can be used to iterate over iterators and a range, i.e print("List Iteration")
   Source: W3Schools.


6. Functions in Python:
   - What are functions in Python, and why are they useful? Write a Python function that takes two arguments and returns their sum. Include an example of how to call this function.

   -functions are block of codes which only runs when it is called, i.e def my_function():
   print("Hello from a function")
   Source: W3Schools.

7. Lists and Dictionaries:
   - Describe the differences between lists and dictionaries in Python. Write a script that creates a list of numbers and a dictionary with some key-value pairs, then demonstrates basic operations on both.

   -lists are linear in nature whereas dictionaries store data in key-value pair.
   -lists are such as;
   List = ["Greeks", "For", "Greeks"]
   print("List containing multiple values: ")
   -dictionaries are such as;
   Dict = {1: "Greeks", 2: "For", 3: "Greeks: "}
   prnit(Dict)
   :Soure;greeksforgreeks.org

8. Exception Handling:
   - What is exception handling in Python? Provide an example of how to use `try`, `except`, and `finally` blocks to handle errors in a Python script.

-Exception handling is a fundemental concept in python that allows a developer to anticipate and manage errors during the execution of a program; i.e try:
#code that might raise an exception
result =10 / 0
except ZeroDivisionError:
print("Caught a division by zero!")
-Source;diveintopython.org

9. Modules and Packages:
   - Explain the concepts of modules and packages in Python. How can you import and use a module in your script? Provide an example using the `math` module.

   -consider modules to be the same as a code library, i.e def greeting(name):
   print(Hello, " + name).
   -packages helps avoid collusions between modules names; i.e mod1.py
   def foo():
   print( "[mod1] foo()")
   class Foo:
   pass
   -Source: daveinpython and w3school.

10. File I/O:
    - How do you read from and write to files in Python? Write a script that reads the content of a file and prints it to the console, and another script that writes a list of strings to a file.

i.e OPEN(1,FILE=TRIM(filenameout),RECL=2000)
WRITE(1,*) "tAge/yr (u-r)
(u-z) fGas Mstars/MstarsOld"
CLOSE(1) is an example of reading files in python.
# Submission Guidelines:
- Your answers should be well-structured, concise, and to the point.
- Provide code snippets or complete scripts where applicable.
- Cite any references or sources you use in your answers.
- Submit your completed assignment by [due date].


