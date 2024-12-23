# Lua documentation made by dex
# What is lua? 
lua is known for a coding language for roblox, world of warcraft otherwise it is used for networking
# Alright lets get started with lua

# Lets get started with datatypes.
Datatypes are group of collections of data values
These are:
```lua
table: {}
number: 1, 30, 31, 3.33, etc
float: 0.1, 1.1, etc
bool or boolean: true, false
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
Here is how we could commend it by using "--"
Heres an example:
```lua
print('Helo World') -- prints Helo World ths is an example on putting description on ur code!
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
Relational Operators:
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
We could use them to check if they are equal to what ur gonna equal it to i dont know how to explain but here is the best explanation:
```lua
local a = 5
local b = 5
local example = a==b
print(example)
```
# Output:
```lua
true
```
See it output true? it is because a and b are the same value and we equal it to using == operator
All Relational operators always returns <bool> true or false
Now lets get to Logical Operators
First we start with NOT logic
```lua
local a = true
print(not a) 
```

# Output:
```
false
```
Notice how it output false instead of true? it is because we put not in it
not is used to negate a boolean or bool value it returns the opposite value of its operand
Now lets get to OR logic
```lua
local a = true
local b = false
print(a or b)
print(b or a)
```
# Output:
```lua
true
true
```
Notice how the two outputs true? 
it is because "or" returns 'true' if one contains atleast true in it or if one of its operand contains atleast true in it
Now lets get to AND logic
```lua
local a = true
local b = false
print(a and b)
print(b and a)
```
# Output:
```lua
false
false
```
Notice how both outputs are false?
It is because "AND" logic returns the value if both are true it returns true if both arent true it returns false if one is true and other is false it returns false
Example again:
```lua
local a = true
local b = true
print(a and b)
```
# Output:
```
```lua
true
```
Now we're done with operators lets get to conditional statements:

# Conditional Statements:
If u scroll back at keywords you will see "if" and "then" and "else" and "elseif"
They are used for conditional statements we will use that to construct if statement
We will use logical operator too to construct if statement
Here is how:

```lua
local a = true
local b = true
if a == b then
print('The condition passed!')
end
```
# Output:
```lua
The condition passed!
```
Noticed how it output The condition passed? and there is an end?
We needed to put an "end" when putting if statement at the end of the condition.
It is because we used the Equal To operator or "==" both are the same value so it passes the conditional statement
If ur questioning what if the other one is not the same value? Lets see that..

```lua
local a = true
local b = false
if a == b then
print('The condition passed!')
end
```

# Output
```
```
Noticed how the output is empty? 
It is because the condition havent passed we need to add else to make that happen 
Here is how:
```lua
local a = true
local b = false
if a == b then
print('The condition passed!')
else
print('The condition havent passed!')
end
```
# Output
```lua
The condition havent passed!
```
Noticed how the output is the opposite?
It is because it havent passed the equal to and we put an "else" so it detects if it havent passed the condition statement
Now if ur asking how to make a multiple if statement in one if statement 
It is made possible using a keyword called "elseif"
```lua
local a = true
local b = false
if a == b then
print('the condition passed!')
elseif a~=b
print('condition not passed')
end
```
# Output:
```lua
condition not passed
```
It is not the best to use elseif in that case but it is what it is
We used ~= aka "not equal to" for elseif

Now were done with conditional statements lets get into loops
There are 3 types of loop while, for, repeat
Lets get started with the most simple one "for loop"
Heres how to use it:

```lua
for i = 1,50 do
print(i)
end
```
# Output:
```lua
1
2
3
4
5
6
7
8
9
10
11
12
13
14
15
16
17
18
19
20
21
22
23
24
25
26
27
28
29
30
31
32
33
34
35
36
37
38
39
40
41
42
43
44
45
46
47
48
49
50
```
It loops for 50 times and the i is the variable thats stored in the loop so u can see how many times it had looped
U need to put an end just like in the condition statement
Now we're onto while loop how can we use it? 
Here is how to use it:

```lua
local a = true
while a do wait()
print('Looped')
end
```
# Output:
```lua
Looped
Looped
Looped
Looped
Looped
And so on
```
It will loop until the bool is false eventually so if u set "A" to false it will not loop
Now lets get into repeat loop
```lua
local hai = false
repeat wait()
print('repeating')
until hai -- this will keep printing repeating until hai is true
```

# Comment
```lua
repeating
repeating
repeating
repeating
repeating
repeating
and so on
```
Notice how similar they are?
It will loop until the bool is true eventually so if u set hai to true it will not 

Now were done with loops lets get into function to simplify and beautify ur code!
Here is how to use "function"
```lua
function abcd(arguments) 
```
Basically the arguments would just be like a variable but for function example:
```lua
function abcd(a, b) 
print(a,b) 
end
abcd("hello","hai")
```
# Output:
```lua
Hello hai
```

Lets modify that to calculate!
```lua
function abcd(a, operator, b)
if operator == "+" then
print(a + b)
elseif operator == "*" then
print(a * b)
 --and so on
end
abcd(5, *, 5)
```
# Output:
```
25
```
Basically u can put any code in the function aslong as it doesnt have any errors


# We'll get into index, newproxy, metatable, etc some advanced stuff soon
