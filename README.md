# cshell
a shell in c


# Notes 
## Notes taken from brennan.io
The lifetime of a shell can be broken down as:
- Initialize: read and execute config files. Changes aspects of shells behaviour.
- Interpret: shell reads commands from stdin. THis could be interactive or a file.
- Terminate: After the commands have been executed, the shell executes any shutdown commands and
  frees down any memory and then terminates.

Whilst active the shell is essentially looping.
It does several things:
-read: read the command from standard input.
-parse: seperate the command string into a program and arguments.
-excute: run the parsed command



```


## Things to udnerstand
kernel

## Resources for Notes
https://brennan.io/2015/01/16/write-a-shell-in-c/
