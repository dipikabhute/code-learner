---
title: 📌PYTHON DATA TYPES 
nav_order: 2
parent: Unit 1
---

---

# 🌟 Introduction to Python Data Types

## Python मध्ये data store करण्यासाठी Data Types वापरतात.
### Different type चा data store करण्यासाठी Python वेगवेगळे data types provide करतो.

---
---
# 📂 Python Data Types Diagram

---                     Python Data Types                           │
-  ┌───┼────┐          ┌─────┼─────┐
│   │    │          │     │     │
 int float complex  String List Tuple

 ---

## 🔢 1. Numeric Data Types

## 📖 Definition

 ### Numbers store करण्यासाठी वापरले जाणारे data types म्हणजे Numeric Data Types.

## 📋 Types of Numeric Data Types

## Data Type	         Description	          Example

###  int              	Whole Number	              10
### float	            Decimal Number	              5.5
### complex	            Imaginary Number	          2+

## 1️⃣ Integer (int) Data Type

## 📖 Definition

### Whole numbers store करण्यासाठी int वापरतात.

####   ✔️ Decimal नसतो
####   ✔️ Positive किंवा Negative value असू शकते

## ✨ Syntax

### variable_name = value

## 💻 Example

## a = 10
## b = -20

## print(a)
## print(b)

## 📤 Output

 ## 10
 ## -20

## ⚡ Features of Integer

## ✔️ Whole numbers store करतो
## ✔️ Memory efficient
## ✔️ Immutable data type

## ✅ Advantages

## ✔️ Fast calculations
## ✔️ Easy to use
## ✔️ Less memory usage

## ❌ Disadvantages

## ❌ Decimal values store करू शकत नाही

## 📌 Important Exam Point

## 🔥 int decimal numbers support करत नाही.


## 2️⃣ Float (float) Data Type

## 📖 Definition

## Decimal values store करण्यासाठी float वापरतात.

## 💻 Example

## x = 10.5
## y = -3.14

## print(x)
## print(y)

## 📤 Output 
## 10.5
## -3.14

## ⚡ Features of Float

## ✔️ Decimal values support
## ✔️ Scientific calculations साठी useful
## ✔️ Immutable

## ✅ Advantages

## ✔️ Accurate decimal calculations
## ✔️ Scientific use

## ❌ Disadvantages

## ❌ Integer पेक्षा जास्त memory वापरतो

## 📌 Float Example Diagram

## 10.5  │
## ├── 10 → Integer Part
## └── .5 → Decimal Part


## 3️⃣ Complex (complex) Data Type

## 📖 Definition

## Complex number म्हणजे:

## Real Part + Imaginary Part(j)

## ✨ Structure

## a + bj

## Example:

## 2 + 3j

## 💻 Example

## c = 2 + 3j

## print(c)
## print(type(c))

## 📤 Output

## (2+3j)
## <class 'complex'>

## 🔍 Real and Imaginary Part
## c = 4 + 5j

## print(c.real)
## print(c.imag)

## 📤 Output
## 4.0
## 5.0

## ✅ Advantages

## ✔️ Mathematical calculations
## ✔️ Engineering applications
 
## ❌ Disadvantages

## ❌ Beginners साठी difficult वाटू शकतो


## 🔤 2. String Data Type

## 📖 Definition
## Characters चा collection म्हणजे String.

## ✨ String Creation
## name = "Dipika"
## city = 'Pune'

## print(name)
## print(city)

## 📌 String Features

## ✔️ Immutable
## ✔️ Ordered
## ✔️ Indexing supported
## ✔️ Slicing supported

# 🔧 String Operations

## 1️⃣ Concatenation (+)

## 📖 Definition
दोन strings जोडण्यासाठी वापरतात.

## 💻 Example
## a = "Hello"
## b = "Python"

## print(a + " " + b)

## 📤 Output
##          Hello Python


## 2️⃣ Repetition (*)

## 💻 Example
## print("Hi " * 3)

## 📤 Output
##           Hi Hi Hi


## 3️⃣ String Indexing

## 📖 Definition
## Character position वापरून access करणे.

## 💻 Example
##    text = "Python"
##    print(text[0])
##    print(text[3])

