# Linux-intro-cli-task


-	Use Command ` whoami ` and figure out the output.
You can use man to know more about whoami.

Command: whoami
Output: kali


-	Use Command ` hostname ` and figure out the output.
You can use man to know more about hostname.

Command: hostname
Output: kali


-	Count how many words in any file in your system?

Command: wc file
Output: 1  4 19 file

-	Find the logged in users in your system?

Command: logname
Output: kali

-	Use history command and run one of the processes that appears in the history without re-write the command?

Command: history

Output: 
    1  
    2  sudo 
    3  man sudo
    4  man man
    5  apt
    6  man
    7  man man

Command: !7
Command: man man



-	Find since when your system was running?

Command: uptime
Output:  09:12:58 up  4:27,  1 user,  load average: 0.09, 0.05, 0.01

-	Get the data and time in Dubai using CLI?

Command: TZ=emirates/dubai date
Output: Tue Oct 11 01:14:04 PM emirates 2022


-	Store calendar output to a file called calender.txt

Command: cal > calender.txt

-	Use this command echos “Oh there is an error” then save the error(output) if appears to file called logs.txt

Command: echos “Oh there is an error” 2> logs.txt



 After every task write the command you used 
 and the output you got in this README.md file


**Always remember to use man command to explore the commands you are using!**



