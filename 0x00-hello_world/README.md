# 0x00. C - Hello, World


Sure, here are the answers to your questions:

Why C programming is awesome

C is a powerful and versatile programming language that is used to create a wide variety of applications. It is a low-level language, which means that it has a close relationship with the hardware, making it very efficient. C is also a very portable language, meaning that code written in C can be easily ported to other platforms.

Who invented C

C was invented by Dennis Ritchie at Bell Labs in the early 1970s. Ritchie was inspired by the programming language B, which was developed by Ken Thompson. C was designed to be a more powerful and portable language than B.

Who are Dennis Ritchie, Brian Kernighan and Linus Torvalds

Dennis Ritchie (1941-2011) was an American computer scientist who invented the C programming language. He also co-developed the Unix operating system.
Brian Kernighan (born 1942) is a Canadian computer scientist who is known for his work on the C programming language. He co-authored the book "The C Programming Language" with Dennis Ritchie.
Linus Torvalds (born 1969) is a Finnish software engineer who is the creator of the Linux kernel. Linux is a free and open-source operating system that is based on the C programming language.
What happens when you type gcc main.c

When you type gcc main.c, the following steps happen:

The gcc compiler first preprocesses the C source code, which means that it removes comments and expands macros.
The preprocessed code is then compiled into assembly language.
The assembly language is then converted into machine code.
The machine code is linked with other libraries to create an executable file.
What is an entry point

An entry point is the first instruction that is executed when a program starts running. In C, the entry point is always the main function.

What is main

The main function is the most important function in a C program. It is the function that is called when the program starts running. The main function must return an integer value, which indicates the success or failure of the program.

How to print text using printf, puts and putchar

There are three main ways to print text in C:

printf() is a versatile function that can be used to print a variety of data types, including strings, integers, and floats.
puts() is a simple function that can be used to print a string.
putchar() is a low-level function that can be used to print a single character.
How to get the size of a specific type using the unary operator sizeof

The unary operator sizeof can be used to get the size of a specific type. For example, the following code will print the size of an integer:

C
int i;

printf("The size of an integer is %d bytes\n", sizeof(i));
Use code with caution. Learn more
How to compile using gcc

To compile a C program using gcc, you can use the following command:

gcc main.c -o main
This command will compile the C source code file main.c and create an executable file called main.

What is the default program name when compiling with gcc

The default program name when compiling with gcc is a.out. However, you can specify a different program name by using the -o option. For example, the following command will compile the C source code file main.c and create an executable file called my_program:

gcc main.c -o my_program
What is the official C coding style and how to check your code with betty-style

The official C coding style is defined by the C89 standard: https://en.wikipedia.org/wiki/C89. You can check your code for compliance with the C89 standard using the betty-style tool. To use betty-style, you can run the following command:

betty-style main.c
This command will check the C source code file main.c for compliance with the C89 standard.

How to find the right header to include in your source code when using a standard library function

When you are using a standard library function in your C code, you need to include the header file that defines the function. You can find the right header file by looking