## 📤 Output
## P
## h

 ## 📌 Index Diagram
 ## P   y   t   h   o   n
 ## 0   1   2   3   4   5


 ## 4️⃣ String Slicing

 ## 📖 Definition
 ## String मधून specific part काढणे म्हणजे slicing.

 ## ✨ Syntax
 ##         string[start:end]

 ## 💻 Example
 ##     text = "Programming"

 ##      print(text[0:6])
 ##      print(text[3:8])

 ## 📤 Output
 ## Progra
 ## gramm

 ## ⚡ Important Point

 ## ✔️ Start index include होतो
 ## ✔️ End index exclude होतो

 ## ✅ Advantages of String

 ## ✔️ Easy text handling
 ## ✔️ Unicode support

 ## ❌ Disadvantages

 ## ❌ Immutable असल्यामुळे direct changes होत नाहीत

 ## 📋 3. List Data Type

 ## 📖 Definition
 ## Multiple values store करण्यासाठी List वापरतात.

 ## ✨ Features of List

 ## ✔️ Ordered
 ## ✔️ Mutable
 ## ✔️ Duplicate values allow

 ## 📌 Syntax

 ## list_name = [values]

 ## 💻 Example
 ## numbers = [10, 20, 30, 40]

 ## print(numbers)

 ## 🔍 Accessing List Elements

 ##  numbers = [10, 20, 30]

 ## print(numbers[0])
 ## print(numbers[2])

 ## 📤 Output
 ## 10
 ## 30

 ## ✂️ List Slicing

 ## 💻 Example
 ## numbers = [10, 20, 30, 40, 50]
 ## print(numbers[1:4])

 ## 📤 Output
 ## [20, 30, 40]

 ## 📌 List Diagram
 ## Index →   0    1    2    3
 ## List  → [10, 20, 30, 40]

 ## 🔄 Modifying List
 ## data = [1, 2, 3]

 ## data[1] = 100

 ## print(data)

 ## 📤 Output
 ## [1, 100, 3]

# 📋 Common List Functions

 ## Function	Work
 ## append()	Add element
 ## insert()	Insert element
 ## remove()	Remove element
 ## pop()	    Delete element
 ## sort()	     Sort list

 ## ✅ Advantages

 ## ✔️ Easy data storage
 ## ✔️ Dynamic size
 ## ✔️ Mutable

 ## ❌ Disadvantages

 ## ❌ Large lists memory जास्त वापरतात

 ## 📦 4. Tuple Data Type

 ## 📖 Definition
 ##    Tuple म्हणजे immutable ordered collection.

 ## ✨ Features

 ## ✔️ Immutable
 ## ✔️ Faster than list
 ## ✔️ Ordered

 ## 📌 Syntax
 ##          tuple_name = (values)

 ## 💻 Example
 ##    t = (10, 20, 30)
 ##    print(t)

 ## 🔍 Accessing Tuple Elements

 ## t = (100, 200, 300)
 ## print(t[1])

 ## 📤 Output
 ##     200

 ## ✂️ Tuple Slicing
 ##  t = (1, 2, 3, 4, 5)
 ##  print(t[1:4])

 ## 📤 Output
 ##    (2, 3, 4)


 ## ⚖️ Difference Between List and Tuple
 ## List	Tuple
 ## Mutable	Immutable
 ## Uses []	Uses ()
 ## Slower	Faster

 ## ✅ Advantages of Tuple

 ## ✔️ Faster processing
 ## ✔️ Secure data storage

 ## ❌ Disadvantages

 ## ❌ Values modify करता येत नाहीत

 ##  🔄 5. Type Conversion

 ## 📖 Definition
 ## एका data type ला दुसऱ्या data type मध्ये convert करणे म्हणजे Type Conversion.

 ## 📌 Conversion Diagram

 ## String → int()
 ## String → float()
 ## Number → str()

  
 ## 💻 Integer Conversion
 ##    x = "10"
 ##    y = int(x)

 ##    print(y)

 ## 💻 Float Conversion
 ## a = "5.5"
 ## b = float(a)
 ## print(b)

 ## 💻 String Conversion
 ##     num = 100
 ##     text = str(num)
 ##     print(text)

 ## ✅ Advantages

 ## ✔️ Flexible programming
 ## ✔️ Easy data manipulation

 ## ❌ Disadvantages

 ## ❌ Wrong conversion causes error

# 🛠️ 6. Built-in Functions

 ## 📖 Definition
 ## Python मध्ये already available functions म्हणजे Built-in Functions.

 ## 📋 Common Built-in Functions

 ## Function	Work
 ## print()	 Output display
 ## input()	 User input
 ## type()	 Show data type
 ## len()	 Length count
 ## max()	 Maximum value
 ## min()	 Minimum value
 ## sum()	 Total
 ## abs()	 Absolute value

 ## 💻 print() Function
 ##    print("Hello")
 
##  💻 input() Function
##  name = input("Enter name: ")
##  print(name)

## 💻 type() Function
##    x = 10
##    print(type(x))

##  💻 len() Function
 ##    text = "Python"
##     print(len(text))

##  💻 max() and min()
##      numbers = [10, 20, 5]
##      print(max(numbers))
##      print(min(numbers))

##  📤 Output
##      20
##      5

##  💻 sum() Function
##     nums = [1, 2, 3]
##     print(sum(nums))

##  📤 Output
##      6

##   💻 abs() Function
##        print(abs(-10))

##  📤 Output
##        10

---

