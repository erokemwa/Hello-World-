# Hello, World!

**What is C Language ?**

C is a type of computer language that allows programmers to write instructions that a computer can understand and execute. It was created in the 1970s and is used to build software and computer systems that require high-performance and low-level access to hardware. It is a widely used language that has influenced many other programming languages.

---

**Who are Dennis Ritchie, Brian Kernighan and Linus Torvalds ?**

1)- Dennis Ritchie was an American computer scientist who is best known for developing the C programming language and for his work on the UNIX operating system. He worked at Bell Labs and was awarded the Turing Award in 1983 for his contributions to computer science.

2)- Brian Kernighan is also an American computer scientist who worked at Bell Labs and is known for his work on the development of the C programming language and the UNIX operating system. He is the co-author of the book "The C Programming Language," which is still widely used as a reference for C programmers.

3) -Linus Torvalds is a Finnish software engineer who is best known for creating the Linux operating system, which is based on the UNIX operating system. He created the first version of Linux in 1991 and has been the chief architect and coordinator of the project ever since.

---

**What is the gcc command ?**

`gcc` is a command-line compiler for C and C++ programming languages. It is part of the GNU Compiler Collection, which is a suite of compilers and tools for a variety of programming languages.

The `gcc` command is used to compile and link C or C++ source code files. It can take one or more source code files as input and generate an executable file as output. `gcc` supports many different options that can be used to customize the compilation process, including options for optimizing the code, specifying the target platform, and linking with libraries.

```bash
**gcc -o hello_maya hello_maya.c**
```

> When compiling a C program with GCC (GNU Compiler Collection), the default program name is "a.out". This means that if you compile a C program without specifying an output file name, the resulting executable file will be named "a.out".
> 

---

**What is an entry point ?**

In C programming, the term "entry point" refers to the starting point of program execution. Typically, the entry point is the "main" function, which is where the program starts running. The main function is a special function in C, and it must return an integer value. It is where the program's logic is implemented, and it may call other functions to perform specific tasks. When a C program is compiled, the machine code corresponding to the main function's instructions is loaded into memory, and the processor begins executing instructions at the memory address of the main function.

**How does the main function influence the return value of the program ?**

In C programming, the return value of the main function influences the exit status of the program. A return value of 0 indicates success, while a non-zero value indicates an error occurred.

---

**Printing text :**

In C programming, there are three functions that can be used to print text to the console: `printf`, `puts`, and `putchar`.

1. `printf` - This function is used to print formatted text to the console. It allows you to include placeholders in the string that are replaced with values at runtime. Here's an example:

```c
#include <stdio.h>

int main() {
   int num = 6;
   printf("The value of num is %d\n", num);
   return 0;
}
```

 2. `puts` - This function is used to print a string to the console. It is simpler than printf and is useful for printing simple messages. Here's an example:

```c
#include <stdio.h>

int main() {
   puts("Hello, friends of Maya!");
   return 0;
}
```

1.  `putchar` - This function is used to print a single character to the console. It can be useful when you need to print individual characters. Here's an example:

```c
#include <stdio.h>

int main() {
   putchar('M');
   return 0;
}
```

---

**The sizeof operator :**

In C programming, you can use the unary operator "sizeof" to determine the size of a specific data type in bytes. The syntax for using the sizeof operator is as follows:

```c
sizeof(datatype)
```

---

**How to find the right header to include in your source code when using a standard library function ?**

- Check the function's documentation to determine which header file contains the function's declaration.
- Use the header files that match the function's category. Functions related to a specific category, such as input/output or string handling, are typically declared in specific header files.
- Check the compiler error message to determine which header file you need to include. The error message will often include the name of the missing function and the name of the header file that declares it.
- Use Google to look up the function's name and the phrase "header file" if you're still unsure which header file to include.

Source: https://roasted-puppet-dda.notion.site/Hello-World-e7472434a63e46538c8b82d6e972768d
