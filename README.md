# Compiling & running your first program

This project will help you get up to speed with the things you need  create and run C programs. It will explain what is needed and the steps that need to be taken in order to `compile` and `run` your code.

## What is required ?

In order to `compile` and `run` your first C program you will need the following things:

* A plain text editor
* A C compiler

## Basic workflow

*It would be nice to represent the following with a flowchart*

* Source code is written
* File is compiled
* Executable is run


## Which compiler should I use?

Depending on the platform that you are working,you can use one compiler or another. You should be able to compile and run the application regardless of the compiler you are using.

### Windows users

You've got several options:

* Visual Studio
* MinGW

### Unix / Linux users

* Gcc

### MAC OSX

* *XCode?*

## Writing the code

C programs are text files that happen to have the '.c' extension.

For our first program, let's create a file called `hello_world.c` and type the following:

```c
#include <stdio.h>

int main()
{
    printf("hello, world\n");
}
```

## Compiling the code

*explanation of the compilation process*

## Running the code

*We could add a screenshot of the result that they should get*
Success!

## Problems?

*What about adding this section explaining that if they run into problems trying to follow this project they should create an issue so it can get addressed in future versions of the project?*
