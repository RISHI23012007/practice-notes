---
title: "Internals"
date: 2024-07-19
categories:
---
# Internals
## Parts:
1.**Inside a PC**:There is a power supply,Expansion slot,Hard disks and many more.

2.**MotherBoard**:It is very important for a computer this is where many of important process take place.Parts inside Motherboard:

 i)Back Panel Connectors

 ii)Memory Slots

 iii)Expansion cards 

## Functional Units:

1.**CPU(Central Processing Unit)**:It controls the whole unit.The CPU is also known as  *'Brain of Computer'*.It has two parts :

i)ALU-Algorithm and Logic Unit

ii)Control Unit-Executes the instructions

2.**Memory**:Stores area;Quickly accessible from CPU by '*Bus*'

3.**Hard Disk**:Storage;Not so quickly accessible from CPU.

## Binary Format:
1.Computer accepts only sets of 0's and 1's.

2.As a computer can only understand 0's and 1's.These both numbers are called as *Binary Numbers*.

3.For Example : 4 can be represented as 00000100.

## Execution in a Computer :

1.All the data  and commands related to computation is stored in memory.

2.The commands are bought into CPU for processing by 'BUS'.

3.A **program** is collection of commands.

4.If a command requires data CPU acquires data from memory.
   Then command is executed using the data.


## Assembly Language :

1.The **Binary Language** is also called as **Machine Language** which is difficult to understand.

2.**Assembly Language** is introduced to make things simple for us.

3.It is easier because assembly language addresses data,memory as names.

## OS(Operating System)

1.Main function is to take input from user and store it in appropriate location of memory.

2.After computation of result it displays output to the user.

3.It make the communication between user and computer easier.

4.For Example : **Mac**,**Windows**,**Linux**

## HIGH LEVEL AND LOW LEVEL:

1.Examples of HIGH LEVEL PROGRAMMING LANGUAGES:**_COBOL_**,**FORTRON**,**_C_**

2.Examples of LOW LEVEL PROGRAMMING LANGUAGES :**Assembly and Machine**

Note: For standard header files we use <> and for custom header files we use ""

## Compilers:

1.Translates a C program to machine language.

2.*Clang* is commonly used.

## .I and .S and .O files

### .O
 Is an **object file** that gets created after the compiler compiles your .c file. It contains machine code, but it's not yet an executable program. The linker uses these .o files to create the final executable.

### .S
 A .s file is an assembly language source code file. When you compile a C program, the compiler can generate an assembly code equivalent of your C code, which is typically stored in a .s file. This file can be useful for debugging or understanding what's happening at a lower level in your program.

### .I
 In the context of C programming, a .i file is a preprocessed source file. When you compile a C program, the first step the compiler takes is preprocessing, which includes expanding macros, including header files, and removing comments. The result of this preprocessing step can be saved in a .i file. 

