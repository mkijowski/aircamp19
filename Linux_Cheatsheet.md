# Linux: Terminal Cheat Sheet
It's dangerous to go alone.  Take this:

o()xxxx[{:::::::::::::::::::::::::::::>

Note: this is a brief list of usefull commands, later challenges will introduce
other commands but these will always be helpful (especially the `man` command!)

#### System commands
These commands will help you learn more about the system you are signed into.

* `man [COMMAND]` - show the manual for the specified command
* `whoami` - display the user name you are logged in as
* `which [COMMAND]` - show the path to the specified command
* `help` - show Bash help menu
* `help [COMMAND]` - shows help menu for a some commands if there is no **man** 
  page available
* `history` - display all previously ran commands
* `exit` - sign out / end session

#### File System commands
A critical part of all operating systems is the file system.  The file system
stores all of the data on a computer in files in folders.  While you may be 
more familiar with the Microsoft Windows graphical way of moving around in a 
file system, cyber security experts prefer the command line because of the 
immense power it gives them once they become accustomed to it.

That being said it takes some time to get used to moving around via the command
line.  These commands will help you navigate the file system:
* `ls` - list files and folders in current directory
* `ls -l` - list files and folders in current directory and show their 
  permissions, size, ownership, etc.
* `ls -a` - list files and folders in current directory including *hidden* 
  files (hidden files begin with a `.`)
* `ls -F` - list files and folders in a directory and classify them 
  (directories end with `/` and executables will end with `*`)
* `ls dir` - list all items in the folder specified by `dir` (note: `dir` will 
  often start with either a `/`, `../`, or `~/`
* `cd dir` - change directroy to `dir`
* `cd ..` - go up one directory
* `cd /` - go to the root directory
* `cd ~` - go to **your** home directory (the user that you are signed in as)
* `cd -` - go to the last directory you were in
* `pwd` - print working directory
* `cat [FILE]` - output the contents of the file
* `less [FILE]` - output the contents of the file one page at a time
* `touch [FILE]` - create an empty file

#### Shortcuts
* `ctrl+c` - stop the currently running command
* `ctrl+a` - go to beginning of the line
* `ctrl+e` - go to the end of the line
* `&#8593;` - show previously ran command
 
