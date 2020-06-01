# Small coding projects

## 1. Write a program to convert temperature that user enters in Celius to Farenhite (No i dont expect you to know the formulae from the top of your head, F = 9/5 C + 32)

```python
def convertTemperature(temp_celcius):
  temp_farenhite = (9/5 * temp_celcius) + 32
  return temp_farenhite
```

## 2. Write a program for a calculator which can perform addition, subtraction, multiplication, divition and exponential. Take the numbers and the operatation to be performed from the user. 

```python
def calculator(num1, num2, operator):
  if operator == '+':
    return num1 + num2
  elif operator == '-':
    return num1 - num2
  elif operator == '*':
    return num1 * num2
  elif operator == '/':
    return num1/num2
  elif operator == '**':
    return num1**num2
  else:
    print("Please input a valid operator")

```
