# 0x0F-function_pointers

## 0-print_name.c
> A function that prints a name.
## 1-array_iterator.c
> A function that executes a function given as a parameter on each element of an array.
## 2-int_index.c
> A function that searches for an integer.
## function_pointers.h
> Header file contains function prototypes of tasl 0 to task 2.
## *Task 3*
> A program that performs simple operations.
> - Usage: ``` calc num1 operator num2 ```.
> - Assumes ``` num1 ``` and ``` num2 ``` are integers, ``` atoi ``` function is used to convert them from the string input to ``` int ```.
> - ``` operator ``` is one of the following:
> * ``` + ``` : addition.
> * ``` - ``` : subtraction.
> * ``` * ``` : multiplication.
> * ``` / ``` : division.
> * ``` % ``` : modulo.
> The program prints the result of the operation followed by a new line.
> - Assumes the result of operation can be stored in an ``` int ```.
> - If the number of arguments is wrong, program prints ``` Error ``` followed by anew line, and exits with a status of ``` 98 ```.
> - If the ``` operator ``` is none of the above, program prints ``` Error ``` folllowed by a new line and exits with a status of ``` 99 ```.
> - If the user tries to divide ( ``` / ``` or ``` % ``` ) by ``` 0 ```, program prints ``` Error ``` followed by a new line and exits with a status of ``` 100 ```.
