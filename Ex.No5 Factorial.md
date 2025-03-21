# Ex.No: 5   Logic Programming – Factorial of number   
### DATE: 21/3/25                                                                           
### REGISTER NUMBER : 212222043003
### AIM: 
To  write  a logic program for finding the factorial of given number using SWI-PROLOG. 
### Algorithm:
1. STEP 1: Start the program
2. STEP 2:  Write a rules for finding factorial of given program in SWI-PROLOG.
3.   a)	factorial of 0 is 1 => written as factorial(0,1).
4.   b)	factorial of number greater than 0 obtained by recursively calling the factorial    function.
5. STEP 3: Run the program  to find answer of  query.
6. STEP 4: Stop the program.

### Program:
```
factorial(0,1).
factorial(A,B) :-  
       A > 0, 
       C is A-1,
       factorial(C,D),
       B is A*D.
  ```


### Output:


![IMG_5990](https://github.com/user-attachments/assets/f9b3d207-49b9-4d95-9e99-556eda63c7be)

### Result:
Thus the factorial of given number was found by logic programming. 
