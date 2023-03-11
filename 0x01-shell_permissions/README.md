# 0x01. Shell, Permissions
This repository contains exercises and examples for working with file permissions and users and groups in the Unix shell.

## Learning Objectives
By completing the exercises in this repository, you will learn:

* How to manipulate file permissions in the Unix shell
* How to create users and groups and assign permissions to them
* How to use special permissions like setuid, setgid, and sticky bit
* How to use the `chmod` and `chown` commands to change permissions and ownership of files and directories

## Repo Structure
The repository is organized into directories for each exercise, as well as a tests directory for testing your solutions. Each exercise directory contains a `README` file with a description of the exercise and a list of tasks to complete, as well as one or more shell scripts to modify and execute.

### The exercises are organized as follows:

0 `-iam_betty`: Script to change the user ID to `betty`.
1 `-who_am_i`: Script to print the effective user ID of the current user.
2 `-groups`: Script to print all the groups the current user is a part of.
3 `-new_owner`: Script to change the owner of the file `hello` to the user `betty`.
4 `-empty`: Script to create an empty file called hello.
5 `-execute`: Script to add execute permission to the owner of the file `hello`.
6 `-multiple_permissions`: Script to add execute permission to the owner and group owner, and read permission to other users, to the file `hello`.
7 `-everybody`: Script to add execute permission to the owner, group owner, and other users, to the file `hello`.
8 `-James_Bond`: Script to set the permissions of the file `hello` to `007`.
9 `-John_Doe`: Script to set the mode of the file `hello` to `-rwxr-x-wx`.
10 `-mirror_permissions`: Script to set the mode of the file `hello` the same as that of the file `olleh`.
11 `-directories_permissions`: Script to add execute permission to all subdirectories of the current directory for the owner, group owner, and other users.
12 `-directory_permissions`: Script to create a directory called `dir_holberton` with specific permissions.
13 `-change_group`: Script to change the group owner of the file `hello` to `holberton`.
100 `-change_owner_and_group`: Script to change the owner to `betty` and the group owner to `holberton` for all files and directories in the working directory.
101 `-symbolic_link_permissions`: Script to add execute permission to everyone for the `file _hello`.
102 `-if_only`: Script to set the mode of the file `hello` to `-rwxr-x-wx` using if statements.
103 `-Star_Wars`: Script that plays the Star Wars IV episode in the terminal.

## Getting Started
To use this repository, simply clone it to your local machine using the following command:


`git clone https://github.com/<username>/0x01-shell_permissions.git`
Once you have cloned the repository, you can navigate to the directory containing the exercise you want to complete and read the README file for instructions on how to complete the tasks.

You can test your solutions by running the shell scripts in the tests directory.

Authors
This repository was created by [ifeanyi kalu](https://github.com/fazzy12)
