# Pair Group Project: _printf.c

## Group Members

- Group Member One: [Ofori Gyimah Rabbi](https://github.com/oforigyimah)
- Group Member Two: [Anthony Amoah](https://github.com/anthony4m)


## Overview

This project is our own implemented version of the c standard library function `printf()`.
This version is called `_printf()`, which take a format string and and a variable number of arguments and prints the formatted string to the standard output.

## Usage

must include the header file `main.h` to use and call the function with a format string and any aditional arguments a needed.

```c
#include "main.h"

int main(void)
{
	char name[] = "Gregory	
	_printf("Hello, %s!\n", name);
	return (0);
}

```
output
```c
Hello, Gregory!
