# Lambda Function in Python: Addition of Two Numbers

## 🎯 Aim
To write a Python program that defines a **lambda function** which takes two arguments `a` and `b`, and returns their sum.

## 🧠 Algorithm
1. Get two integer inputs from the user.
2. Use a **lambda function** to define a function `f` that returns `a + b`.
3. Call the function with the user inputs and print the result.

## 🧾 Program
Add code here
```
# Step 1: Get two integer inputs from the user
a = int(input("Enter the first number: "))
b = int(input("Enter the second number: "))

# Step 2: Define a lambda function to return the sum of a and b
f = lambda a, b: a + b

# Step 3: Call the function with the user inputs and print the result
result = f(a, b)
print(f"The sum of {a} and {b} is:", result)
```


## Output
```
The sum of 5 and 8 is: 13
```
## Result
This program successfully defines and uses a lambda function to compute and print the sum of two numbers based on user input.
