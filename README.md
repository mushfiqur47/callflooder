Asterisk Call Flooder by MasterChen (@chenb0x)

###############
#  DISCLAIMER #   
###############
THIS IS FOR EDUCATIONAL PURPOSES ONLY AND I CANNOT BE HELD RESPONSIBLE FOR ANY MALICIOUS IMPLEMENTATION OF THESE SCRIPTS.
THIS IS EXACTLY WHAT THE TITLE SAYS. IT FLOODS A TARGET WITH CALLS FROM A VOIP SERVER. THIS IS RECOMMENDED FOR TESTING 
YOUR OWN ABILITY TO HANDLE DOS ATTEMPTS.

Materials Needed
================
Asterisk (tested on v1.8 and higher)\n
SIP provider\n
BASH\n


Usage
=====
From your working directory:
./callscript.sh &ltnumber of calls&gt

The script runs through a loop that keeps throwing the Asterisk callfile into the outgoing directory.
The speed of calls depends on a few things.
1. Computing power
2. The channel limit set by your SIP provider
3. I guess it's just 1 and 2.

To Do 10/08/2015
================
1. Change caller ID with each call to avoid a blacklist.
