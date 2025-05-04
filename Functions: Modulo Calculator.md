# Functions in Python: Modulo Calculator

## 🎯 Aim
To write a Python program that defines a function which accepts two values and returns their **modulo** using the `%` operator.

## 🧠 Algorithm
1. Define a function called `result` that takes two arguments `a` and `b`.
2. Inside the function, compute the modulo using `a % b`.
3. Print the result of the modulo operation.
4. Get two integer inputs from the user.
5. Call the `result` function with the user-provided values.

## 🧾 Program
Add code Here
```
# Step 1: Define a function called 'result' that takes two arguments a and b
def result(a, b):
    # Step 2: Compute the modulo using the '%' operator
    mod = a % b
    # Step 3: Print the result of the modulo operation
    print(f"The result of {a} % {b} is:", mod)

# Step 4: Get two integer inputs from the user
a = int(input("Enter the first number: "))
b = int(input("Enter the second number: "))

# Step 5: Call the result function with the user-provided values
result(a, b)
**
```
## Output
```
The result of 10 % 3 is: 1
```

## Result
This program successfully calculates and prints the modulo of two numbers based on user input.
