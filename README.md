# Algorithms & Data Structures 
[![Status](https://img.shields.io/badge/status-deprecated-red)](#)
[![Purpose](https://img.shields.io/badge/purpose-educational%20%2F%20history-blue)](#)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](./LICENSE)
[![Year](https://img.shields.io/badge/year-2018-lightgrey)](#)

> **This project is no longer maintained.**
> It is kept as an educational subproject for reference and historical purposes. 
> The code may be incomplete, outdated, or contain educational simplifications.

A course on algorithms and data structures. Solving problems and implementing various algorithms and data structures in the C programming language.

## C Language Syntax

```c
main // entry point of the program
<> // path where the compiler is located
"" // path relative to the project folder
#ifndef // if not yet defined
#define // define
#endif // end of if
#define true 1 // replaces all true with ones
void // a function that returns nothing
\n // new line
\t // tab
\\ // backslash
\0 // end of string
%d // int (value)
%s // string
%c // char (characters)
%f // float
%lf // long float (double)
%.2f // number of digits after the decimal point
%05d // total number of digits of an integer (padded with zeros)
%% // the % character itself
%p // pointers (&a - address / int * pointer; pointer = &a / *a - dereference, i.e. access the variable the pointer refers to)
unsigned // unsigned
int: 4 bytes // -2147000000…2147000000
unsigned int: 4 bytes // 0...4294000000
short: 2 bytes // -32768…+32767
double (long float): 8 bytes // mantissa, exponent, and sign
char: 1 byte // -128…+127
unsigned char: 1 byte // 0…+255
char sir[25] = "string"
char* sir = "string"
puts(sir) // print a string
gets() // read a string from the console
strcat(sir, name) // concatenation (joining strings)
strlen() // number of characters in a string
isalpha() // returns true if the character is alphabetic
isdigit() // checks for a decimal digit
isspace() // checks for a space
isupper() // checks for uppercase
islower() // checks for lowercase
toupper() // convert to uppercase
tolower() // convert to lowercase
atoi() // convert to an integer value
atof() // convert to a float value
fopen() // returns a pointer to a memory address (r - read, w - write, a - append, rb, wb, ab)
fprintf() // write to a file
fscanf() // read a formatted value from a file
fclose() // close a file
feof() // returns zero if the end of the file has not been reached
? "true" : "false" // ternary operator, returns a value based on the condition
break // stop the loop execution
continue // stop the current loop iteration, pass control to the loop's logical construct
malloc() // allocate (reserve) memory
calloc(number of elements, size) // clear memory before allocation
sizeof() // returns the size of variables in bytes
free() // free memory
realloc() // change the memory size
exit() // immediately terminate the program and free memory
int * area = (int*) malloc (sizeof(int) * 10) = int area [10] // almost the same thing
'\0' // end of string
/*  */ // comment out
& // and
| // or
! // not
^ // exclusive or
««  »» // shifts
4%2 // remainder of dividing 4 by 2
++ // increment, increases by 1
-- // decrement, decreases by 1
> // greater than
< // less than
>= // greater than or equal to
<= // less than or equal to
== // equality check
&& // and (both true)
|| // or (at least one true)
! // not (false)
^ // exclusive or (when they differ)
^= // xor assignment
break // exit the loop
continue // skip
exit // exit the program
int array1[number of elements] array1[0] = 9; / {0, 2 , 4} // array
#include <stdlib.h> srand(time(NULL)) // random number generator
```