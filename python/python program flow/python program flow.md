---
title: 📌 Python Program FlowControl 
nav_order: 1
parent: Python
---
---

#📘 **What is Program Flow Control?**

### Program Flow Control means controlling the order in which statements execute in a program.

## Python executes code line by line, but using:

### ✅ Conditions
### ✅ Loops
### ✅ Loop Control Statements

### we can change the normal flow of execution.
---
## 🔷 Types of Flow Control in Python

|**Type**	                   |  **Purpose**          |    

|🔀 Conditional Statements	  |  Decision making      |

|🔁 Loops	                  | Repeating statements  |

|⚙ Loop Control Statements	  |Controlling loops      |

---

## **🔶 Conditional Statements in Python**

### Conditional statements are used to make decisions based on conditions.

## ✅ if Statement
### The if block executes only when the condition is True.

## 📌 Syntax

### if condition:
###     statement

## 📌 Example

### age = 20

### if age >= 18:
###     print("Eligible for voting")

## 📌 Output

### Eligible for voting

## 💡 Explanation

- Condition is checked

- If condition is True → block executes

- If False → skipped

## 🔷 Flowchart of if

### Condition True → Execute Block
### Condition False → Skip Block


## ✅ if-else Statement
- Used when there are two choices.

## 📌 Syntax

### if condition:
###     statement1
### else:
###     statement2

## 📌 Example

### num = 7

### if num % 2 == 0:
###     print("Even Number")
### else:
###     print("Odd Number")

## 📌 Output

### Odd Number


## ✅ if-elif-else Statement

- ###  Used to check multiple conditions.

📌 Syntax
if condition1:
    statement1

elif condition2:
    statement2

else:
    statement3
📌 Example
marks = 85

if marks >= 90:
    print("Grade A")

elif marks >= 75:
    print("Grade B")

elif marks >= 50:
    print("Grade C")

else:
    print("Fail")
📌 Output
Grade B
🔷 Nested if Statement

An if inside another if.

📌 Example
num = 10

if num > 0:

    if num % 2 == 0:
        print("Positive Even Number")
📌 Output
Positive Even Number
🔶 Block in Python

A block is a group of statements having the same indentation.

Python uses indentation instead of { }.

📌 Example
if True:
    print("Hello")
    print("Python")

Both statements belong to same block.

⚠ Importance of Indentation

Incorrect indentation causes errors.

❌ Wrong
if True:
print("Hello")
✅ Correct
if True:
    print("Hello")
🔁 Loops in Python

Loops repeat a block of code multiple times.

🔷 Types of Loops
Loop	Purpose
for loop	Fixed repetition
while loop	Repeat while condition is True
✅ Simple for Loop

Used to iterate through sequences.

📌 Syntax
for variable in sequence:
    statements
📌 Example
for i in [1, 2, 3]:
    print(i)
📌 Output
1
2
3
✅ for Loop Using range()

range() generates numbers.

🔹 range(stop)
for i in range(5):
    print(i)
📌 Output
0
1
2
3
4
🔹 range(start, stop)
for i in range(1, 6):
    print(i)
📌 Output
1
2
3
4
5
🔹 range(start, stop, step)
for i in range(2, 11, 2):
    print(i)
📌 Output
2
4
6
8
10
🔤 for Loop with Strings

Loops can iterate through each character.

📌 Example
name = "Python"

for ch in name:
    print(ch)
📌 Output
P
y
t
h
o
n
📋 for Loop with Lists
📌 Example
fruits = ["Apple", "Mango", "Banana"]

for fruit in fruits:
    print(fruit)
📌 Output
Apple
Mango
Banana
📖 for Loop with Dictionaries

Dictionary stores key-value pairs.

📌 Example
student = {
    "name": "Dipika",
    "age": 20
}

for key in student:
    print(key, ":", student[key])
📌 Output
name : Dipika
age : 20
🔁 while Loop in Python

The while loop executes while condition is True.

📌 Syntax
while condition:
    statements
📌 Example
i = 1

while i <= 5:
    print(i)
    i += 1
📌 Output
1
2
3
4
5
⚠ Infinite while Loop

Condition never becomes False.

📌 Example
while True:
    print("Hello")

⚠ Runs forever.

🔷 Loop Manipulation Statements

These statements control loop behavior.

📊 Types of Loop Control Statements
Statement	Purpose
break	Stop loop
continue	Skip current iteration
pass	Empty placeholder
else	Executes after loop completion
⛔ break Statement

Terminates loop immediately.

📌 Example
for i in range(1, 6):

    if i == 4:
        break

    print(i)
📌 Output
1
2
3
⏭ continue Statement

Skips current iteration.

📌 Example
for i in range(1, 6):

    if i == 3:
        continue

    print(i)
📌 Output
1
2
4
5
💤 pass Statement

Used as placeholder.

📌 Example
for i in range(5):
    pass
💡 Explanation
pass does nothing
Used for future code
✅ else with Loop

The else block executes when loop ends normally.

📌 Example
for i in range(3):
    print(i)

else:
    print("Loop Finished")
📌 Output
0
1
2
Loop Finished
🔷 Programming Using Conditional Statements and Loops
✅ Program 1: Check Positive or Negative
num = int(input("Enter Number: "))

if num > 0:
    print("Positive")

elif num < 0:
    print("Negative")

else:
    print("Zero")
✅ Program 2: Largest of Two Numbers
a = 20
b = 15

if a > b:
    print("A is Largest")

else:
    print("B is Largest")
✅ Program 3: Multiplication Table
num = 5

for i in range(1, 11):
    print(num * i)
📌 Output
5
10
15
20
25
30
35
40
45
50
✅ Program 4: Sum of Numbers
sum = 0

for i in range(1, 11):
    sum += i

print(sum)
📌 Output
55
✅ Program 5: Factorial Using while
num = 5
fact = 1

while num > 0:
    fact = fact * num
    num -= 1

print(fact)
📌 Output
120
✅ Program 6: Prime Number Check
num = 7
flag = True

for i in range(2, num):

    if num % i == 0:
        flag = False
        break

if flag:
    print("Prime Number")

else:
    print("Not Prime")
📊 Difference Between for and while
Feature	for Loop	while Loop
Iteration	Fixed	Depends on condition
Easy to Use	Yes	Moderate
Infinite Loop Risk	Less	High
Used For	Sequences	Conditions
🌟 Advantages of Loops

✅ Reduce code repetition
✅ Save time
✅ Increase efficiency
✅ Easy automation

⚠ Disadvantages of Loops

❌ Infinite loops possible
❌ Nested loops can become complex
❌ Wrong conditions may crash logic

📝 Important Interview Questions
What is flow control in Python?
Difference between if and if-else?
Explain elif with example.
What is indentation in Python?
Difference between for and while?
Explain break statement.
Explain continue statement.
What is pass statement?
What is infinite loop?
Explain loop else statement.
🎯 Conclusion

Python Flow Control helps in:

🔀 Decision Making
🔁 Repeating Tasks
⚙ Controlling Program Execution

Important concepts:

✅ if, else, elif
✅ for loop
✅ while loop
✅ break, continue, pass
✅ Conditional Programming

These topics are very important for:

📚 Exams
💻 Coding
🎤 Interviews
🚀 Projects
