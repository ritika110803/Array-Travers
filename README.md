# Array Traversal in C

This project demonstrates how to traverse (iterate through) an array in the C programming language using a `for` loop.

## 📌 Description

The program:
- Declares an integer array of size 5
- Stores predefined values in the array
- Uses a `for` loop to access and print each element
- Displays the elements on the console

## 💻 Source Code

```c
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
