
## f-string
**f-string** or (**formatted string literal**) lets you easily embed **variables** or **expressions** directly inside a string using curly braces `{}` without needing extra steps.

- Without using f-string:
```
Name = 'ahmad'
Age = '33'
print("my name is", Name, "and my age is",Age)
```
The result will be:
```
my name is ahmad and my age is 33
```
- Now with using f-string:
```
Name = 'ahmad'
Age = '33'
print(f"my name is {Name} and my age is {Age}")
```
The result will be:
```
my name is ahmad and my age is 33
```
### What does .1f, .2f, etc. mean?
These are format specifiers used in f-strings to control how many decimal places a floating-point number should have.
- `:.1f` → 1 decimal place
- `:.2f` → 2 decimal places
- `:.3f` → 3 decimal places

```
temperature = 23.5647

# {temperature:.1f} formats the float to one decimal place.
print(f"The current temperature is {temperature:.1f}°C")

# {temperature:.2f} formats the float to two decimal places.
print(f"The current temperature is {temperature:.2f}°C")

# {temperature:.3f} formats the float to three decimal places.
print(f"The current temperature is {temperature:.3f}°C")

```
The Result: 
```
The current temperature is 23.6°C
The current temperature is 23.56°C
The current temperature is 23.565°C
```
