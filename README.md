# minishell
The objective of this project is to create a simple shell.

My shell should:
* Show a prompt when waiting for a new command
* Search and launch the right executable (based on the PATH variable or by using
relative or absolute path) like in bash
* It must implement the builtins like in bash:
* echo with option ’-n’
* cd with only a relative or absolute path
* pwd without any options
* export without any options
* unset without any options
* env without any options and any arguments
* exit without any options
* ; in the command should separate commands like in bash
* ’ and " should work like in bash except for multiline commands
* Redirections < > “>>” should work like in bash except for file descriptor aggregation
* Pipes | should work like in bash
* Environment variables ($ followed by characters) should work like in bash
* $? should work like in bash
* ctrl-C, ctrl-D and ctrl-\ should have the same result as in bash

## Other

**Authors:**  
*[Mark Veligod](https://github.com/markveligod)*  
*[Polina Baranovskaya](https://github.com/polinariabar)*  
