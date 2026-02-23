# Experiment-8
#**Aim : Study of For loops in Python **

**Theory:**
- Used to repeat a block of code for each item in a sequence.
- Commonly used with range() to generate numbers.
- Syntax: for variable in sequence:
- Suitable when number of iterations is known.
- Can calculate sums and perform arithmetic operations.
- Nested loops are used for matrices and patterns.
- Helps in matrix display and matrix multiplication.
- Used to generate combinations of values.
- Useful for printing patterns like triangles and pyramids.
- Makes repetitive tasks simple and organized.

  **Algorithms:**

- Print Numbers from 1 to 5
1. StartUse
2. range(1,6)
3. Repeat loop for each number
4. Print the number
5. Stop

- Print Even Numbers from 1 to 10
1. Start
2. Use range(2,11,2)
3. Repeat loop
4. Print each even number
5. Stop

- Sum of First N Natural Numbers
1. Start
2. Initialize total = 0
3. Input value of n
4. Repeat loop from 1 to n
5. Add each number to total
6. Display the sum
7. Stop

- Display 3×3 Matrix (Using Index)
1. Start
2. Define matrix A
3. Repeat outer loop for rows (0 to 2)
4. Repeat inner loop for columns (0 to 2)
5. Print each element A[i][j]
6. Move to next line after each row
7. Stop

Display Matrix (Using Direct Iteration)
1. Start
2. Define matrix A
3. Repeat loop for each row in matrix
4. Print the row
5. Stop

6. Multiplication of Two 3×3 Matrices
1. Start
2. Define matrices A and B
3. Initialize result matrix with zeros
4. Repeat outer loop for rows of A
5. Repeat second loop for columns of B
6. Repeat third loop for multiplication
7. Multiply and add elements to result
8. Print result matrix
9. Stop

- Print All Possible Combinations of Three Digits
1. Start
2. Store three digits in a list
3. Repeat three nested loops (0 to 2)
4. Check condition to avoid repetition
5. Print valid combinations
6. Stop

- Right-Angled Triangle Pattern
1. Start
2. Input number of rows
3. Repeat outer loop from 1 to rows
4. Repeat inner loop from 1 to current row
5. Print *
6. Move to next line
7. Stop

- Pyramid Pattern
1. Start
2. Set number of rows
3. Repeat outer loop from 1 to rows
4. Print spaces (rows - i)
5. Print stars (i times)
6. Move to next line
7. Stop

Conclusion
The for loop in Python is an important control structure used to execute a block of code repeatedly for a fixed number of times. It is simple, efficient, and commonly used with range() for generating sequences. The for loop helps in performing arithmetic operations, calculating sums, working with matrices, generating patterns, and handling repetitive tasks in an organized manner. Thus, it plays a vital role in writing efficient and structured Python programs.
