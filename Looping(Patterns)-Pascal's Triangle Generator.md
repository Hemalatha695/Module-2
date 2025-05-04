# 🔺 Looping(Patterns)-Pascal's Triangle Generator in Python

This project demonstrates a simple Python program to generate **Pascal’s Triangle**, where the number of rows is provided by the user.

---

## 🎯 Aim

To write a Python program that generates **Pascal's Triangle** using numbers. The number of rows is accepted from the user.

---

## 🧠 Algorithm

1. Start the program.
2. Input the number of rows from the user.
3. Loop from 0 to the number of rows.
4. For each row:
   - Print appropriate spaces to shape the triangle.
   - Compute values using the formula:  
     \[
     C(n, k) = \frac{n!}{k!(n-k)!}
     \]
5. Print all rows of Pascal’s Triangle.
6. End the program.

---

## 🧪 Program
Add Code Here
```
import math

# Step 2: Input the number of rows from the user
rows = int(input("Enter the number of rows for Pascal's Triangle: "))

# Step 3: Loop through each row to generate Pascal's Triangle
for n in range(rows):
    # Step 4: Print spaces to shape the triangle
    print(" " * (rows - n - 1), end="")

    # Step 4: Compute and print the values for the current row
    for k in range(n + 1):
        # Compute C(n, k) using factorial formula
        value = math.comb(n, k)  # math.comb(n, k) is more efficient and cleaner
        print(value, end=" ")

    # Move to the next line after each row
    print()
```


## Sample Output
```
    1 
   1 1 
  1 2 1 
 1 3 3 1 
1 4 6 4 1
```

## Result
This program successfully generates Pascal’s Triangle based on the number of rows specified by the user!
