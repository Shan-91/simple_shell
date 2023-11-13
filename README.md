0x16. C - Simple Shell
C
Group project ALX software engineering program 
Syscal

PROJECT OVERVIEW
A shell is a program that executes other programs in response to text commands. A sophisticated shell can also change the environment in which other programs execute by passing named variables, a parameter list, or an input source.

In Unix-like operating systems, users typically have many choices of command-line interpreters for interactive sessions. When a user logs into the system interactively, a shell program is automatically executed for the duration of the session. The type of shell, which may be customized for each user, is typically stored in the user's profile, for example in the local passwd file or in a distributed configuration system such as NIS or LDAP; however, the user may execute any other available shell interactively.

Output
Unless specified otherwise, your program must have the exact same output as sh (/bin/sh) as well as the exact same error output.
The only difference is when you print an error, the name of the program must be equivalent to your argv[0]

Compilation
This shell will be compiled this way:
gcc -Wall -Werror -Wextra -pedantic -std=gnu89 *.c -o hs
