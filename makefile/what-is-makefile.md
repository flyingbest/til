# Makefile

**A makefile is a file containing a set of directives used with the make build automation tool.** The makefile understands the dependencies between files and tells the compiler to execute the SHELL command sequentially as written in the Makefile (description file).

### Advantages of makefile

- Save time by automating repetitive commands for each file.
- It can quickly identify the dependency structure of the program and is easy to manage.
- Minimize simple iteration and rewrite.

### Configuration of the makefile

- Target : The file to store the result of the execution of the command.
- Dependency : The material needed to create an object file.
- Command : Commands to be executed.
- Macro : How to simplify the code.

### Example Code

```shell
CC = gcc
OBJS = MySocket.o MyClient.o
TARGET = MyClient
 
.SUFFIXES : .c .o
 
all : $(TARGET)
 
$(TARGET): $(OBJS)
	   $(CC) -o $@ $(OBJS)
 
clean :
      rm -f $(OBJS) $(TARGET)
```

