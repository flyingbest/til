# What's the difference between interpreter and compiler?

|-|Interpreter|
|:-----|:-----|
|1.|Translates program one statement at a time.|
|2.|No Intermediate Object Code is Generated.|
|3.|Memory Requirement is Less.|
|4.|Conditional Control Statements are Executes slower.|
|5.|Continues translating the program until the first error is met, in which case it stops. Hence debugging is easy.|
|6.|Programming language like Python, Ruby use interpreters.|

|-|Compiler| 
|:-----|:-----|
|1.|Scans the entire program and translates it as a whole into machine code.|
|2.|Intermediate Object Code is Generated.|
|3.|Memory Requirement is More.|
|4.|Conditional Control Statements are Executes faster.|
|5.|It generates the error message only after scanning the whole program. Hence debugging is comparatively hard.|
|6.|Programming language like C, C++ use compilers.|

We generally write a computer program using a high-level language. A high-level language is one which is understandable by us humans. It contains words and phrases from the English (or other) language. But a computer does not understand high-level language. It only understands program written in 0's and 1's in binary, called the machine code. A program written in high-level language is called a source code. We need to convert the source code into machine code and this is accomplished my compilers and interpreters. Hence, a compiler or an interpreter is a program that converts program written in high-level language into machine code understood by the computer.

