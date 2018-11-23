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
### 2.2 Sets
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
