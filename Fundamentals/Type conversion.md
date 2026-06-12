# 03 -- Type Conversion in python
##  Concept
Type conversion is the process of changing a value from one data type to another.

Python provides built-in functions to perform these conversions.

## Common Conversion Function
| Function | Converts to |
|---|---|
|'int()'| Integer |
|'float()'|Float |
|'str()'| String|
|'bool()'| Boolean|

## String to Integer

``` python
age = "18"

age = int(age)

print(age)
print(type(age))
```
Output:
``` python
18
<class 'int'>
```

## Integer to String
``` python
age = 18

age = str(age)

print(age)
print(type(age))
```
Output:
``` python
18
<class 'str'>
```

## Integer to Float
``` python
number = 10

 number = float(number)

 print(number)
 print(type(number))
 ```
Output:
``` python
10
<class'float'>
```

## Float to Integer
``` python
price = 9.99

price =int(price)

print(price)
```

Output:
``` python
9
```

### Note
'int()' removes the decimal part instead of rounding.

## Common Mistakes
### Invalid Conversion
``` python
number = "hello"

number = int(number)

print(number)
```
Because '"hello"' is not a valid number.

## Why Type Conversion Matters
One of the most common uses of type conversion is when working with user input.

Example:

``` python
age = int(input("Enter your age: "))
```

The 'input()' function returns a string.

so 'int()' is used to convert the value into an integer before performing calculations.

## Notes
Type conversion is commonly used when:
- Working with user input
- Performing calculations
- Processing data from files or APIs
- Converting values between different formats
