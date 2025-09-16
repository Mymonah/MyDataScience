### input() function 
The built-in `input()` function in Python is used to get input from the user during program execution.
It pauses the program and waits for the user to type something, **<u>then returns the input as a string**.</br>

**It's very important to keep in mind that the `input()` function always returns a string, even if the user types a number**.

So, if you're asking the user to enter a number and you want to perform arithmetic operations, you need to convert the input to an appropriate type usually int or float as we learned in [casting](https://github.com/Mymonah/MyDataScience/blob/main/MyPython/MyPython-2.md#casting).

The syntax is `input(prompt)`, prompt: is a string, representing a default message before the input.

```
x = input('Enter your name:')
```
When you run a program that uses the `input()` function, the execution pauses and waits for the user to enter a value and hit **Enter**, then the program continues to the next line of code as shown below:
</br></br>
<img src="/Assets/Python3.png" width="60%" align="center" alt="Python3.png">
</br></br>

### Arithmetic Operations:
It includes all basic arithmetic operations that can be performed on variables, such as addition, subtraction, multiplication, division, and more.
|   |   |   |   |   |
|---|---|---|---|---|
|**Operator**|**Name**|**Example**|**Result**|**Description**|
|+|Addition|10 + 3|13|Adds two numbers|
|-|Subtraction|10 - 3|7|Subtracts the second number from the first|
|*|Multiplication|10 * 3|30|Multiplies two numbers|
|/|Division|10 / 3|3.333...|Divides the first number by the second|
|//|Floor Division|10 // 3|3|Divides and rounds down to nearest integer|
|%|Modulus (Remainder)|10 % 3|1|Returns the remainder after division|
|**|Exponentiation (power)|10 ** 3|1000|Raises the first number to the power of the second|

We can also use varibles combined with arithmetic operations as following:
```
x + = 2      # x = x + 2
x - = 2      # x = x - 2
x * = 2      # x = x * 2
x / = 2      # x = x / 2
x // = 2     # x = x // 2
x % = 2      # x = x % 2
x ** = 2     # x = x ** 2

```


### Comparison Operations:
These are used to compare values, the result is always True or False.
|   |   |   |
|---|---|---|
|**Operator**|**Meaning**|**Example**|
|==|Equal to|3 == 3 → True|
|!=|Not equal to|5 != 3 → True|
|>|Greater than|7 > 3 → True|
|<|Less than|3 < 7 → True|
|>=|Greater or equal|3 >= 3 → True|
|<=|Less or equal|3 <= 6 → True|

### Logical Operations:
These are used to combine conditional statements as shown in the **Truth Table** below:

|   |   |   |   |   |   |
|---|---|---|---|---|---|
|**A**|**B**|**A AND B**|**A OR B**|**NOT A**|**NOT B**|
|True|True|True|True|False|False|
|True|False|False|True|False|True|
|False|True|False|True|True|False|
|False|False|False|False|True|True|

### Order of Operations:
In Python, the order of operations tells us which part of an expression gets calculated first. Python follows a set of rules called operator precedence to decide this.

Here’s the order, from highest to lowest:

1. Parentheses () – Do these first.
2. Exponents ** – Powers like 2**3.
3. Multiplication, division, floor division, and modulus * / // %
4. Addition and subtraction + -
5. Comparisons == != > >= < <=
6. Logical not
7. Logical and
8. Logical or

>> If two operations have the same priority, Python usually works left to right except for powers (**), which go right to left.

The left-to-right rule is generally understood, but exponentiation can be a bit confusing. So, it will be explained using an [example from Stack Overflow](https://stackoverflow.com/questions/47429513/why-is-exponentiation-applied-right-to-left).

<img src="/Assets/Python4.png" width="70%" align="center" alt="Python4.png">
