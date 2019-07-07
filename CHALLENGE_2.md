### Challenge 2 - Wild blue yonder...
Now that you are getting familiar with Airman Joe's local linux system, lets 
take a look at his server (IP address: 10.0.0.25).  There are flags 
associated with all open ports, can you find them?

For this challenge I **highly** recommend  starting off with a scan of the 
given IP address using nmap.  A basic nmap scan can be run with the following:
```
nmap 10.0.0.25
```

But you might need to re run this command with additional options for some 
challenges!

There should be 6 ports open, and 7 flags to find, one of the ports only opens 
if you're listening...


#### Port 10000 - Lets connect
A random service is listening on port 10000, lets see what it has to say...
###### Helpful commands
`nc` 


#### Port 7800 - Dr. Frasier Crane
As the good doctor on station 7800 says, I'm listening.  Maybe you should try
listening to 7800 too, you just may need to wait a minute before you can hear
him...
###### Helpful commands
`nc, man nc`  **Remember, you can search the man page with `/`** 


#### Port 80 - Lair of the spider
This port is a commonly used to host web sites.  I'll give you two options,
1. Read through all of the [HTTP Protocol information](https://en.wikipedia.org/wiki/Hypertext_Transfer_Protocol#Request_methods)
   so you can figure out what exact set of commands to pass to a web server **OR**
2. Try out some new linux commands like `wget` or `curl`


#### Port ???? - Elite secret
There is a secret service listening on a secret port.  We know that the secret 
port number is greater than 1000 and less than 2000.  Can you find it?
###### Helpful commands
`nmap -p, man nmap, nc` 


#### Port 25565 - The name of the game
This service will give you the flag if you can tell it the name of the program 
that typically uses this port.
###### Helpful commands
`nmap, nc` 


#### Port 22 - User Error
Port 22 is what the SSH service runs on, which allows for remote control
(remember, you used SSH to connect to the challenge as airmanjoe).

Unfortunately airmanjoe did not set up his SSH key correctly to sign into the
server.  I wonder if any other user did?
###### Helpful commands
`ssh, su, cat`  


#### Port 156 - Brute-aly 
This port requires a 4-digit pin.  The only way your getting in is trying all 
numbers up to 9999.  If only linux had some way to make this easier...
###### Helpful commands
`seq, |`

