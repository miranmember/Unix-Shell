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
## Examples
+ To run a simple command, such as ls, enter ls in the shell.
+ To run a command in the background, add & at the end of the command. For example, sleep 10 & will run the sleep command in the background for 10 seconds.
+ To perform input redirection, use < followed by the file name. For example, sort < input.txt will sort the contents of input.txt and display the result in the shell.
+ To perform output redirection, use > followed by the file name. For example, ls > output.txt will save the output of the ls command to a file named output.txt.

## Limitations
+ The shell does not currently support piping using |.
+ The shell does not handle input/output redirection in the same command. For example, ls > output.txt < input.txt is not currently supported.
