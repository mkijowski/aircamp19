# Linux: Terminal Cheat Sheet
Note: this is a brief list of useful commands, later challenges will introduce
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
stores all of the data on a computer in files in folders.  It takes some time 
Getting used to moving around a file system via the command line so we have
put together these basic commands to help you navigate the file system:
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

##### Common folders and paths in Linux
These are some common paths in the linux file system.  You can use these with
the above `cd` and `ls` commands to find out more about the file system.  For
example: `ls /home` will show you the contents of the `/home` directory.

* `/home/airmanjoe` - Airman Joe's home folder.  This should be the folder you
  are in when you first sign into your system.
* `/home` - directory containing all user owned files.  Each user of the 
  system will have their own folder inside of this folder.  You can get here
  from Airman Joe's home directory with either `cd /home` OR with `cd ..`
* `/` - the **root** directory, all other files and folders are inside this
  directory.


#### Shortcuts
* `ctrl+c` - stop the currently running command
* `ctrl+a` - go to beginning of the line
* `ctrl+e` - go to the end of the line
* `ctrl+p` - show previously ran command (also you can use the *up arrow* key)
* `ctrl+n` - show the next command that was run (you can use the *down arrow*
  key here)
 
