# big-data-shell-commands
Sneak-peak of Bash and PowerShell commands for processing the data

### Bash
List of commands:

1. ls — List directory contents
 - Syntax: ls [option(s)] [file(s)]
 - Common options: -a, -l
 
2. echo — Prints text to the terminal window
 - Syntax: echo [option(s)] [string(s)]
 - Common options: -e, -n
 
3. touch — Creates a file
 - Syntax: touch [option(s)] file_name(s)
 - Common options: -a, -m, -r, -d
 
4. mkdir — Create a directory
 - Syntax: mkdir [option(s)] directory_name(s)
 - Common options: -m, -p, -v

5. grep — search
 - Syntax: grep [option(s)] pattern [file(s)]
 - Common options: -i, -c, -n
 
6. man — Print manual or get help for a command
 - Syntax: man [option(s)] keyword(s)
 - Common options: -w, -f, -b
 
7. pwd — Print working directory
 - Syntax: pwd [option(s)]
 - Common options: options aren’t typically used with pwd
 
8. cd — Change directory
 - Syntax: cd [option(s)] directory
 - Common options: options aren’t typically used with cd
 
9. rmdir — Remove directory
 - Syntax: rmdir [option(s)] directory_names
 - Common options: -p
 
10. locate — Locate a specific file or directory
 - Syntax: locate [option(s)] file_name(s)
 - Common options: -q, -n, -i
 
11.  > — redirect stdout
 - Syntax: >
 - Common options: n/a
 
12. cat — Read a file, create a file, and concatenate files
 - Syntax: cat [option(s)] [file_name(s)] [-] [file_name(s)]
 - Common options: -n
 
13. | — Pipe
 - Syntax: |
 - Common options: n/a
 
14. head — Read the start of a file
 - Syntax: head [option(s)] file(s)
 - Common options: -n
 
15. tail — Read the end of a file
 - Syntax: tail [option(s)] file_names
 - Common options: -n
 
16. chmod — Sets the file permissions flag on a file or folder 
 - Syntax: chmod [option(s)] permissions file_name
 - Common options: -f, -v
 
17. cp — copy files and directories
 - Syntax: cp [option(s)] current_name new_name
 - Common options: -r, -i, -b
 
18. history — list your most recent commands
 - Syntax: history
 - Common options: -c, -d
 
19. kill — terminate stalled processes
 - Syntax: kill [signal or option(s)] PID(s)
 - Common options: -p

20. compgen — Shows all available commands, aliases, and functions
 - Syntax: compgen [option(s)]
 - Common options: -a, -c, -d


Custom commands in Bash are known as “aliases”. Aliases are essentially an abbreviation, or a means to avoid typing a long command sequence. They can save a great deal of typing at the command line so you can avoid having to remember complex combinations of commands and options. There is one caveat to using aliases, and that is to be sure you don’t overwrite any keywords.

Syntax: alias alias_name = “command_to_run”
```
alias c = “clear”
```
```
alias www = ‘python -m SimpleHTTPServer 8000’
```

### PowerShell 
List of commands:

```











```
