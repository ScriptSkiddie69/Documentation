# Lua documentation made by dex
# What is lua? 
lua is known for a coding language for roblox, world of warcraft otherwise it is used for networking
# Alright lets get started!

# Lets get started with datatypes.
Datatypes are group of collections of data values
These are:
```lua
table: {}
number or number: <number> or 1 for example
float: <float> or 0.1 or 1.1
boolean or bool: true, false
string or str: "Hello This is a string" 
nil: nil represents no value so its like 0 but it has nothing in it
```
We only listed simple datatypes as to not get confusing we'll get to the advanced later
# Lua keywords:
```lua
and,	break,	do,	else
elseif,	end,	false,	for,
function,	if,	in,	local,
nil,	not,	or,	repeat,
return,	then,	true,	until,
while

```
# Basic lua syntax
Now lets get to the real coding part!
How are we gonna output strings, variable, etc into the console?
Heres how:
```lua
print('Hello World')
```
# Output:
```lua
Hello World
```
Notice how it outputted Hello World? we could do a different one
```lua
print('Hello from dex!')
```
# Output:
```lua
Hello from dex!
```
Now it says hello from dex!
How would we use variable in this case? heres how
```lua
local anyname = <datatype>
```
We need to use any data type to be stored in the variable
Lets use string!
```lua
local anyname = "Hello World"
print(anyname)
```
# Output:
```lua
Hello World
```
If you ask can we do a different datatype? 
Sure
Lets use number or boolean
```lua
local anyname = 69
print(anyname)
```
# Output: 
```lua
69
```
Now it prints number
Lets do boolean!
```lua
local anyname = <bool>
```
Theres 2 values in boolean datatype its true and false lets use true
```lua
local anyname = true
print(anyname)
```
# Output:
```
true
```
Now if u ask how to make description in ur code?
Here is how we could commend it by using #
Heres an example:
```lua
print('Helo World') # prints Helo World ths is an example on putting description on ur code!
```
# Output:
```lua
Helo World
```
Notice how the output hasnt changed? its becaused we only added description or comment
Now you know what is variable and datatypes lets get into operators!
We're gonna explain 3 different operators this include such as:
Math operator / Arithmetic operator
Relations operator 
Logical operator
Lets start with math operator

# Math operators:
```lua
+ : Addition
- : Subtraction
* : Multiplication
/ : Division
% : Modulus
^ : Exponentiation
- : Unary negation
```
Math Operator is the same in lua as how u use math in real life 
Example:
```lua
local calculate = 5 * 2 
```
# Output:
```lua
10
```
What is that "*" u asking? its multiplication instead of X we used * because it is how it is implemented in lua
More examples:
```lua
local calculate = 10 + 10
print(calculate)
```
# Output:
```lua
20
```
Now u understand math operators lets get into logical and relational operator
# Logical and relational operator:
```lua
== : Equal to
~= : Not equal to
> : Greater than
< : Less than
>= : Greater than or equal to
<= : Less than or equal to
Logical Operators:
and : Logical AND
or : Logical OR
not : Logical NOT
```


