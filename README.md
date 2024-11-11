https://www.youtube.com/watch?v=LHRn9NMNBCQ&list=PLbvhRHYrmshRFWUrS6x2LgeE4CMte_m5K

# **PYTHON LEARNING (BEGINNER LEVEL)** [⏫](https://www.notion.so/Python-1356bec38d3e803680dac1b551a9cc01?pvs=21)

INTRODUCTION

Pyton is a high-level programming language for general-purpose programming. It is an open source, intepreted, objected-oriented programming language.

Python was created by a Dutch programmer, Guido van Rossum

# VARIABLES [⏫](https://www.notion.so/Python-1356bec38d3e803680dac1b551a9cc01?pvs=21)

## 🔢 Number (Biến dạng số) [⏫](https://www.notion.so/Python-1356bec38d3e803680dac1b551a9cc01?pvs=21)

Variables are containers that hold data values. They are used to store, manipulate, and display information within a program.

In short a variables is like a memory unit that we can access by typing the name of the variable.

Each variable has a unique name anf a value that van be of different types. Python is capable of automatically detecing the variable type, which makes coding more efficient.

To initializw a variable, we use the following format:

```python
variable_name = value
```

Let’s take a look at the different types of numbers

```python
#Whole number, such as 1 or -2
int
#Real number, such as 1.32 or 0.98
float 
```

```python
# Type your code below
var = ?

# Don't change the line below
print(f'var = {var}')
```

## 🆎 String (Biến dạng chuỗi) [⏫](https://www.notion.so/Python-1356bec38d3e803680dac1b551a9cc01?pvs=21)

A char is a single character (For example:  1, 5, 6, %, …)

The str (string) type is a special type that consists of multiple chars.

To initialize a string value in a variable, enclose it within single or double quotation marks:

```python
s1 = 'This is a string'
s2 = "This is also a string"

```

• ***QUIZ***

Q: Which of the following is used to initialize a string in Python?

A: Single or double quotation marks

Q: What does the char type represent?

A: A single character

```python
# Type your code below
coddy = "I am learning to code with Coddy!"

# Don't change the line below
print(f'coddy = "{coddy}"')
```

## ♾️ Boolean (Biến dang Boolean) [⏫](https://www.notion.so/Python-1356bec38d3e803680dac1b551a9cc01?pvs=21)

A bool (Boolean) type has only 2 possible values: True or False

To assign a bool value to a variable,

```python
variable_true = True
variable_false = False
```

In the above example, 2 variables named “variable_true” & ”variables_false” are initialized, with the values “True” & “False” respectively.

> ***Booleans are the building blocks for creating logic in the programs we write. We have a whole chapter about logic and conditions.***
> 

• ***QUIZ***

Q: What is the correct way to assign a Boolean value of True to a variable named foo in Python?

A: foo = True

Q: Which of the following values is NOT a Boolean type in Python?

A: ‘False’

Q: What is the primary utility of Booleans in programming?

A: Creating logic and conditions in programs

```python
Declare a variable named boolean and assign it the value True.
# Type your code below
boolean = True

# Don't change the line below
print(f'boolean = {boolean}')

#Outcome
boolean = True
```

## ⛔ RECAP CHALLENGE #1 [⏫](https://www.notion.so/Python-1356bec38d3e803680dac1b551a9cc01?pvs=21)

Write code that initializes the following variables:

- `k` with the value `88`
- `PI` with the value `3.14`
- `name` with the value `"bob"`

```python

# Type your code below
k = int(88)
PI = float(3.14)
name = "bob"

# Don't change the line below
print(f"k = {k}")
print(f"PI = {PI}")
print(f"name = {name}")
```

# OPERATORS [⏫](https://www.notion.so/Python-1356bec38d3e803680dac1b551a9cc01?pvs=21)

## ARITHEMETIC OPERATORS [⏫](https://www.notion.so/Python-1356bec38d3e803680dac1b551a9cc01?pvs=21)

Operators used to perform operations on values.

Frist we will discuss the most basic arithmetic operators, they may be familiar from math classes

| ***Operator*** | ***Operation*** | ***Example*** |
| --- | --- | --- |
| + | Addition | 3 + 2 = 5 |
| - | Subtraction | 3 - 2 = 1 |
| * | Multiplication | 3 * 2 = 6 |
| / | Division | 4 / 2 = 2 |
| % | Modulus (Remainder after division) | 3 % 2 = 1 |

