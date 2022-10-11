# Linux-intro-cli-task


-	Use Command ` whoami ` and figure out the output.
You can use man to know more about whoami.

Command: whoami
Output: Kali


-	Use Command ` hostname ` and figure out the output .
You can use man to know more about hostname.
Command: hostname
Output: Kali
-	Count how many words in any file in your system?
Command:wc file 
Output: 1  4  9 file
-	Find the logged in users in your system?
Command:logname 
Output: kali
-	Use history command and run one of the processes that appears in the history without re-write the command?
Command: history
Output: 2  ip
    3  address
    4  man man
    5  man files
    6  man file
    7  mam
    8  nam
    9  man
   10  man
command :!4
command :man man
-	Find since when your system was running?
Command: uptime
Output: 09:13:22 up  5:30,  1 user,  load average: 0.28, 0.18, 0.16

-	Get the data and time in Dubai using CLI?
  Command: tz=emirates/dubai date
  
-	Store calendar output to a file called calender.txt
command:cal >calendar.txt
 
-	Use this command echos “Oh there is an error” then save the error(output) if appears to file called logs.txt
echos “Oh there is an error” 2>logs.txt
Command 'echos' not found, did you mean:
  command 'echo' from deb coreutils
Try: sudo apt install <deb name>

 After every task write the command you used 
 and the output you got in this README.md file


**Always remember to use man command to explore the commands you are using!**



