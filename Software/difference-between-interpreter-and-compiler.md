# What's the difference between interpreter and compiler?

|Interpreter|
|:-----|
|Translates program one statement at a time.|
|No Intermediate Object Code is Generated.|
|Memory Requirement is Less.|
|Conditional Control Statements are Executes slower.|
|Continues translating the program until the first error is met, in which case it stops. Hence debugging is easy.|
|Programming language like Python, Ruby use interpreters.|

|Compiler| 
|:-----|
|Scans the entire program and translates it as a whole into machine code.|
|Intermediate Object Code is Generated.|
|Memory Requirement is More.|
|Conditional Control Statements are Executes faster.|
|It generates the error message only after scanning the whole program. Hence debugging is comparatively hard.|
|Programming language like C, C++ use compilers.|

We generally write a computer program using a high-level language. A high-level language is one which is understandable by us humans. It contains words and phrases from the English (or other) language. But a computer does not understand high-level language. It only understands program written in 0's and 1's in binary, called the machine code. A program written in high-level language is called a source code. We need to convert the source code into machine code and this is accomplished my compilers and interpreters. Hence, a compiler or an interpreter is a program that converts program written in high-level language into machine code understood by the computer.

