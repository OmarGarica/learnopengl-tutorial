# learnopengl-tutorial

## Setup 

I have found a way to succefully set up the learnopengl code on Mac
I have 3 main files and directories in my set up

* Makefile 
* src
* bin

### src 

In src directory I admit its pretty convoluted 
I have an include directory and glad.c file and the glad binary as glad.o 

In include I have all the libs neccessary for building the project 
I have edited all the .h files in include so that all headers are called properly 

## Running the code 
I run my makefile using the make command
```
make && cd bin && ./myApp && cd ..
```

## Goals
My first goal for this repo is to document my C++/C/OpenGL journey through the book
'Learn OpenGL'.
My second goal for this repo is to have a repo available to run openGL code out of 
the box without the struggle of bulding on Mac
