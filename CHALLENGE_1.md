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
directory `/home/airmanjoe`
###### Helpful commands
`cd, ls, cat, head, tail, pwd`

##### Flag 2 - 
The second flag is stored in a file called **-** located in the home 
directory `/home/airmanjoe` 
###### Helpful commands
`cd, ls, cat, file, du`

##### Flag 3 - space
Flag 3 is stored in a file called **spaces in this filename** in the home 
directory `~/`
###### Helpful commands
`cd, ls, cat, file`

##### Flag 4 - hidden
The next flag is stored in a hidden file in the **hidden** directory.
###### Helpful commands
`cd, ls, cat, file, find`

##### Flag 5 - execute
This flag is output when you run the **execute_me** program in the home directory.
###### Helpful commands
`cd, ls, cat, file`

##### Flag 6 - A History Lesson
Do you know your **history**?  Check and see if you can find who helped King 
Arthur build the Round Table...
###### Helpful commands
`history`

##### Flag 7 - It wasn't me...
You will need to use the **setuid** program for this challenge.  The next flag 
is stored in a file named **readme** in airman **Bob's** home directory 
`/home/airmanbob/readme`.
###### Helpful commands
`whoami, cd, ls, cat`

##### Flag 8 - lost
This flag is hidden somewhere in the **lost** directory in a file that is 
exactly 503 bytes.
###### Helpful commands
`cd, ls, cat, file, find, du`

##### Flags 9 & 10 - alike
Two files in the **alike** directory have the same contents.  These two flags
are the names of the two files with identical contents.
###### Helpful commands
`cd, ls, md5sum, diff`

##### Flag 11 - Talk to me goose... 
Something on your localhost is listening on port 10000. I wonder what it wants 
to tell you? 
###### Helpful commands
`cat, nc, wget`

##### Flag 12 - Dr. Frasier Crane
As the good doctor on station 7800 says, I'm listening.  Maybe you should try
listening to 7800 too, you just may need to wait a minute before you can hear 
him...
###### Helpful commands
`nc`


