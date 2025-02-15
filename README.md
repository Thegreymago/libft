# Libft

Libft is a custom implementation of the C standard library functions, along with additional utility functions for linked list manipulation. This library is designed to be used in C projects where standard library functions are not available or need to be extended.

## Features

- **Standard Library Functions**: Implementations of common C standard library functions like `ft_strlen`, `ft_memset`, `ft_atoi`, etc.
- **Linked List Utilities**: Functions to manipulate linked lists, such as `ft_lstadd_front`, `ft_lstadd_back`, `ft_lstnew`, and more.

## Setup

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/jguigli/libft.git
   cd libft
   ```

2. **Build the Library**:
   - To compile the standard functions:
     ```bash
     make
     ```
   - To include bonus linked list functions:
     ```bash
     make bonus
     ```

3. **Clean Up**:
   - Remove object files:
     ```bash
     make clean
     ```
   - Remove all generated files:
     ```bash
     make fclean
     ```

4. **Rebuild the Library**:
   ```bash
   make re
   ```

## Usage

- Include the `libft.h` header in your C files:
  ```c
  #include "libft.h"
  ```

- Link the compiled `libft.a` library when compiling your project:
  ```bash
  cc -o my_program my_program.c -L. -lft
  ```
