### input() function 
The built-in `input()` function in Python is used to get input from the user during program execution.
It pauses the program and waits for the user to type something, **<u>then returns the input as a string**.</br>

It's very important to keep in mind that the `input()` function always returns a string, even if the user types a number.

So, if you're asking the user to enter a number and you want to perform arithmetic operations, you need to convert the input to an appropriate type usually int or float as we learned in [castings](https://github.com/Mymonah/MyDataScience/blob/main/MyPython/MyPython-2.md#castings).

The syntax is `input(prompt)`, prompt: is a string, representing a default message before the input.

```
x = input('Enter your name:')
```
When you run a program that uses the `input()` function, the execution pauses and waits for the user to enter a value and hit **Enter**, then the program continues to the next line of code as shown below:
</br></br>
<img src="/Assets/Python3.png" width="60%" align="center" alt="Python3.png">
</br></br>
