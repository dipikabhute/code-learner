---
title: 📌PYTHON DATA TYPES 
nav_order: 2
parent: Unit 1
---

---

# 🌟 Introduction to Data Types

## 📖 Definition
### A Data Type defines the type of value a variable can store.
### 👉 Python automatically identifies the data type when a value is assigned.

## 🧠 Example

###    a = 10
###    b = 3.14
###    c = "Python"

---

## |  Variable	    |Value	      |Data Type|
  

   | a	            |10	          | int      |
    
   | b	            |3.14	      |float    |
    
 | c	            |Python	      |string   |

 ---

🔢 Numeric Data Types

Python provides 3 main numeric data types:

Data Type	Description	Example
int	Integer numbers	10
float	Decimal numbers	3.14
complex	Complex numbers	2+3j
🔹 Integer (int)
📖 Definition

int stores whole numbers without decimal points.

✅ Example
x = 100
print(x)
print(type(x))
📌 Output
100
<class 'int'>
⭐ Features

✔️ Positive and negative numbers
✔️ No decimal point
✔️ Unlimited length

🎯 Real Life Example
Age = 20
Marks = 95
Number of students = 50
🔹 Float (float)
📖 Definition

float stores decimal point numbers.

✅ Example
price = 99.99
print(price)
print(type(price))
📌 Output
99.99
<class 'float'>
⭐ Features

✔️ Decimal values
✔️ Scientific notation supported

✅ Scientific Notation Example
x = 2.5e3
print(x)
📌 Output
2500.0
🔹 Complex (complex)
📖 Definition

Complex numbers contain a real part and an imaginary part.

👉 Imaginary part uses j.

✅ Example
z = 2 + 3j
print(z)
print(type(z))
📌 Output
(2+3j)
<class 'complex'>
📌 Formula

z=a+bj

Where:

a = Real part
b = Imaginary part
🔤 String Data Type
📖 Definition

A String is a collection of characters enclosed in quotes.

✅ Creating Strings
name = "Python"
city = 'Pune'
✨ String Operations
🔹 1. Concatenation (+)
a = "Hello"
b = "World"

print(a + " " + b)
📌 Output
Hello World
🔹 2. Repetition (*)
print("Hi " * 3)
📌 Output
Hi Hi Hi
🔹 3. Indexing
text = "Python"

print(text[0])
print(text[2])
📌 Output
P
t
🔹 4. Slicing
📖 Syntax
string[start:end]
✅ Example
word = "Programming"

print(word[0:6])
📌 Output
Progra
🔹 5. Length Function
text = "Python"

print(len(text))
📌 Output
6
📋 List Data Type
📖 Definition

A List is an ordered collection of items.

✔️ Mutable (can change)
✔️ Allows duplicate values

✅ Creating List
numbers = [10, 20, 30, 40]
print(numbers)
📌 Output
[10, 20, 30, 40]
✨ List Features

✔️ Ordered
✔️ Mutable
✔️ Heterogeneous data allowed

🔪 List Slicing
📖 Syntax
list[start:end]
✅ Example
data = [1,2,3,4,5,6]

print(data[1:4])
📌 Output
[2, 3, 4]
📊 List Slicing Diagram
Index:   0   1   2   3   4   5
Value:  [1,  2,  3,  4,  5,  6]
📦 Tuple Data Type
📖 Definition

A Tuple is an ordered collection of items that cannot be changed.

✔️ Immutable
✔️ Faster than lists

✅ Creating Tuple
t = (10, 20, 30)

print(t)
📌 Output
(10, 20, 30)
🔍 Tuple Features

✔️ Ordered
✔️ Immutable
✔️ Allows duplicates

📊 Difference Between List and Tuple
Feature	List	Tuple
Symbol	[]	()
Mutable	Yes	No
Speed	Slower	Faster
Memory	More	Less
🔄 Type Conversion
📖 Definition

Changing one data type into another is called Type Conversion.

🔹 Integer to Float
x = 10

print(float(x))
📌 Output
10.0
🔹 Float to Integer
y = 5.8

print(int(y))
📌 Output
5
🔹 Integer to String
num = 100

print(str(num))
📌 Output
"100"
⚙️ Built-in Functions
📖 Definition

Functions already available in Python are called Built-in Functions.

🔹 Important Built-in Functions
Function	Purpose
type()	Shows data type
len()	Finds length
int()	Converts to integer
float()	Converts to float
str()	Converts to string
list()	Converts to list
tuple()	Converts to tuple
✅ Example of Built-in Functions
x = "Python"

print(len(x))
print(type(x))
📌 Output
6
<class 'str'>
📊 Comparison of Numeric Data Types
Feature	int	float	complex
Decimal Allowed	❌	✔️	✔️
Imaginary Part	❌	❌	✔️
Example	10	3.14	2+3j
✅ Advantages and Disadvantages
🔹 Advantages

✔️ Easy to use
✔️ Beginner friendly
✔️ Flexible data handling
✔️ Fast development

🔹 Disadvantages

❌ High memory usage
❌ Slower than compiled languages
❌ Runtime errors possible

🎯 Important Interview Questions and Answers
❓1. What is a data type in Python?
✅ Answer:

A data type defines the kind of value a variable can store.

❓2. Difference between List and Tuple?
✅ Answer:
List	Tuple
Mutable	Immutable
Uses []	Uses ()
❓3. What is slicing?
✅ Answer:

Slicing is used to extract a part of a sequence.

Example:

text[1:4]
❓4. What is a complex number?
✅ Answer:

A number containing real and imaginary parts.

Example:

2 + 3j
❓5. What is type conversion?
✅ Answer:

Changing one data type into another.

Example:

int(3.5)
📝 Exam-Oriented Key Points
⭐ Remember These

✔️ int → Whole numbers
✔️ float → Decimal numbers
✔️ complex → Imaginary numbers
✔️ Strings use quotes
✔️ Lists are mutable
✔️ Tuples are immutable
✔️ Slicing uses [start:end]
✔️ type() checks data type

📚 Summary
🔥 In This Chapter You Learned:

✔️ Numeric data types (int, float, complex)
✔️ String operations
✔️ Lists and slicing
✔️ Tuple data type
✔️ Type conversions
✔️ Built-in functions

🎓 Final Conclusion

Python data types are the foundation of programming.
Understanding lists, tuples, strings, and numeric types helps in writing efficient and powerful programs. 🚀

🌟 Quick Revision Chart
int      → Whole Numbers
float    → Decimal Numbers
complex  → Imaginary Numbers
string   → Text Data
list     → Mutable Collection
tuple    → Immutable Collection
🚀 Happy Learning Python 🐍