1. 3
   At line 12, "3" prints. 3 is the var that iterates through the array, and there are 3 elements in the array.
2. 150
   At line 13, "150" prints. The discounted price is half of the element in the array that is sent in, and the last element that is checked is 300. Half of 300 is 150, so 150 is printed.
3. 150
   At line 14, "150" prints. The value of 150 is multiplied by 100 and rounded to the nearest integer, and then divided by 100, yielding 150 again.
4. [50,100,150]
   The initial array sent in is [100, 200, 300]. The for loop iterates through the area, and adds prices that are 50% of the original values into discounted. Discounted is then returned, so it will return these values.
5. The code has an error.
   i is a let, and is only defined within the block of the for loop. Attempting to access it outside the block will throw an error.
6. The code has an error.
   discountedPrice is a let, and is only defined within the block of the for loop. Attempting to access it outside the block will throw an error.
7. 150
   At line 14, "150" prints. The value of 150 is multiplied by 100 and rounded to the nearest integer, and then divided by 100, yielding 150 again. The let is defined within the same block as this print statement, so there will not be an error.
8. [50,100,150]
   The initial array sent in is [100, 200, 300]. The for loop iterates through the area, and adds prices that are 50% of the original values into discounted. Discounted is then returned, so it will return these values. The return statement is within the same block as the let, so it will be able to access the value without an error.
9. The code has an error.
   i is a let, and is only defined within the block of the for loop. Attempting to access it outside the block will throw an error.
10. 3.
    The length of the array prices is 3 when the const is initialized. The value of a const cannot change, so the statemement will print 3.
11. [50,100,150]
    Const means the variable cannot be reassigned, but it can be manipulated. So, pushing new variables to the array discounted will work, and 50, 100, and 150 will be pushed to it.

## Data Types

12. 5 parts
   A. student.name;  
   B. student["Grad Year"];  
   C. student.greeting();  
   D. student["Favorite Teacher"].name;  
   E. student.courseLoad[0];  


## Basic Operators and Type Conversion

13. 
      A. '32'
         This is because the int 2 is converted to the string "2," then concatenated with the string '3' to form "32."  
      B.  1  
          '3' is converted to the int 3 because – is a mathematical operation, so 3-2=1.  
      C.  3  
            null is converted to 0 for the mathematical operation. 3+0=0  
      D.  '3null'  
            3 is the first data to show up and it is a string, so null is also converted to string form and then concatenated with '3.'  
      E.  4  
            true is converted to 1 to be added to an integer. 1+3=4  
      F.  0
            both false and null are converted to ints, and both convert to 0 0+0=0  
      G. '3undefined'  
            3 is the first data to show up and it is a string, so undefined is converted to string form and then concatenated with '3.'  
      H. NaN  
            - means a mathematical operation occurs. '3' becomes 3, but undefined becomes NaN when converted to an integer.  
14.  
      A. true  
         The number 2 is converted to the number 2 for the comparison, and 2>1 is true.  
      B.  false   
          Both '2' and '12' are evaluated as strings. '2' is greater than '12' because 2 is after 1 in lexographical order.  
      C.  true  
            '2' is converted to a number for the comparison, and 2 == 2 is true.  
      D.  false  
            === is a strict equals operator, and it returns false because 2 and '2' are not the same type.  
      E.  false.  
            true is converted to a number, 1, and 1 == 2 is false.
      E.  4  
            true is converted to 1 to be added to an integer. 1+3=4  
      F.  true.  
            Boolean(2) is converted to 2, as any non 0 and non-null or undefined value does. true === true, so the result is true.  
15. == checks equality with type conversion; for example, ''==false, and 0 == false. However, === is more strict, and compares 2 values without type conversions, so it would return false in situations like the two stated above.


## Loops

16. in js-file, part2-question16.js.


## Functions

17. [2,4,6]  
      doSomething is a callback function, and it is called on every element of the array. The return value is the initial value doubled, and that is the value pushed onto the new array.  

## setInterval(), setTimeout(), clearTimeout()

18. in js-file, part2-question18.js

19. 
    1  
    4  
    3  
    2  
   

