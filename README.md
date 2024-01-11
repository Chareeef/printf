# Printf Project

## Project Overview

Welcome to the custom `printf` project! In this project, we aim to implement a personalized version of the `printf` function in C. This project is an excellent opportunity to deepen your understanding of formatting, string manipulation, and memory management in the C programming language.

## Getting Started

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/Chareeef/printf.git
   ```

2. **Navigate to Project Directory:**
   ```bash
   cd printf
   ```

3. **Compile the Code:**
   ```bash
   gcc -Wall -Werror -Wextra -pedantic *.c -o printf
   ```

## Usage

To use our custom `_printf` function, include the provided header file in your C program:

```c
#include "main.h"
```

Then, you can use the `_printf` function just like the standard `printf`:

```c
int main(void)
{
    _printf("Hello, %s!\n", "World");
    _printf("This is a number: %d\n", 42);
    return 0;
}
```

## Supported Format Specifiers

Our custom `_printf` currently supports the following format specifiers:

- `%s` for strings
- `%c` for characters
- `%d` for integers
- `%i` for integers
- `%u` for unsigned integers

Happy coding! If you have any questions or need assistance, don't hesitate to reach out.