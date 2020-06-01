# Knowledge Test

## 1 Describe one difference between compliers and interpreters.
Compilers convert the code to byte code, then that code gets executed. Since the conversion is already done, the byte code is faster to execute.
Interpreter directly executes the instructions in the source code, line by line, as a result is slow.

## 2 Name one high level language which uses compliers and one that uses interpreters.
Java uses compiler, whereas Python uses Interpreter

## 3 Write an algorithm for finding a number from a file which has sorted numbers. (Assume you have functions to read the file line by line and one number is written per line)
```python
def findNumber(int num):
  file = open('fileWithNums.txt') # Open the file
  lines = file.readLines() # Get all the lines
  count = 0
  for line in lines:
      count++
      if(line == num)
        print("Input number {} found at line #{} in the given file".format(num, count))
        break;
```
## 4 Write a function that takes name of the person running the program and prints "Hey there <Name> !" [Hint: Try str = input("Whats your name ? ") ]

```python
   
def hello()
  name = input("Please enter your name -")
  print("Hello there, " + name)
 ```   
## 5 Write a function which prints cubes of all values from 1 to 20
```python
def printCube():
  for i in range(1, 21): 
    print(i**3)
```

## 6 Write a function that prints all numbers from 1 to 100 that are divisble by both 3 and 5
```python
def printNum():
  for i in range(1, 101): 
    if (i%3 and i%5 == 0):
      print(i)
```
## 7 Write the output of the expression 2.0 * 5 / 1 - 4 
6.0

## 8 Execute the following line and answer the questions
n = input("Please a select a number between 1 and 5")

### a. Whats the data type of n ?
type(n)
str

### b. Whats happens when you do n + 5
TypeError: must be str, not int

### c. Change the line to say n = exec(input("Please a select a number between 1 and 5")), now whats the data type of n ?
NoneType
