## Aim: Study of For loop in python

## Theory:
In Python, a for loop is used to repeatedly run a block of code, once for each item in a sequence (such as a list, tuple, string, dictionary, set, or range).  
A series of numbers is produced by the range() function.    
Break: Stops the loop completely.    
Continue: Skips the current iteration.  
Multiplying two 3x3 Matrix:
for i in range(3):          # rows of a  
  for j in range(3):        # rows of b    
    for k in range(3):    
      result[i][j] += a[i][k] * b[k][j]  
for row in result:  
  print(row)  

## Algoritm:
1: DISPLAY NUMBERS FROM 1 TO 5 USING FOR LOOP

Start
Initialize a for loop to iterate from 1 to 5 using range()
Print the value of the loop variable in each iteration
Repeat until all values in the range are completed
Stop

2: PRINT ODD NUMBERS FROM 1 TO 10 USING FOR LOOP

Start
Initialize a for loop using range from 1 to 10 with step value 2
In each iteration, display the value of the loop variable
Repeat until the loop completes all values in the range
Stop

3: PRINT EVEN NUMBERS FROM 1 TO 10 USING FOR LOOP

Start
Initialize a for loop using range from 2 to 10 with step value 2
In each iteration, display the value of the loop variable
Repeat until all values in the range are completed
Stop

4: FIND THE SUM OF FIRST N NATURAL NUMBERS USING FOR LOOP

Start
Input a number n from the user
Initialize a variable total with value 0
Initialize a for loop from 1 to n
Add the current value of the loop variable to total
Repeat until the loop completes
Display the sum stored in total
Stop

5: DISPLAY ELEMENTS OF A 3×3 MATRIX USING NESTED FOR LOOPS

Start
Create a 3×3 matrix with elements arranged in rows and columns
Initialize an outer loop to iterate through rows (0 to 2)
Inside it, initialize an inner loop to iterate through columns (0 to 2)
Display the element at position A[i][j]
Repeat the inner loop for all columns of a row
Move to the next line after completing each row
Repeat until all rows are displayed
Stop

6: MATRIX MULTIPLICATION USING NESTED FOR LOOPS

Start
Create two 3×3 matrices A and B
Create a result matrix initialized with zeros
Use an outer loop to iterate through rows of matrix A
Use a second loop to iterate through columns of matrix B
Initialize a third loop to perform multiplication of corresponding elements
Multiply elements A[i][k] and B[k][j] and add the result to Result[i][j]
Repeat the third loop for all values of k
Repeat steps 5 to 8 for all columns
Repeat steps 4 to 9 for all rows
Display the resulting matrix
Stop

7: PRINT ALL POSSIBLE COMBINATIONS OF THREE DIGITS

Start
Initialize three digits and store them in a list
Use the first loop to select the first digit
Use the second loop to select the second digit
Use the third loop to select the third digit
Check that all three selected digits are different
If all digits are different, display the combination
Repeat until all possible combinations are generated
Stop

8: PRINT AN INVERTED RIGHT-ANGLED TRIANGLE PATTERN

Start
Initialize a for loop to run from 5 down to 1
In each iteration, print the symbol “*” repeated i times
Move to the next line after each iteration
Repeat until the loop ends
Stop

9: PRINT A PYRAMID STAR PATTERN

Start
Set the number of rows for the pyramid
Initialize a for loop from 1 to the number of rows
Print spaces equal to (rows − current row number)
Print the symbol “* ” repeated equal to the current row number
Move to the next line after each iteration
Repeat until all rows are printed
Stop

## Conclusion:
Hence for loop was used in python and programs were done using it.
