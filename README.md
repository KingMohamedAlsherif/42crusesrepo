# ft_printf

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Supported Conversion Specifiers](#supported-conversion-specifiers)
- [Credits](#credits)
- [License](#license)

## Introduction
`ft_printf` is a custom implementation of the standard C library function `printf`. This project is part of the 42 School curriculum and aims to replicate the functionality of `printf` by formatting and printing data to the standard output. Implementing `ft_printf` provides a deep understanding of variadic functions, parsing, and data formatting in C.

## Features
- Supports various conversion specifiers (e.g., `%c`, `%s`, `%d`, `%x`)
- Handles flags, width, precision, and length modifiers
- Robust error handling and edge case management

## Installation
To use `ft_printf`, clone the repository and compile the source code into your project:

```bash
git clone https://github.com/KingMohamedAlsherif/ft_printf.git
cd ft_printf
make
make clean # clean the .o files
make fclean # clean all the files
make re # clean and remake
