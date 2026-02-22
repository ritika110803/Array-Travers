  C Program: Print Array Elements

This is a simple C program that demonstrates how to declare, initialize, and print elements of an integer array using a for loop.

 Description

The program:

* Declares an integer array of size 5
* Initializes the array with values {10, 20, 30, 40, 50}
* Uses a for loop to iterate through the array
* Prints each element to the console

This example is useful for beginners learning about arrays and loops in C.

---

 Source Code

c

#include <stdio.h>

int main() {
    int arr[5] = {10, 20, 30, 40, 50};
    int i;

    printf("Array elements are:\n");

    for(i = 0; i < 5; i++) {
        printf("%d ", arr[i]);
    }

    return 0;
}


---

 How to Compile and Run

 Using GCC

1. Save the file as array.c
2. Open terminal or command prompt
3. Compile the program:


gcc array.c -o array


4. Run the executable:


./array


(On Windows, use array.exe)

---

 Sample Output


Array elements are:
10 20 30 40 50


---

 Concepts Covered

* Arrays in C
* Looping with for
* Printing output using printf
* Basic program structure in C

---
   
