# Welcome To Python!

This is Python Tutorials for beginner to start with

```python runnable
print('Hello World!')
```

# Vairables in Python

```python runnable
userName = "de Developer"
age = 23
print(age)
print(userName)
```
# Operators in Python

```python runnable
print("operators in python")
print("+, -, *, /")
print(2+3)
print(4-1)
print(12*2)
print(50/5)

print(23 or 32)
print(23 and 32)
print(23 != 23)

print(23<<32)
print(33<32)
print(23>>32)
print(23>23)
```

# if else statement in Python

```python runnable
userName = "de_Developer"
age = 23
if userName != " de_Developer" and age != 1234:
    print("Invalid Arguments")
else:
    print("Welcome Back")
```

# User Input in String format

```python runnable
userName = input("Enter Your Name: ")
print("Name: " + userName)
```

# User Input in integer format

```python runnable
age = int(input("Enter Your Age: "))
print("Age: " + age.toString)
```

# Simple Calculator program

```python runnable
value1 = int(input("Enter First Number: "))
value2 = int(input("Enter Second Number: "))
print(value1+value2)
print(value1-value2)
print(value1/value2)
print(value1*value2)
print(value1%value2)
```
# Data Types

```python runnable
stringDataTypes = "de Developer"
intDataType = 12
floatDataType = 23.2
setDataType = {1,2,3,4,5,6}
listDataType = [1,2,3,4,5,6,6,7,8]
tupleDataType = (1,2,3,4,5,6,7,8,9)
boolDataType = True
boolDataType = False
bytesDataType = b"developer"
complexDataTypes = 23j
rangeDataType = range(23)


```
# Type Casting

```python runnable
stringDataTypes = "12"
intDataType = 12
# conversion of string to int
stringDataTypeToIntDataType = int(stringDataType)
print(type(stringDataTypeToIntDataType))
# conversion of int to string
intDataTypeToStringDataType = str(intDataType)
print(type(intDataTypeToStringDataType))
#conversion of int to float
intDataTypeToFloatDataType = float(intDataType)
print(type(intDataTypeToFloatDataType))

```
# Lists in Python

```python runnable
data = ["apple", "mango", "oranges"]
print(data)
# to find length of list in python
print(len(data))


print("List in Python")
myList = [1, 2, 3, 4, 5, 6, 7, 8, 8, 9]
# will display all items in the list
print(myList)
# will display items at some range
print(myList[1:4])
print(myList[4:6])

# also in reverse direction
print(myList[:-1])
print(myList[4:-1])

# to update the value of specific item
myList[2] = 99
print(myList)

# to add new value at the end
myList.append(1002)
print(myList)
# to remove item
print(myList)
myList.remove(8)  # will remove first occurrence of 8
print(myList)

# to sort list
myList.sort()
print(myList)

# to reverse list
myList.reverse()
print(myList)

abc = ["abc", "Hello", "between"]
# to check if something is in the list or not
print(999 in myList)
print(4 in myList)
print(6 in myList)
print(2 in myList)
print("Hello" in abc)




```
# Tuple in Python

```python runnable
print("Tuple in Python")
myTuple = ("grapes", "banana", "apple", "mango") # simple tuple
print(myTuple)  # to display simple tuple

# to display tuple to some range
print(myTuple[1:4])
print(myTuple)

print(myTuple.count("apple"))
print(myTuple.index("apple"))

# searching in tuple
print("banana" in myTuple)

# we can also concatenate tuple
newTuple = ("oranges", "pineapple")
concatenation = myTuple+newTuple
print(concatenation)

# we can also assign dferent variables to diferent values in tuple
#like this one
a, b, c, e = myTuple
print(a)
print(b)
print(c)
print(e)


# and as we can also return multiple values from function we can store them in tuples
# see below

def tupleValues():
    return (1,2,3,4,5,6,7,8,9)

myNewTuple = tupleValues()
print(myNewTuple)
print(type(myNewTuple))

```
# Set in Python

```python runnable
print("Sets in Python")

newSet = {"apple", "mango", "oranges"}
print(type(newSet))

#to add Value to set
newSet.add("grapes")
print(newSet)

# to remove value from set
newSet.remove("apple")
print(newSet)

# to access using loop
for item in newSet:
    print(item)

# to join two sets
newSet1 = {"Banana", "PineApple"}

afterjoin = newSet.union(newSet1)
print(afterjoin)

# if you want to print specific item in set
print("Apple" in afterjoin)
# False due to case
```

# Dectionary in Python

