# 01 -- Variables in Python
## What is variable?
A variable is a container used to store data.

In Python, you don't need to declare the type explicitly.

### example
``` python
name = "Chris" #name stores text (string = data type for text)
age = 18 #age stores a number (integer = data type for number)
```

## How variables work
Variables store values that can be used later in program.
``` python
x = 10 #this is variable
y = 5
result = x + y

print(result) #output
```

## Rules for variables

valid

``` python
usrr_name = "throne"
age1 = 25
```
invalid
``` python
1name = "throne" #cannot start with number
user-name = alice #no hyphens allowed
```

## Case Sensitivity (IMPORTANT!)

Python is case-sensitivity, which means:
'name', 'Name', and 'NAME' are treated as different variables.

### example
``` python
name = "throne"
Name = "Alice"
NAME = "Bob"
print(name)
print(Name)
print(NAME)
```
output:
``` python
throne
Alice
Bob
```

## Why This matters?
Because Python treats them as different variables, this can easily cause bugs if you're not careful.

Example mistake:
``` python
userName = "Chris"
username = "Alice"

print(userName) # different variable!
```

## Best
Use one consistent style, 'snake_case' (recommended in python)

``` python
user_name = "Chris"
age_value = 18
```