> ***Modulus** operation provides the remainder that results from dividing the first value by the second value.*
> 

For example:

14 % 4 returns 2 because 4 can be inserted into 14 three times (4*3=12) and now 14 minus 12 equals 2 (The remainder)

***• QUIZ***

<aside>
💡

Q: What is the result of operation 3*2 using arithmetic operators described?

A: 6

</aside>

<aside>
💡

Q: What result does the modulus operator % return when applied as in 5%2

A: 1

</aside>

<aside>
💡

Q: Considering basic arithmetic operators, which operation is correctly excuted in the following Python code:

```python
a = 4
b = 2
c = a / b
```

A: Division

</aside>

***• CHALLENGE***

Write a code that initializes two variables, `a` and `b`, with the values `5.2` and `2.6` (respectively).

After that, initialize another variable `c` that will hold the result of `a / b`.

```python
# Type your code below
a = 5.2
b = 2.6
c = a/b

# Don't change the line below
print(f"a = {a}, b = {b}, c = {c}");
```

## ARITHMETIC SHORTCUTS [⏫](https://www.notion.so/Python-1356bec38d3e803680dac1b551a9cc01?pvs=21)

Python created a cool shortcut for self-arithmetic operations.

```python
# For example instead of writing
a = 5
a = a + 3 # a holds 8
# We can simplify it by writing +=
a = 5
a += 3 # a hold 8
```

The `+=` is adding to `a` **itself** the value `3`

This operation is valid for all arithmetic operations:

| ***Operator*** | ***Shortcut*** |
| --- | --- |
| + | += |
| - | -= |
| * | *= |
| / | /= |
| % | %= |

• QUIZ

<aside>
💡

Q: Which of the following shortcut operators is used to multiply a variable by itself and another given value in Python?

A: *=

</aside>

<aside>
💡

Q: What will be the value of `a` after executing these operations?

```python
a = 10
a /= 2
```

A: 5

</aside>

<aside>
💡

Q: Considering the arithmetic shortcuts in Python, which of the following is the correct way to decrement a variable `b` by `2`?

b -= 2

b =- 2

b +-= 2

b -- 2

</aside>

• CHALLENGE

