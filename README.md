- [English](#english)
- [Português](#português)

# English

# ft_printf - 42

This project, ft_printf, is part of the curriculum at School 42. The goal of this project is to recreate the functionality of the standard printf function in C, allowing for formatted output to the standard output (stdout) or a specified file descriptor.

## Table of Contents

- [Functionality](#functionality)
- [How to Use](#how-to-use)
- [Building](#building)

## Functionality

The `ft_printf` function works similarly to the standard printf function in C. It accepts a format string containing format specifiers and optional arguments, and it prints the formatted output according to the specified format. The function supports basic format specifiers like `%s`, `%d`, `%c`, `%f`, `%x`, `%p`, as well as flags, width, precision, and length modifiers.

## How to Use

To use the `ft_printf` function in your project, follow these steps:

1. Clone the ft_printf repository:
   ```sh
   git clone git@github.com:rofnavarro/42-ft_printf.git
   cd ft_printf
   ```

2. Include the header file `ft_printf.h` in your code:
   ```c
   #include "ft_printf.h"
   ```

## Building

The ft_printf project includes a `Makefile` that automates the compilation process. You can use the following commands:

- `make`: Compile the library.
- `make clean`: Remove object files.
- `make fclean`: Remove object files and the library file.
- `make re`: Re-compile the library.

***

# Português

# ft_printf - 42

Este projeto, ft_printf, faz parte do currículo da Escola 42. O objetivo deste projeto é recriar a funcionalidade da função printf padrão em C, permitindo a saída formatada para a saída padrão (stdout) ou um descritor de arquivo específico.

## Sumário

- [Funcionalidade](#funcionalidade)
- [Como Usar](#como-usar)
- [Compilação](#compilação)

## Funcionalidade

A função `ft_printf` funciona de forma semelhante à função printf padrão em C. Ela aceita uma string de formato contendo especificadores de formato e argumentos opcionais, e imprime a saída formatada de acordo com o formato especificado. A função suporta especificadores de formato básicos como `%s`, `%d`, `%c`, `%f`, `%x`, `%p`, além de flags, largura, precisão e modificadores de comprimento.

## Como Usar

Para usar a função `ft_printf` em seu projeto, siga estas etapas:

1. Clone o repositório ft_printf:
   ```sh
   git clone git@github.com:rofnavarro/42-ft_printf.git
   cd ft_printf
   ```

2. Inclua o arquivo de cabeçalho `ft_printf.h` em seu código:
   ```c
   #include "ft_printf.h"
   ```

## Compilação

O projeto ft_printf inclui um `Makefile` que automatiza o processo de compilação. Você pode usar os seguintes comandos:

- `make`: Compila a biblioteca.
- `make clean`: Remove os arquivos de objeto.
- `make fclean`: Remove os arquivos de objeto e o arquivo da biblioteca.
- `make re`: Recompila a biblioteca.