```python runnable
print("Dictionary in Python")
dict = {"apple": 2, "banana": 3, "grapes": 4, "mango": 5}
# type of dict
print(type(dict))
# to print dict keys and values
print(dict)
# return boolean if it exist or not
print("apple" in dict)
# printing specific item
print(dict["apple"])
# length of dict
print(len(dict))
# update
dict.update({"apple": 5})
print(dict)
#add item
dict["color"] = "red";
print(dict)
# remove item
dict.pop("apple")
print(dict)
# REMOVE LAST ITEM
dict.popitem()
print(dict)
# clear method will clear the dictionary
#----dict.clear()
#----print(dict)
# copy dictionary
dict2 = dict.copy()
print(dict2)


```
# Simple Array in Python

```python runnable
print("Arrays in Python")
array = [1,2,3,4,5,6,7,8,9]
print(array)
```

# While Loop in Python

```python runnable
print("While Loop in Python")
print("While loop in Python")
i = 0
while i<4:
    print(i)
    i+=1

```
# forin Loop in Python

```python runnable
print("forin Loop in Python")
print("For Loop in Python")
fruits = {"apple", "mango", "oranges", "banana", "grapes"}
for items in fruits:
    print(items, " are some fruits for you")
    

```
# Functions in Python

```python runnable
print("Functions in Python")
print("Functions in Python")

# functions which return something
def doSum(value1, value2):
    return value1+value2

# function which does not return something
def doSub(value1, value2):
    print(value1+value2)

print(doSum(4,5))

print(doSub(23,43))

```

# Lambda Functions in Python

```python runnable
print("Lambda Functions in Python")
print("lambda Function in python")

# addition using lambda
doSum = lambda a, b: a+b
print(doSum(2,3))
doSub = lambda a, b: a-b
print(doSub(2,3))
doMultiPly = lambda a, b: a*b
print(doMultiPly(2,3))
doDivision = lambda a, b: a/b
print(doDivision(2,3))

```
# Simple Authentication using Functions in Python

```python runnable
print("Authentication in python")

def welcome():
    print("Welcome Dude")

def error(index):
    if index < 3:
        authentication()
    else:
        print("Out of Moves")

def authentication():
    indexvalue = 0
    pincode = int(input("Pin COde: "))

    if pincode == 1234:
        welcome()
        # print("incorrect Pin Code")
    else:
        indexvalue = indexvalue + 1
        error(indexvalue)

name = input("Name: ")
authentication()
```

# classes and objects in Python

```python runnable
print("Objects and Classes in Python")
class student:
    def __init__(self, name, age):
        self.name = name
        self.age = age


# now we create new instent of student class
std1 = student("de Developer", 23)

print(std1.age)
print(std1.name)

# Another Example

print("classes and objects in python")
class student:
    def __init__(self, name, age):
        self.name = name
        self.age = age

    def display(self):
        print("Name: " + self.name)
        print("Age: " + str(self.age))

std1 = student("de Developer", 23)
print(std1.display())

```
# inheritance in Python

```python runnable
print("Inheritance in Python")

print("inheritance using python")
class Person:
    def __init__(self, Name, Age):
        self.name = Name
        self.age = Age
    def diplayDataOfUser(self):
        print(self.name)
        print(self.age)

class Student(Person):
    pass

std = Student("De Developer", 22)

std.diplayDataOfUser()

print("inheritance using python")
class Person:
    def __init__(self, Name, Age):
        self.name = Name
        self.age = Age
    def diplayDataOfUser(self):
        print(self.name)
        print(self.age)

class Student(Person):
    def __init__(self, name, age):
        Person.__init__(self, name, age)
        # print(self.name)
        # print(self.age)

std = Student("De Developer", 22)

std.diplayDataOfUser()


```
# Exception Handling in Python

```python runnable
print("Exception handling in Python")

try:
    print("de Develiper" + 12)
except:
    print(" some thing went wrong")

```

# File Handling in Python
```python runnable

print("File Handling in Python")

# opening file if exist
try:
    file = open("data.txt", "r")
except:
    print("file not found: ")

# writing to file and creating
try:
    file1 = open("data.txt", "w")
    file1.write("Hey, this is de Developer \n")
    file1.write("You can follow me on Github \n")
    file1.write("Link to my Github is \n")
    file1.write("[github.com/SyabAhmad] \n")
except:
    print("Some Error")

# reading file

try:
    file3 = open("data.txt", "r")
    a = file3.read()
    print(a)
except:
    print("File Not Found")

```

# Advanced usage

If you want a more complex example (external libraries, viewers...), use the [Advanced Python template]https://github.com/SyabAhmad/Python3DaysChallenge
