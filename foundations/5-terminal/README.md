# Bash

# Working with Bash and the Terminal

This README serves as a basic introduction to working with the Bash shell and the terminal. The Bash shell is a command-line interface that allows you to interact with your operating system using text-based commands. The terminal is the application where you type and execute these commands.

Use this page as a reference for commands you will use throughout this course.

## Table of Contents

1. [Getting Started with the Terminal](#getting-started-with-the-terminal)
2. [Basic Bash Commands](#basic-bash-commands)
3. [Working with Files and Directories](#working-with-files-and-directories)
4. [Permissions and Ownership](#permissions-and-ownership)
5. [Pipes and Redirection](#pipes-and-redirection)
6. [Helpful Resources](#helpful-resources)

## Getting Started with the Terminal

Open your terminal application. You should see a prompt where you can start typing commands. The prompt may display information such as your username, computer name, and current directory.

## Basic Bash Commands

Here are some basic commands to help you get started with Bash:

*   `pwd` - Print the current working directory.
*   `ls` - List the files and directories in the current directory.
*   `cd` - Change to a different directory (e.g. `cd Documents`).
*   `echo` - Display a line of text (e.g. `echo "Hello, World!"`).
*   `clear` - Clear the terminal screen.

## Working with Files and Directories

Bash provides several commands for working with files and directories:

*   `mkdir` - Create a new directory (e.g. `mkdir new_directory`).
*   `touch` - Create a new, empty file (e.g. `touch new_file.txt`).
*   `cp` - Copy a file or directory (e.g. `cp source.txt destination.txt`).
*   `mv` - Move or rename a file or directory (e.g. `mv old_name.txt new_name.txt`).
*   `rm` - Remove a file (e.g. `rm file_to_delete.txt`).
*   `rmdir` - Remove an empty directory (e.g. `rmdir empty_directory`).

## Permissions and Ownership

Files and directories in Unix-based systems have associated permissions and ownership. You can view these using the `ls -l` command. Permissions are displayed as a series of characters, such as `-rwxr-xr-x`.

*   `chmod` - Modify the permissions of a file or directory (e.g. `chmod 755 file.txt`).
*   `chown` - Change the ownership of a file or directory (e.g. `chown user:group file.txt`).

## Pipes and Redirection

Pipes (`|`) and redirection (`>`, `>>`, `<`) are powerful features in Bash that allow you to chain commands and manipulate input and output.

*   **Pipes**: Send the output of one command as input to another (e.g. `ls | grep "txt"`).
*   **Redirection**: Redirect the output of a command to a file or another command (e.g. `echo "Hello, World!" > hello.txt`).

## Reference

[Bash Reference Manual](https://www.gnu.org/software/bash/manual/bash.html)