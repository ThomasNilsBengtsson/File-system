# File System Simulation Project

# Introduction

This project is a laboratory assignment. The objective is to develop a simple file system using C++ that simulates fundamental operations of a real file system, inspired by the FAT (File Allocation Table) system. The implementation follows C++11 standards and runs on Ubuntu Linux.

## Features

The file system provides the following functionality:

### Basic file operations:

Format disk

Create, read, and delete files

List directory contents

### Advanced file operations:

Copy and move files

Append content from one file to another

Directory management:

Create directories

Navigate using cd and view the current path

Hierarchical directory support

Access rights management:

Set and modify access permissions (read, write, execute)

## Installation

To set up and run the project, follow these steps:

### Clone the repository:

git clone https://github.com/ThomasNilsBengtsson/file-system.git
cd filesystem-lab

### Compile the code using the provided Makefile:

make all

Run the file system shell:

./filesystem

Usage

After running the program, the following commands can be used:

File Operations:

format - Initializes the file system

create <filename> - Creates a new file

cat <filename> - Displays file contents

ls - Lists directory contents

Directory Operations:

mkdir <dirname> - Creates a new directory

cd <dirname> - Changes to the specified directory

pwd - Prints the current directory path

Permission Management:

chmod <accessrights> <filename> - Changes file access rights

## Project Structure

The project contains the following key files:

fs.h and fs.cpp: Implementation of the file system logic

disk.h and disk.cpp: Simulated disk operations

shell.h and shell.cpp: User interface for interacting with the file system

Makefile: Compilation script

test_script1.cpp, test_script2.cpp, ...: Test scripts for different functionalities

## Testing

The provided test scripts can be executed using:

make test1
./test1

Ensure all test cases pass to verify correctness of the implementation.

Requirements

Ubuntu Linux

C++11 standard compliance

No external dependencies required
