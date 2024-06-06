# T1W6-Thursday
## Control Flow
Order in which l;ines of code are executed in a program

print("Hello, welcome to python")

a = 10
b = 5
result = a + b

print(f"The result of adding {a} and {b} is {result}")

print ("Thank you")

# Sequentual control flow
Execution of code statements one after another, in the order they appear in the program,

# Conditional control flow / control flow
Execution of code statements based ons ome input 

if tommorow is Saturday
    set alarm for 7
if tomorrow is Tuessday
    set alarm for 6

# Boolean Data type Re-visit
Data type that has twop values: True and False. Boolean values are used to control the flow of the program.

is_the_earth_flat = False
print(is_the_earth_flat)

i_am_happy = True
print(i_am_happy)

# Comparison Operators / Relational Operators 
Decide the relationship between the operands. Result iof comparison is a boolean value (True/False)

if tommorow == Saturday
    set alarm for 7
if tomorrow == Tuessday
    set alarm for 6

print(x > y) # Greater than
print(x < y) #lesser than
print(y == z) # equals too
print(y <= z) #lesser or equal too
print(y >= z) #greater or equal too
print(y != z) #means not

# if, elif, else
Simplest form of AI (you could say that)
'if' checks condition, if true, the extended logs get executed, if false, skips the intended blocks

today = "Tuesday"

if today == "Monday":
    print("set alarm for 5AM")
elif today == "Tuesday":
    print("Set alarm for 6AM")
elif today == "Saturday":
    print("Set alarm for 7AM")

temperature = 30

if temperature > 35:
    print("It's hot outside.")
elif temperature < 15:
    print("It's cold outside.")
else:
    print("The weather is mild.")


# Pass
Does nothing, just passes 

# Boolean Operators 
AND, OR, NOT. 

a = True 
b = False

result = a or b # True
print(result)

result = a or b # false
print(result)

result = not b # True
print(result)