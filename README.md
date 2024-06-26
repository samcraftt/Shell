# Shell

This is a C program that implements a working shell, i.e., a
program that allows users to run commands. The shell reads a command and
follows the fork-exec-wait model to make a new process, execute that command in that new
process, and wait on that new process to complete in the original/parent process. This program executes the command given in the command_line_words array, handles the special case of the user running the "exit" command,
and handles input/output redirection.
