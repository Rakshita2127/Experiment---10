# Experiment-10

## Program 1
### Aim: 
Declare and initialize pointers of different data types and print the following values (Repeat for float and char data types)
### Software used: 
Visual Studio Code
### Theory:
A variable that stores the address of another variable in memory is called a pointer in C++. When declaring a pointer, an asterisk (*) and the data type of the variable to which the pointer will point must be provided. Pointers must be initialized by being given the memory address of a variable using the address-of operator (&). Pointers are necessary for dynamic memory management, efficient function parameter passing, and arrays.
### Output:
![image](https://github.com/user-attachments/assets/cf4f62cf-05f3-4f4c-9a9e-e0dc37ef4948)

### Conclusion:
We learned about pointers in C++. 

## Program 2
### Aim: 
Access array using pointer and without using pointer variable
### Software used: 
Visual Studio Code
### Theory:
In C++, pointers can be used to access elements of an array. When an array is declared, the name of the array acts as a pointer to the first element of the array. Using pointer arithmetic, you can traverse the array by incrementing the pointer to point to subsequent elements. This method is useful in cases where you want to process arrays in functions or manage dynamic memory.
### Output:
![image](https://github.com/user-attachments/assets/8dca1c2d-8bff-40ce-8d72-5408dae03a33)

### Conclusion:
We learned how pointers work in arrays. 

## Program 3
### Aim: 
Swap the numbers using call-by-value
### Software used: 
Visual Studio Code
### Theory:
A replica of the real arguments is sent to the function upon call in the call-by-value mechanism. The original variables outside the function are unaffected by changes made to the parameters inside the function since the function operates with these copies. Call by value can be slow when passing huge data structures, but it is straightforward and safe because it guards against unintentional changes to the original data.
### Output:
![image](https://github.com/user-attachments/assets/9727b921-3ef1-46d0-9743-f2c53962a442)

### Conclusion:
We learned about the call-by-value operation in C++. 

## Program 4
### Aim: 
Swap the numbers using call-by-reference. 
### Software used: 
Visual Studio Code
### Theory:
The call-by-reference mechanism passes references, or pointers, to the original variables to the function rather than a copy of the arguments. The initial variables will be directly impacted by any modifications made to the function's parameters. Large data structures benefit from this method's increased efficiency, which also lets functions change the caller's variables. However, care must be taken to prevent unexpected consequences.
### Output:
![image](https://github.com/user-attachments/assets/7221e74e-1b01-4cb2-871b-adb9dd6b4839)

### Conclusion:
We learned about the call-by-reference in C++. 
