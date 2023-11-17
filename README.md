# The Monty Program

This is a C implementation of "The Monty Program," a stack program that includes extended opcodes for advanced functionality.

## Table of Contents
- [Overview](#overview)
- [Implementation Details](#implementation-details)
- [Extended Opcodes](#extended-opcodes)
- [Usage](#usage)
- [Compilation](#compilation)
- [Example](#example)
- [Contributing](#contributing)
- [License](#license)

## Overview

"The Monty Program" is a stack-based program implemented in C, extending basic stack operations with advanced opcodes. The source code file `monty.c` defines the stack structure and functions for initializing, pushing, popping, peeking, swapping, adding, and other operations.

## Implementation Details

The stack is implemented using an array and a structure in C. The source code file `monty.c` contains the stack structure and functions for various operations.

## Extended Opcodes

- **push:** Push an element onto the stack.
- **pop:** Pop an element from the stack.
- **pint:** Print integer elements of the stack.
- **swap:** Swap the top two elements of the stack.
- **add:** Add the top two elements of the stack.
- **nop:** No operation; does nothing.

## Usage

To use "The Monty Program" with extended opcodes in your C project:

1. Copy the `monty.c` file into your project directory.
2. Include the Monty header in your source code: `#include "monty.c"`
3. Initialize a stack using `initialize(&stack)`.
4. Write a program using the extended opcodes.

## Compilation

Compile the program using a C compiler, for example:

```bash
gcc -Wall -Werror -Wextra -pedantic -std=c89 *.c -o monty

