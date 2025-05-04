## Loops in Python: Palindrome Number Checker

## 🎯 Aim
To write a Python program that checks whether a given number is a **palindrome** using loops.

## 🧠 Algorithm
1. Get input from the user and assign it to a variable `num`.
2. Assign the value of `num` to a temporary variable `temp`.
3. Initialize a variable `rev` to 0 (used to store the reversed number).
4. Use a `while` loop to reverse the digits:
   - While `temp > 0`:
     - `rev = (10 * rev) + temp % 10`
     - `temp = temp // 10`
5. After the loop, compare `rev` with `num`:
   - If equal, print that the number is a palindrome.
   - Else, print that it is not a palindrome.

## 🧾 Program
Add code Here
```
# Step 1: Get input from the user and assign it to a variable num
num = int(input("Enter a number: "))

# Step 2: Assign the value of num to a temporary variable temp
temp = num

# Step 3: Initialize a variable rev to 0 (used to store the reversed number)
rev = 0

# Step 4: Use a while loop to reverse the digits
while temp > 0
```
## Output
```
121 is a palindrome.
```
## Result 
This program successfully checks if the given number is a palindrome using loops!
