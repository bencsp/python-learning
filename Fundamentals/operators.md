# 04 -- Opeartors in Python
## Concept
Operators are special symbols used to perform operations on values and variables.

Python provides different types of operators for calculations, comparisons, and logical operations.

## Types of Operators
|Types|Purpose|
|---|---|
|Arithmetic|Mathematical calculations|
|Comparison|Compare values|
|Logical|Combine conditions|

## Arithmetic Operators
Arithmetic operators are used for mathematical calculations.
|Operator|Description|Example|
|---|---|---|
|+|Addition|5 + 3|
|-|Subtraction|5 - 3|
|*|Multiplication|5 * 3|
|/|Division|5 / 3|
|//|Floor Division|5 // 3|
|%|Modulus|5 % 3|
|**|Exponent|5 ** 3|

### Example
``` python
x = 10
y = 3

print(x + y)
print(x - y)
print(x * y)
print(x / y)
```

Output:
``` python
13
7
30
3.333333
```

## Floor Division
Floor division removes the decimal part.
``` python
print(10 // 3)
```

Output:
``` python
3
```
m
## Modulus
Returns the remainder after division.
``` python
print(10 % 3)
```

Output:
``` python
1
```
Because:
``` text
10 % 3 = 3 remainder 1
```

## Exponent
Raises a number to a power.
``` python
print(2 ** 3)
```

Output:
``` python
8
```
Because:
``` text
2 x 2 x 2 = 8
```

## Comparison Operators
Comparison operators compare two values.

The result is always a boolean value:
``` python
True
False
```

|Operator|Description|
|---|---|
|==|Equal to|
|!=|Not equal to|
|>|Greater than|
|<|Less than|
|>=|Greater than or equal to|
|<=|Less than or equal to|

### Example
``` python
print(10 == 10)
print(10 != 5)
print(10 > 5)
print(10 < 5)
```

Output:
``` python
True
True
True
False
```

## Common Mistake
Many beginners confuse:
``` python
=
```
and
``` python
==
```

So, what is the difference?
### Assignment
``` python
age = 18
```
Assigns a value to a variable.

### Comparison
``` python
age == 18
```
Checks whether the value is equal to 18.

## Logical Operators
Logical operators are used to combine multiple conditions.
|Operator|Description|
|---|---|
|and|Both conditions must be True|
|or|At least one condition must be True|
|not|Reverses a boolean value|

## AND
``` python
print(True and True)
print(True and False)
```
Output:
``` python
True
False
```
## OR
``` python
print(True or False)
```

Output:
``` python
True
```

## NOT
``` python
print(not True)
```

Output:
``` python
False
```

## Assignment Operators
Assignment operators are used to assign and update values.
|Operator|Example|Equivalent to|
|---|---|---|
|=|x = 5|Assign a value|
|+=|x += 3|x = x + 3|
|-=|x -= 3|x = x - 3|
|*=|x *= 3|x = x * 3|
|/=|x /= 3|x = x / 3|

### Examples
#### Addition Assignment
``` python
score = 100
score += 50 # Equivalent to score = score + 50
print(score)
```

Output:
``` python
150
```
#### Subtraction Assignment
``` python
coins = 20
coin -= 5

print(coins)
```

Output:
``` python
15
```

#### Multiplication Assignment
``` python
value = 10
value *= 2

print(value)
```

Output:
``` python
20
```

#### Division Assignment
``` python
money = 100
money /= 4

print(money)
```

Output:
``` python
25.0
```

## Another Example
Imagine you're building a shopping application.
``` python
price = 15
quantity = 3

total = price * quantity

print(total)
```

Output:
``` python
45
```

The multiplication operator can be used to calculate the total cos of multiple items.

## Notes
Python operators allow you to:
- Perform calculations
- Compare values
- Combine conditions
- Update values efficiently
