# big-data-shell-commands
Sneak-peak of Bash and PowerShell commands for processing the data

### Bash
List of commands:

1. ls — List directory contents
 - Syntax: ls [option(s)] [file(s)]
 - Common options: -a, -l
 ```
 ls -a
 ```
 ```
 ls -al
 ```
 
2. echo — Prints text to the terminal window
 - Syntax: echo [option(s)] [string(s)]
 - Common options: -e, -n
 ```
 $ echo "Hello World"
 ```
 
3. touch — Creates a file
 - Syntax: touch [option(s)] file_name(s)
 - Common options: -a, -m, -r, -d
 
4. mkdir — Create a directory
 - Syntax: mkdir [option(s)] directory_name(s)
 - Common options: -m, -p, -v
 ```
 mkdir mydirectory
 ```

5. grep — search
 - Syntax: grep [option(s)] pattern [file(s)]
 - Common options: -i, -c, -n
 ``` 
 grep bus *.txt
 ```
 
6. man — Print manual or get help for a command
 - Syntax: man [option(s)] keyword(s)
 - Common options: -w, -f, -b
 
7. pwd — Print working directory
 - Syntax: pwd [option(s)]
 - Common options: options aren’t typically used with pwd
 ```
 pwd -P
 ```
 ```
 pwd -L
 ```
 
8. cd — Change directory
 - Syntax: cd [option(s)] directory
 - Common options: options aren’t typically used with cd
 ```
 cd /usr/local/doc
 ```
 ```
 cd ..
 ```
 
9. rmdir — Remove directory
 - Syntax: rmdir [option(s)] directory_names
 - Common options: -p
 ```
 rmdir mydirectory
 ```
10. locate — Locate a specific file or directory
 - Syntax: locate [option(s)] file_name(s)
 - Common options: -q, -n, -i
 
11. " > " — redirect stdout
 - Syntax: >
 - Common options: n/a
 
12. cat — Read a file, create a file, and concatenate files
 - Syntax: cat [option(s)] [file_name(s)] [-] [file_name(s)]
 - Common options: -n
 ```
 $cat *.txt
 ```
 ```
 cat sample
 ```
 
13. | — Pipe
 - Syntax: |
 - Common options: n/a
 
14. head — Read the start of a file
 - Syntax: head [option(s)] file(s)
 - Common options: -n
 ```
 head -example.txt
 ```
 
15. tail — Read the end of a file
 - Syntax: tail [option(s)] file_names
 - Common options: -n
 ```
 tail example.txt
 ```
 
16. chmod — Sets the file permissions flag on a file or folder 
 - Syntax: chmod [option(s)] permissions file_name
 - Common options: -f, -v
 ```
 chmod 764 test.txt
 ```
 
17. cp — copy files and directories
 - Syntax: cp [option(s)] current_name new_name
 - Common options: -r, -i, -b
 ```
 cp me1.txt me2.txt
 ```
 
18. history — list your most recent commands
 - Syntax: history
 - Common options: -c, -d
 ```
 !180
 ```
 
19. kill — terminate stalled processes
 - Syntax: kill [signal or option(s)] PID(s)
 - Common options: -p
 ```
 kill 1702
 ```

20. compgen — Shows all available commands, aliases, and functions
 - Syntax: compgen [option(s)]
 - Common options: -a, -c, -d
 
21. rm - Removes files from the system without confirmation
  ```
  rm sample
  ```
22. mv - move a file, rename a file
  ```
  mv sample /home/user/Documents
 
  ```
23. cURL - curl is a highly functional tool to recover data from URLs (Uniform Resource Locators) or internet repositories
  ```
  curl https://raw.githubu.com/linux/master/kernel/events/core.c -o core.c
  ```
24. df- display the size, available space, and used space on the filesystems of the device.
  -  -a, –all : it includes duplicate and files that are inaccessible
  -  -x: exclude specific filesystems
  -  -i, –inodes: it list inode information rather than that of block usage
  -  -T, –print-type: prints the type of file system
  -  -P, –portability: it will use the POSIX output format
  -  -B, –block-size=SIZE: increase the size before printing the result
  -  -h, –human-readable: print sizes in power of 1024, which is Mb or Gb
  -  -H, –si: shows result in the power of 1000
  -  –total: omits all entries not relevant to available space, and presents the total
  -   -t, –type=TYPE: the result is limited to listing to file systems of a particular type


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
