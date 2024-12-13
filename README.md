README

This simple C program demonstrates how to define a structure for storing address information in C. The `address` structure contains the following fields:
- `street`: A string to hold the street address (up to 100 characters).
- `state`: A two-character string for the state abbreviation.
- `zip`: An integer to store the zip code.

## Code Overview

```c
#include <stdio.h>
#include <string.h>

int main() {
    struct address {
        char street[100];
        char state[2];
        int zip;
    };

    struct address myAddress;
    int i;

    // Example of setting the address (uncomment and modify as needed)
    // strcpy(myAddress.street, "810 Thornton St SE");
    // strcpy(myAddress.state, "WA");
    // myAddress.zip = 98002;

    return 0;
}
