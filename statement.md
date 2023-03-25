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
# Advanced usage

If you want a more complex example (external libraries, viewers...), use the [Advanced Python template]https://github.com/SyabAhmad/Python3DaysChallenge
