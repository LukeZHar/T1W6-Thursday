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

age = 20 
has_permission = False

if age >= 18:
    if has_permission:
        print("Access granted")
    else:
        print("Access Denied")
else: 
    print("Access Denied")

if age >= 18 and has_permission:
    print("Access Granted")
else:
    print("Access denied")

# Tenary Operator
Condense series of code to one line, where applicable 

age = 20 
has_permission = False

print("Access Granted" if age >= 18 and has_permission else "Access Denied")

temperature = 30

<!-- # if temperature >  30:
#     message = "It's Hot outside"
# else:
#     message= "It's not hot outside"

# print(message) -->

message = "It's hot outside" if temperature > 30 else "It's not hot outside"

# Match-case
Control flow, similar to switch statements in other programming languages

day_number = 3

match day_number:
    case 1:
        day_name = "Monday"
    case 2: 
        day_name = "Tuesday"
    case 3: 
        day_name = "Wednesday"
    case 4:
        day_name = "Thursday"

print(day_name)


# Activity
Whites a python script that asks the user to input a numerical score and caterogrizes it into grade (A, B, C, D, F) based on the following:

90-100: A
80-89: B
70-79: C
60-69: D
59 below: Fail

<!-- # Prompt the user to enter a score -->
score = int (input("Enter the score (0-100):"))

if score >= 90 and score <= 100:
    grade = "A"
elif score >= 80:
    grade = "B"
elif score >= 70:
    grade = "C"
elif score >= 60:
    grade = "D"
else:
    grade = "F"

print(f"The grade for score {score} is {grade}")