# Welcome to WSU Cyber Air Camp 2019!

### Rules

1. Nothing illegal
2. If you have any questions, ask!
3. Have fun!

### Getting started

1. Get your battle space IP address from one of your room's mentors.
2. Launch *MobaXterm* from the desktop
3. Start a *Ubuntu WSL* terminal
4. Type `cd ~` then Enter to Change Directory (cd) into your home directory (~)
5. Download the SSH private key [Airman Joe's SSH key](airmanjoe.key) with the following command 
   ```
   wget https://raw.githubusercontent.com/cyber-raider/aircamp19/master/airmanjoe.key
   ```
6. SSH keys wont be trusted if they dont have the correct permissions.  
   Change yours with:
   ```
   chmod 600 airmanjoe.key
   ```
7. SSH into your battlespace with the following: 
   ```
   ssh -i airmanjoe.key airmanjoe@YOUR IP ADDRESS
   ``` 
   substituting the IP given to you for your battle space. 
8. You are welcome to have more than one person signed into your battlespace at 
   a time.

### Useful linux tips
### `man`
One of the most important commands in linux is the `man` command.  Typing 
`man` followed by the name of another command shows you the online manual 
for that command (for example, `man ls` shows you the manual for the `ls` 
command).
* You can search a man page by typing `/` followed by the words you are looking for.
* `n` will take you to the next occurence of your last search
* `p` will take you to the previous occurence of your last search
* `q` will exit out of the man page

Each challenge provides you with a list of possibly helpful linux commands.  
If you get stuck or are unsure about what a command does just check that command's `man` page.

### `ctrl` + `c`
The next most important command isn't so much a command as it is a shortcut.  
`Ctrl` + `c` or shorthand `^c` means hold down the Ctrl key and type the 
letter `c`.  This shortcut sends a signal to the current process telling it to 
stop.

There are several commands used throughout this competition that may take a 
while (minutes) and if mistyped could run indefinitely.  Use `ctrl` + `c` to 
stop these commands.