You are given a code with initialization of `count`. (Don't delete this line!)

Your task is to add the following operations, **in this order**:

1. Add `4` to `count`
2. Multiply `count` by `2`
3. Subtract `1` from `count`

Use the arithmetic shortcuts to do so!

```python
# Type your code below
count = 4
count *= 2
count -= 1

# Don't change the line below
print(f"count = {count}")

# Expected Output
count = 7
```

## COMPARISON OPERATORS [⏫](https://www.notion.so/Python-1356bec38d3e803680dac1b551a9cc01?pvs=21)

Comparision operators is used to compare between two operands.

Sometimes we need to check whether an operand is bigger/smaller/... than another operand. The following table shows possible operators for comparison:

| ***Operator*** | ***Meaning*** | ***Example*** |
| --- | --- | --- |
| == | Equal | 1 == 2 return false |
| != | Not Equal | 1 != 2 return true |
| > | Greater Than | 1 > 2 return false |
| < | Lower Than | 1 < 2 return true |
| >= | Greater or Equal | 1 >= 2 return false |
| <= | Lower or Equal | 1 <= 2 return true |

The comparison operator returns `True` if the comparison is correct or `False` ****otherwise.

For example:

```c
var1 = 13
var2 = 12
var3 = var1 != var2
```

`var3` will hold `True` because `var1` and `var2` are not equal

> Remember the boolean type,  var3 is a boolean.
> 

***• QUIZ***

<aside>
💡

Q: Which comparison operator checks if the two operands are not equal?

>

<

!=

==

</aside>

<aside>
💡

Q: What will be the result of the comparison `5 >= 5`?

False

None

Error

True

</aside>

<aside>
💡

Consider the expression `7 < 10`. What is the return value of this comparison?

10

False

True

7

</aside>

***• CHALLENGE***

Write a script that initializes 2 variables `n1` and `n2` with the values `8` and `9` (accordingly).

After that initialize another variable `n3` that will hold whether `n1` is bigger than `n2`.

```python
# Type your code below
n1 = 8
n2 = 9
n3 = n1 > n2

# Don't change the line below
print(f"n1 = {n1}, n2 = {n2}, n3 = {n3}")

# Expected Output
n1 = 8, n2 = 9, n3 = False
```

## LOGICAL OPERATORS Part 1 [⏫](https://www.notion.so/Python-1356bec38d3e803680dac1b551a9cc01?pvs=21)

[Challenge.ipynb](https://prod-files-secure.s3.us-west-2.amazonaws.com/9de88d17-a27a-466e-878e-883c2a7e14ad/7fb2f7e7-0419-4aa7-ac62-fc4c1fb7ad00/Challenge.ipynb)

Logical operators are used to check combinations of comparisons that return 

**Logical operators** are used to check combinations of comparisons that return `True` or `False`.

For example the following statement contains two comparisons:

Is 5 greater than 3 **and** lesser than 6?

| Operator | Meaning | Example |
| --- | --- | --- |
| `and` | And - `True` if **all** operands are `True` | `a and b` |
| `or` | Or - `True` if **any** operand is `True` | `a or b` |
| `not` | Not - `True` if the operand is `False` | `not a` |

Let's see some examples,

5 is bigger than 3 and 1 equals 1,

```python
b1 = (5 > 3) and (1 == 1) # holds true

```

**Explanation**: All of the operands are `True`, so `b1` will hold `True` (`and` operation is `True` if both operands are `True`) .

5 is not equals 4 or five equals 2,

```python
b2 = not 5 == 4 or 5 == 2 # holds true

```

**Explanation**: The first operand (`5 != 4`) is `True` so `b2` is also `True` (`or` operation is `True` if either one of the operands is `True`)

1 is not equals 1 or false,

```python
b3 = not 1 == 1 or False # holds false

```

**Explanation**: All of the operands are `False`, so `b3` will hold `False` (`or` operation).

not (3 bigger than 4),

```python
b4 = not (3 > 4) # holds true

```

**Explanation**: The operand is `False`, so `b4` will hold `True` (`not` operation).

not (5 bigger than 10 or 5 bigger than 1),

```python
b5 = not (5 > 10 or 5 > 1) # holds false

```

**Explanation**: `5 > 10 or 5 > 1` is `True` (one of the operands is `True`), so in total `b5` is `False` (`not` operation).

• QUIZ

<aside>
💡

Q: Which logical operator is used to check if **both** operands are `True`?

or

and

not

</aside>

<aside>
💡

Q:   If one of the comparisons in an `or` operation is `True`, what is the result?

True

False

Cannot determine without the exact values

</aside>

<aside>
💡

Q:   What is the outcome of the expression `not (3 > 4)`?

False

Depends on the context

True

</aside>

• CHALLENGE

You are **given** a code, Replace the question marks of the variables `b1` and `b2` so that `b3` holds `True`.

> There are many right solutions!
> 

```python
# Type your code below
b1 = ?
b2 = ?
b3 = b1 or b2

# Don't change the line below
print(f"b3 = {b3}")

# Expected outcome
b3 = True
```

## LOGICAL OPERATORS Part 2 [⏫](https://www.notion.so/Python-1356bec38d3e803680dac1b551a9cc01?pvs=21)

Logical operators have a special table called "Truth table" that shows what the combination of logical operators returns.

Truth table for the `and` operator:

| a | b | a and b |
| --- | --- | --- |
| False | False | False |
| False | True | False |
| True | False | False |
| True | True | True |

The only way to get a `True` for the `and` operator is if both `a` and `b` are `True`

Truth table for the `or` operator:

| a | b | a or b |
| --- | --- | --- |
| False | False | False |
| False | True | True |
| True | False | True |
| True | True | True |

In this case, to get a `True` result, either `a` or `b` should be `True`.

Truth table for the `not` operator:

| a | not a |
| --- | --- |
| False | True |
| True | False |

Here the value of `a` is reversed. If `a` is `False` then `not a` is `True`

***• QUIZ***

<aside>
💡

Which of the following is correct according to the truth table for the `and` operator?

False and False results in True

True and True results in False

True and False results in True

False and True results in False

</aside>

<aside>
💡

According to the truth table for the `or` operator, what is the result of True or False?

True

Cannot be determined

False

</aside>

<aside>
💡

What does the `not` operator do to its operand's boolean value?

Changes True to False and False to True

Combines two boolean values into one

Determines if either of two boolean values is True

Determines if both boolean values are True

</aside>

***• CHALLENGE***

You are **given** a code, replace the question marks of the variables `b1` and `b2` so that `b3` evaluates to `True`.

> Note that b1 and b2 should hold numbers.
> 

```python
# Type your code below
b1 = 2
b2 = -3
b3 = not (b1 + b2) < (b1 * b2)
## Explanation
Let's break down the expression step by step:

Inner Parentheses:

b1 + b2 = 2 + (-3) = -1
b1 * b2 = 2 * (-3) = -6
Comparison:

-1 < -6 is False.
not Operator:

not False is True.
Therefore, the value of b3 is True.

In summary:

The expression inside the parentheses evaluates to -1 < -6, which is False.
The not operator flips the boolean value to True.
This is why the output of the code is b3 = True.

# Don't change the line below
print(f"b3 = {b3}")

# Expected outcome
b3 = True

```

# DECISION MAKING [⏫](https://www.notion.so/Python-1356bec38d3e803680dac1b551a9cc01?pvs=21)

## IF STATEMENT [⏫](https://www.notion.so/Python-1356bec38d3e803680dac1b551a9cc01?pvs=21)

If statements allow us to execute code with conditions.

For example, let's look at the following code:

```python
age = 20
status = "Child"
if age > 18:
    status = "Adult"
age += 1

```

The above code checks whether the `age` variable is bigger than `18`. If it is, it will set `status` to hold `"Adult"` string.

In the end, the code will increment `age` by `1` whether the age is bigger than 18 or not.

To use an `if` statement we need to add a colon `:` at the end of the if, and everything that is inside the `if` is indented with **4 spaces**:

```python
if condition:
    code
    code
    code

```

If the condition is `True`, we will enter the code block inside the if (The indented code)

***• QUIZ***

<aside>
💡

How do you correctly write an `if` statement in Python?

if condition begin

if condition:

if (condition):

if condition then:

</aside>

<aside>
💡

What happens to the `age` variable at the end of the example code?

It decreases by 1

It remains unchanged

It is reset to 0

It increases by 1

</aside>

***• CHALLENGE***

You are given a code.

The variables `a` and `b` have missing values, fill them so that the code inside the `if` statement will be executed!

**Bonus**: try to find more than one solution!

```python
a = 14
b = 12

# Don't change below this line
c = 0
if a >= b and not b < 10:
    c = 2

c += 1
print(f"c = {c}")

# Expected output
c = 3

# Explanation
Let's break down the code step-by-step:

Variable Initialization:

a = 14
b = 12
c = 0
Conditional Check:

if a >= b and not b < 10:
a >= b: This is True because 14 is greater than or equal to 12.
not b < 10: This is also True because 12 is not less than 10.
Since both conditions are True, the code inside the if block will execute.
Inside the if Block:

c = 2
After the if Block:

c += 1: This increments the value of c by 1, so c becomes 3.
Print the Result:

print(f"c = {c}"): This prints the final value of c, which is 3.
Therefore, the output of the code will be:

c = 3
```

## IF - ELSE [⏫](https://www.notion.so/Python-1356bec38d3e803680dac1b551a9cc01?pvs=21)

`if` allows us to execute (thực thi) particular code if a condition is met, but what if we want to execute something else if the condition is not met?

For that we have the `else` statement:

```python
age = 15
status = "None"
if age >= 18:
    status = "Adult"
else:
    status = "Young"

```

In the above example, `age` is smaller than `18` which means it enter the else code and `status` will hold `"Young"`.

We can even make it more profound using the `elif` statement:

```python
age = 68
status = "None"
if age < 18:
    status = "Young"
elif age >= 18 and age <= 65:
    status = "Adult"
else:
    status = "Old"

```

Here it checks whether age is smaller than 18, if not it will continue to the next condition and check whether age is between 18 and 65. If that condition is also not met it will set `status` to `"Old"`.

We can add as many `elif` statements as we want:

```python
if condition1:
    code
elif condition2:
    code
elif condition3:
    code
...

```

> Note that the code inside the if/elif/else must be indented
> 

***ª QUIZ***

<aside>
💡

What will be the value of `status` if `age` is 20 according to the provided Python code?

Young

Adult

Old

None

</aside>

***• CHALLENGE***

You are given a code which gets as input a number that indicates the wind speed and stores it in a variable named `wind`.

**Note**: we will learn in next lessons how to get input from the user, currently just don't touch the first line.

Your task is to initialize variable `status` based on the conditions:

- `"Calm"` if `wind` is smaller than `8`,
- `"Breeze"` if `wind` is between `8` and `31` (including 8 and 31).
- `"Gale"` if `wind` is between `32` and `63` (including 32 and 63)
- `"Storm"` otherwise

> Check the test cases to see all the inputs and the expected outputs
> 

```python
wind = int(input()) # Don't change this line
status = "unset"
# Type your code below

# Don't change the line below
print(f"status = {status}")

# Expected output
5 16 49 107
```

## RECAP CHALLENGE #1 [⏫](https://www.notion.so/Python-1356bec38d3e803680dac1b551a9cc01?pvs=21)

You are given a code which gets as input two numbers `n1` and `n2` and a character `op`.

**Note**: we will learn in next lessons how to get input from the user, currently just don't touch the three first lines.

The possible values for `op` are `'+'`, `'-'`, `'/'` and `'*'`

Your task is to set the variable `result` based on the conditions:

- if `op` is `'+'`, set `result` with `n1 + n2`.
- if `op` is `'-'`, set `result` with `n1 - n2`.
- if `op` is `'/'`, set `result` with `n1 / n2`.
- if `op` is `'*'`, set `result` with `n1 * n2`.

```python
n1 = int(input()) # Don't change this line
n2 = int(input()) # Don't change this line
op = input() # Don't change this line
result = 0
if op = '+':
    result = n1 + n2
elif op = '-':
    result = n1 - n2
elif op = '/':
    result = n1 / n2
elif op = '*':
    result = n1 * n2
else:
    result = 0
# Don't change the line below
print(f"result = {result}")
```

# BASIC IO [⏫](https://www.notion.so/Python-1356bec38d3e803680dac1b551a9cc01?pvs=21)

## OUTPUT [⏫](https://www.notion.so/Python-1356bec38d3e803680dac1b551a9cc01?pvs=21)

We have already seen how to output something but let's recap.

> In programming it's often called "printing" to output something.
> 

In Python to print something to the screen we use `print()`

For example,

```python
print("Hello")

```

The above example prints `"Hello"` to screen.

**Recall** that you must enclose what you want to print with `""` or with `''`, it is a **string** inside the `print()`.

***ª QUIZ***

<aside>
💡

In the context of Python, what does it mean to print something?

To send something to a printer

To save something to a file

To display something on screen

To store something in memory

</aside>

<aside>
💡

Which of the following is a correct way to print a string in Python?

echo "Good evening!"

print('Good afternoon!'

document.write('Good night!')

print("Good morning!")

</aside>

***• CHALLENGE***

Write a program that prints `"I love Python programming"`.

```python
print("I love Python programming")
```

## OUTPUT WITH VARIABLES [⏫](https://www.notion.so/Python-1356bec38d3e803680dac1b551a9cc01?pvs=21)

As of now we learnd how to print simple strings, but sometimes we need to insert variables values into the string.

For example:

```python
age = 10
print("His age is: age")

```

This will print `"His age is: age"` instead of `"His age is: 10"`

to make it work we will use the `f` string `f""`:

```python
age = 10
print(f"His age is: {age}")

```

This prints `"His age is: 10"`

Before the quotation marks `""` we add the letter `f` and inside the string wherever we put parenthesis `{}` it will insert the value of what is written inside it.

***ª QUIZ***

<aside>
💡

What is the purpose of using `f` before the quotation marks in Python strings?

To make the string formatted, allowing variables to be inserted within the string

To flag the string as 'fast' and optimize its storage

To indicate the string should be read from a file

To format the string as fixed-width

</aside>

***• CHALLENGE***

You are given a code that stores a random string as input to a variable named `rnd`.

Print to the console `"The input is: "` and the random string that is inside the variable `rnd`.

> Check the test cases for examples!
> 

```python
rnd = input() # Don't change this line
print(f"The input is: {rnd}")

# Explanation
In your print statement, you're currently using "The input is: rnd" which treats rnd as a string literal instead of the variable's value.

To correctly include the value of the variable rnd in your output, you need to use an f-string. Remember to place rnd inside curly braces {} within the f-string.

Your print statement should look like this: print(f"The input is: {rnd}"). This will ensure that the value stored in rnd is printed instead of the text "rnd".
```

## INPUT [⏫](https://www.notion.so/Python-1356bec38d3e803680dac1b551a9cc01?pvs=21)

As of now we stored values that we thought about in variables. Programs usually don't work this way. We receive values from an outer source, a user for example.

To get input from a user or the system we need to write:

```python
var = input()
```

This will store the input in the variable `var`.

> The input is always of type string. For example, if the input is 56 then var will hold the string "56".
> 

***ª QUIZ***

<aside>
💡

What is the default data type of the input received from the `input()` function in Python?

integer

float

boolean

string

</aside>

<aside>
💡

How do you store the user's input in a variable named `userAge`?

userAge <- input()

input() = userAge

set userAge = input()

userAge = input()

</aside>

<aside>
💡

If a user inputs the number 42, which of the following representations is correct for the variable `var` storing this input?

"'42'"

42

None of the options

"42"

</aside>

***• CHALLENGE***

Write a program that get input from the user (their name), and then outputs `Hello,`  followed by the user's inputted name.

For example, if the user inputs `Bob`, the expected output is `Hello, Bob`.

You will need to:

1. Use `input()` to get input from the user.
2. Store the input in a variable.
3. Print `Hello,`  and the stored variable in the end.

```python
name = input()
print(f"Hello, {name}")
```

## CAST [⏫](https://www.notion.so/Python-1356bec38d3e803680dac1b551a9cc01?pvs=21)

To convert the input to a different type we need to **cast**.

To cast a string to int (a whole number) we will write:

```python
var = input()
var = int(var)
```

Or in one line,

```python
var = int(input())
```

If the input is a number, i.e. 5, 4, 54 then `var` will hold a number. If the input contain an invalid number: 5ab, bb, akt, etc. then the program will fail.

Here is a table that shows how to cast to different types:

| Cast | Explanation |
| --- | --- |
| int() | Convert to a whole number |
| float() | Convert to a real number |
| bool() | Convert to a boolean |
| str() | Convert to a string |

> It is important to use the right type because it can affect the output.Adding two string will result of:
"5" + "5" = "55"
Adding two numbers will result of:
5 + 5 = 10
> 

***ª QUIZ***

<aside>
💡

What does the `int()` function do in Python?

Convert a value to a boolean

Convert a value to a real number

Convert a value to a whole number

Convert a value to a string

</aside>

<aside>
💡

Which type conversion would you use to obtain a real number from a string in Python?

bool()

str()

float()

int()

</aside>

<aside>
💡

What will be the result of adding two strings `'5' + '5'` in Python?

Error

'10'

'55'

10

</aside>

***• CHALLENGE***

To receive multiple inputs from the user write them multiple times:

```python
var1 = input()
var2 = input()
```

Every test case contains two inputs.

Store the inputs in two variables, cast them to **float** and print the **multiplication** of the two.

```python
var1 = float(input())
var2 = float(input())
result = float(var1 * var2)
print(result)
```

## RECAP CHALLENGE #1 [⏫](https://www.notion.so/Python-1356bec38d3e803680dac1b551a9cc01?pvs=21)

Write a program that gets input from the user, his age.

The program will output (print) the number of missing **years till 120** (in a specific format, shown below).

For example, for input `25`, the expected output is `"95 years till 120"`.

> Make sure to not print anything else!
> 

```python
age = int(input())  # Get age input from the user
years_remaining = 120 - age  # Calculate years remaining until 120
print(f"{years_remaining} years till 120")  # Print in the specified format

Explanation:
The program takes the user's age as an integer input.
It calculates the years remaining until 120 by subtracting the age from 120.
It then prints the result in the format, "X years till 120".

```

## RECAP CHALLENGE #2 [⏫](https://www.notion.so/Python-1356bec38d3e803680dac1b551a9cc01?pvs=21)

Write a program that gets an input from the user, a number, `1` or `0`.

The program will output `"T"` if the input is 1 and `"F"` otherwise.

> Remember! you can cast the input to number using int()
> 

```python
number = int(input())
output = "None"
if number == 1:
    output = "T"
else:
    output = "F"
print(f"output = {output}")

# Explanation
The code you provided takes a number as input and sets output to "T" if the number is 1; otherwise, it sets output to "F". It then prints the result in the format output = T or output = F.

Here’s a breakdown of how it works:

number = int(input())  # Get input from the user and convert it to an integer
if number == 1:
    output = "T"       # Set output to "T" if the input is 1
else:
    output = "F"       # Otherwise, set output to "F"
print(f"output = {output}")  # Print the result in the specified format
Example Output
If the input is 1, the output will be:

output = T
If the input is anything other than 1, the output will be:

output = F
```

## REHEARSAL [⏫](https://www.notion.so/Python-1356bec38d3e803680dac1b551a9cc01?pvs=21)

You are given a code that stores a random string as input to a variable named `rnd`.

Print to the console `"The input is: "` and the random string that is inside the variable `rnd`.

> Check the test cases for examples!
> 

```python
rnd = input() # Don't change this line
print(f"The input is: {rnd}")

# Explanation
In your print statement, you're currently using "The input is: rnd" which treats rnd as a string literal instead of the variable's value.

To correctly include the value of the variable rnd in your output, you need to use an f-string. Remember to place rnd inside curly braces {} within the f-string.

Your print statement should look like this: print(f"The input is: {rnd}"). This will ensure that the value stored in rnd is printed instead of the text "rnd".
```

# LOOP [⏫](https://www.notion.so/Python-1356bec38d3e803680dac1b551a9cc01?pvs=21)

## FOR LOOP [⏫](https://www.notion.so/Python-1356bec38d3e803680dac1b551a9cc01?pvs=21)

Sometimes when programming it's necessary to perform same or almost the same operation a couple of times.

To prevent writing the same thing over and over again we can use **Loops**.

The `for` loop has the following syntax:

```python
**for i in range(start, end):
    code**
```

The `range(start, end)` determines what is the `start` value and what is the `end` value. The `i` will receive all values from `start` to `end` (**not including `end`**) sequentially. For example:

```python
for i in range(0, 5):
    print(i)

```

It will execute the print statement 5 times:

```python
0
1
2
3
4
```

> We can simplify the range(0, 5) to range(5):for i in range(5):    print(i)
> 

Loops have many use cases, For example let's sum all the number from 1 to 100:

```python
sum_numbers = 0
for i in range(1, 101):
    sum_numbers += i
print(sum_numbers)

#Explanation
sum_numbers = 0
This initializes a variable called sum_numbers and sets it to 0. This variable will be used to accumulate the sum of the numbers from 1 to 100.

for i in range(1, 101):
This loop iterates over the numbers from 1 to 100 (inclusive). In Python, range(start, end) generates a sequence from start up to, but not including, end. So range(1, 101) produces numbers from 1 to 100.

    sum_numbers += i
Inside the loop, sum_numbers is updated by adding the current value of i to it. The += operator is a shorthand for sum_numbers = sum_numbers + i.

Each time the loop runs, i takes on the next value in the range, and this value is added to sum_numbers.

print(sum_numbers)
After the loop completes, this line outputs the total sum of all numbers from 1 to 100.

Result: The sum of numbers from 1 to 100 is calculated and printed, which is 5050.

This is consistent with the formula for the sum of the first 
nn natural numbers:

Sum=n×(n+1)2=100×1012=5050

Sum=2n×(n+1)=2100×101=5050
```

This will first loop through all numbers between 1 to 101 (not including 101) and sum all of them, Then it will print the `sum_numbers` variable

***ª QUIZ***

<aside>
💡

What is the output of the following code snippet?

```python
for i in range(3):
    print(i)

```

None of the options

0 1 2 3

1 2 3

0 1 2

</aside>

<aside>
💡

Which syntax correctly represents a `for` loop in Python that iterates from 1 to 10, inclusive?

for i in range(1, 11)

for i in range(10)

for i in range(0, 10)

for i in range(1, 10)

</aside>

***• CHALLENGE***

Write a program that prints `"Hello Coddy: "` and the `i` value from 3 to 27 (including, 25 times in total), do it using a **for loop**.

It will look like this:

```python
Hello Coddy: 3
Hello Coddy: 4
...
Hello Coddy: 27
```

## WHILE LOOP [⏫](https://www.notion.so/Python-1356bec38d3e803680dac1b551a9cc01?pvs=21)

# FUNCTIONS [⏫](https://www.notion.so/Python-1356bec38d3e803680dac1b551a9cc01?pvs=21)

https://github.com/Asabeneh/30-Days-Of-Python/blob/master/readme.md

[Get used to learning Pandas & DataFrame](https://www.notion.so/Get-used-to-learning-Pandas-DataFrame-5f51f245dd5847a1a8820f9c1f7476ca?pvs=21)
