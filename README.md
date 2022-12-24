# Unix-Shell
This is a simple Unix shell implementation that allows the user to enter commands and execute them. The shell supports running simple commands, background processes, and handling input/output redirection.

## Features
+ Run simple commands
+ Handle background processes using & at the end of the command
+ Perform input redirection using <
+ Perform output redirection using >

## Compiling and Running
To compile the shell, run ```gcc -o shell shell.c```.
To run the shell, enter ```./shell``` in the command line.
Or,
Using the makefile
```
make spawnshell
./spawnshell
```
