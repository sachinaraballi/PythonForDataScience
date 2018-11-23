# Python For Data Science!
Beginner Guide to Python for Data Science

## 1 Python Basics

Here the tool used to run Python is Anaconda - Spyder (Python 3.7)

Comment and Print statement 

```python
#prints Hello World!
print('Hello World!')

```
### 1.1 Types

Types | Examples | Typecast
------- | --------- | --------
int | 1 | int('1') = 1
floats | 1.12 | float(1) = 1.0
str | "Sachin Araballi" | str(1) = 1
bool | True (1), False (0) | bool(1) = True

We can *type(value)* to get the type of value 

### 1.2 Expressions and Variables

```python
2 * 3 + 5
11

6 / 2 
3.0 # float

6 // 2
3 #int

#variable declaration
var = 10
#assign a value
var:20
```

### 1.3 String Operations

Here we have both positive indexing and negative indexing

name = "Sachin A"

S | A |  C |  H | I | N |  | A 
-- | -- | -- | -- | -- |-- | -- | -- | 
0 | 1 | 2 | 3 | 4 | 5 | 6 | 7 | 8
-8 | -7 | -6 | -5 | -4 | -3 | -2 | -1

name[0]:S name[8]:A or name[-8]:S name[-1]:A

* String : Slicing

    name[0:4] = SAC
    name[4:7] = HIN

* String : Stride
    
    name[::2]:SCI A
    name[0:5:2]:SCI
    
* Some String Methods
    mame.upper()
    
    name.replace('SA' , 'MA)
    
    name.find('A') -> 8
   

## 2 Python Data Structures
### 2.1 Lists and Tuples

#### Tuples
* In Python, there are different data types: string, integer and float. These data types can all be contained in a tuple.
* Tuples are immutable
```python
tuple1 = ("sachin", 100, 1.20)

#concatinating tuples
tuple2 = tuple1 + ("sarvesh" , 30)

#nested tuple
nested =(1, 2, ("sachin", "sarvesh") ,(3,4),("araballi",(1,2)))

#Access the element, with respect to index 2:
nested[3][1] - "sachin"

nested.index("1") - 0
```
#### Lists

Lists are mutable datastructures

```python
L = ["sachin", 1 , 2, 3]

#We can use the method "extend" to add new elements to the list:
L.extend(["sarvesh", 2])

["sachin", 1 , 2, 3, "sarvesh", 2]

L.append(["sarvesh", 2])
["sachin", 1 , 2, 3, ["sarvesh", 2]]

L.del("sarvesh")

"sachin, a".split(',');
[sachin, a]
```

### 2.2 Sets

A set is a unique collection of objects in Python. It is denoted by curly bracket **{}**. 
```python
set1 = {"carnatic", "pop", "hundostani", "western"}

list1 = [1, 2, 3, 4]
set2 = set(list1)

set2.add(5)

5 in set2
True

#common elements in 2 sets
set3 = set1 & set2

#difference
set3 = set1.difference(set2)

#intersection
set1.intersection(set2)   

#other methods union, issuperset , issubset
```
### 2.3 Dictionaries



## 3 Python Programming Fundamentals

### 3.1 Conditions and Branching
### 3.2 Loops
### 3.3 Functions
### 3.4 Objects and Classes

## 4 Working with Data in Python

### 4.1 Reading files with open
### 4.2 Writing files with open
### 4.3 Loading data with Pandas
### 4.4 Working with and Saving data with Pandas
