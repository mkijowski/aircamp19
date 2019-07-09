### Challenge 1 - Find the flags
Airman Joe has hidden several flags around his Operating System (OS).  Each flag consists of two 
words joined by a symbol.  Examples: 
* `first+second` 
* `flag#staff`
Use the clues to recover them.

##### Hints
* If you get stuck on one challenge skip it and come back.
* Don't forget to check the `man` pages of any of the possible helpful commands!
* Google is your friend, don't be afraid to search for answers.

##### Flag 1 - readme
The first flag is stored in a file called **readme** located in the home 
directory of user airmanjoe: `/home/airmanjoe`.  

You can read it directly if you are already in that directory with `cat readme`,
otherwise you need to specify the whole path to the file like this: 
`cat /home/airmanjoe/readme`
###### Helpful commands
`cat`

#### Flag 2- /home sweet /home
The next flag is in a file called ** readme** but this file is "up" one directory in `/home`.  You can get there any number of ways:
1. `cd /home`
2. `cd /` to go to the root directory, followed by `cd home`
3. Or, if you are still in `/home/airmanjoe` you can go up one directory with:
   `cd ..`

If you get lost check the folder you are in with `pwd`.  You can always go back 
to your home directory with `cd /home/airmanjoe` or with a shortcut `cd ~`
###### Helpful commands
`cd, ls, cat, pwd`

##### Flag 3 - 
The next flag is stored in a file called **-** located in the home 
directory `/home/airmanjoe` 
###### Helpful commands
`cat`

##### Flag 4 - space
This flag is stored in a file called **spaces in this filename** in the home 
directory `~/`
###### Helpful commands
`cd, ls, cat`

##### Flag 5 - hidden
The flag is stored in a hidden file in the **hidden** directory.
Some helpful hints:
* `pwd` will show you what directory you are currently in
* `cd ../` will change directory one level up
* `cd ~` will go back to your home directory ('/home/airmanjoe')
###### Helpful commands
`cd, ls, man, cat`

##### Flag 6 - execute
This flag is output when you run the **execute_me** program in the home directory.
Hint: executing programs from your home directory is a little different, you
need to tell linux *where* the program is...
###### Helpful commands
`cd, ls, cat, ./`

##### Flag 7 - A History Lesson
Do you know your **history**?  Check and see if you can find which Knight helped King 
Arthur build the Round Table...
###### Helpful commands
`history`

##### Flag 8 - It wasn't me...
You will need to use the **setuid** program in your home directory for this challenge.  
The next flag is stored in a file named **readme** in airman **Bob's** home directory 
`/home/airmanbob/readme`.
###### Helpful commands
`whoami, cat`

##### Flag 9 - lost
This flag is hidden somewhere in the **lost** directory in a file that is 
exactly 503 bytes.
###### Helpful commands
`cat, find, man`

##### Flags 10 & 11 - alike
Two files in the **alike** directory have the same contents.  These two flags
are the names of the two files with identical contents.
###### Helpful commands
`md5sum, diff`

