### Hello World !

**"Hello, world!"**, I still remember this classic example, often used as the very first line of code when learning any new programming language.
Honestly, I’m not sure why this specific example is the one that's repeated across almost every language, but it has somehow become a universal tradition in programming.

I think it’s like saying: “Hi! I’m ready to code!”

```
print("Hello","World!")
```
The Result is: 

```
Hello world!
```

So now you've stepped into the world of Python, hello from the Python world!</br>
As you can see, the print statement is simple and straightforward.
Unlike in C++, where you need to include headers like *`#include <iostream>`* and write multiple lines just to print a message, in Python one line. That's it.

You can visit [w3schools](https://www.w3schools.com/python/python_syntax.asp) to learn more about Python syntax, how to write code, and how execution works.
It’s a beginner-friendly website with interactive examples and simple explanations.

---
### Comments in python code:
In Python and in any programming language, comments are extremely important to include within your code.</br>
Even though writing comments can sometimes feel frustrating or tedious :disappointed:, they become essential when someone else needs to read, understand, or continue your work.</br>
Well written comments help explain your code flow, purpose, and logic, making your code much easier to maintain and collaborate on.</br>

- Comments can be added as single line using `#` as following:

```
# My comment
# This code is printing etc.
# My name is mymonah 
```
- For longer comments that span multiple lines in Python, you can use triple double quotes `"""` or triple single quotes `'''` as following:

```
"""
This is a multi-line comment.
It explains what the code below does.
You can use triple quotes like this.
"""
```

--- 
### Variables:
One of the most basic and important topics in Python (and in most programming languages) is variables.</br>

*Now, what comes to mind when we say the word "variable"?*

For me, I think of it like this:

A **variable** is like a reserved space in your computer’s memory, used to store a value that you might need to use or change later.

It’s as if the computer saves a spot and puts a label on it, saying, “Hey, here’s a value you can come back to!”


Variables in Python can store different types of data, such as **strings**, **integers**, and **floats**. Unlike some other programming languages, Python has no specific command to declare a variable. You simply assign a value to a name, and Python figures out the type automatically.

```
x = 4              # x is an integer
y ="Mymonah"       # y is a string, 'Mymonah' is also a string, you can use double or single quote
Y = 2.90           # Y is a float, pyhton is case sensitive, so y not equal Y
```
You can check the type of any variable in Python using the built-in `type()` function.

```
x = 10
print(type(x))  # Output: <class 'int'>

name = "Mymonah"
print(type(name))  # Output: <class 'str'>
```

#### Castings:

The last concept related to variables is called **"casting"**, which means changing the data type of a variable.
For example, if you define x as an integer, you can later convert (or cast) it to a string, like this:

```
x = 5             # x is an integer
x = str(x)        # now x is a string
```
Examples:

```
x = str(10)       # Converts the integer 10 to a string '10'
x = float(10)     # Converts the integer 10 to a float 10.0
x = int('10')     # Converts the string '10' to an integer 10
x = int('A')      # Error! You can convert strings to integers only if the string contains numeric characters (like '123'), not letters or symbols.

```
#### CRUD:
CRUD stands for the four basic operations you can perform on data:
- **C** => Create
- **R** => Read
- **U** => Update
- **D** => Delete

This simple concept can be applied to basic variables, as shown in the following table:

|   |   |   |
|---|---|---|
|**Operation**|**Description**|**Example**|
|Create|Define a variable|`x = 10`|
|Read|Access its value|`print(x)`|
|Update|Change its value|`x = 20`|
|Delete|Remove the variable|`del x`|
