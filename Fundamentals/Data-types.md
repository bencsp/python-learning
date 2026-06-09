# 02 -- Data types in Python
## what is Data types?
A data type defines the kind of value stored in a variable.

different data types are used for different purposes, such as storing text, numbers, or logical values.

## Common Data types
int = integer number, ex: 10, -5, 100
float = decimal number, ex: 3.14, 0.5
str = text (string), ex: "hello", 'python'
bool = boolean value, ex: True, False

### Example
``` python
age = 18 # int
height = 170.5 # float
name = "Chris" # str
is_student = True # bool

print(age)
print(height)
print(name)
print(is_student)
```

### Single vs Double quotes
Python treats single quotes and double quotes the same way.

``` python
name = "Chris"
language = 'python'
```
Both values are strings ('str').

Use whichever makes your code easier to read, but try to stay consistent throughout your project.

## Checking Data types
use the 'type()' function to check the type of a value.

``` python
age = 18

print(type(age))
```

output:

``` python
<class 'int'>
```

### Example
``` python
age = 18
height = 170.5
name = "Chris"
is_student = True

print(type(age))
print(type(height))
print(type(name))
print(type(is_student))
```

output:
``` python
<class 'int'>
<class 'float'>
<class 'str'>
<class 'bool'>
```

## Strings
Strings are used to store text.
``` python
name = "chris"
language = "python"
```
Strings must be enclosed in quotation marks.

## integers
Integers are whole numbers without decimal points.

``` python
age = 18
temperature = -5
```
## Floats
Floats are numbers that contain decimal points.

``` python
price = 9.99
pi = 3.14
```

## Booleans
Booleans represent logical values.
There are only two boolean values:

### Example
``` python
is_logged_in = True
has_permission = False
```

## Common Mistakes
### Numbers inside quotes become strings
``` python
age = "18"
```

This is a string, not an integer.

### Important!
The value and the data type are not the same thing.
``` python
18 # int
"18" # str
18.0 # float
```
These values may look similar, but python treats them as different data types.

### Boolean values are case-sensitive
correct:
``` python
True
False
```

incorrect:
``` python
ture
false
```
python will raise an error.

## Notes
Every value in python has a data type.
The most common data types are:
- int
- float
- str
- bool
use 'type()' to check a value's data type. 