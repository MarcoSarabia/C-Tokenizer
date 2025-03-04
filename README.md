# Lab Project: Building a Tokenizer
===================================

# Description
This project involves building a tokenizer in C, which is capable of dividing a string into tokens based on a specified delimiter (e.g., space, tab). Additionally, the tokenizer maintains a history of the user inputs. The tokenizer should be able to process and tokenize strings and also recall and use previous inputs from the history.

The project is implemented in C and uses a state machine for its interface. The user interacts with the program through a simple command-line interface. The tokenizer supports basic string manipulation, dynamic memory allocation, and a history feature that allows users to recall previously entered strings.

The project was originally outlined by Dr. Eric Freudenthal as part of the curriculum for CS 3320 Intro to Computer Architecture at The University of Texas at El Paso.

## Features
- Tokenization: Divides a string into tokens based on spaces or tabs.
- History Management: Maintains a history of previously entered strings and allows the user to recall them (e.g., using !2 to retrieve the second history entry).
- Dynamic Memory Management: Uses malloc, calloc, and free for memory allocation and deallocation.
- Command-line Interface: Simple user interface that accepts input and displays output in the terminal.
- State Transitions: The program reacts to user input and processes commands accordingly.

## Files
The project consists of several source files, header files, and a Makefile for building the project:

- `src/ui.c`: Functions for managing user input.
- `src/tokenizer.c`: The main source code that contains the logic for tokenizing strings and managing history.
- `src/tokenizer.h`: Header file that declares functions for tokenizing strings.
- `src/history.c`: Functions to manage the history of user inputs (linked list of strings).
- `src/history.h`: Header file that declares functions and structs for managing history.
- `Makefile`: The build system for compiling and linking the project.



