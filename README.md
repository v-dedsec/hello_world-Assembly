# Assembly "Hello, World!" Program

This repository contains an assembly language program that prints "Hello, World!" to the standard output. The program is written for the x86-64 architecture using Intel syntax.

## Requirements

- **NASM (Netwide Assembler)**
- **GCC (GNU Compiler Collection)**

## Instructions

### 1. Install NASM

If you haven't installed NASM, you can do so using your package manager. For example, on Debian-based systems (like Ubuntu), use:

```sh
sudo apt-get install nasm

nasm -f elf64 asem.s -o asem.o

gcc -o asem asem.o -nostdlib -static

./asem
