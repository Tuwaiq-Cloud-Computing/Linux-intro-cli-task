# Linux-intro-cli-task


-	Use Command ` whoami ` and figure out the output.
You can use man to know more about whoami.

command: whoami
output: kali  " it returned the current user"


Command: ` Command ` <br/>
Output: -------------------


-	Use Command ` hostname ` and figure out the output.
You can use man to know more about hostname.
command: hostname 
output : kali " returned the hostname of the machine"

-	Count how many words in any file in your system?
commands: 1- vim words.txt " typing three seperated words"
2- wc -w words.txt " counting how many words with option -w " 
output: 3 words.txt

-	Find the logged in users in your system?
command: w -u 
output : kali is the onlu current user logged in
-	Use history command and run one of the processes that appears in the history without re-write the command?

command: 1-history 
2- !4 
output: "the commend was hostname so I reuse it again "

-	Find since when your system was running?

command: uptime 
output : up 28 mins with more info


-	Get the data and time in Dubai using CLI?

command: TZ=Dubai date
output: Tue Oct 11 11:51:40 AM Dubai 2022

-	Store calendar output to a file called calender.txt


command: ncal >calender.txt
cat calender.txt 
output: it shows the output of the command stored in the file

-	Use this command echos “Oh there is an error” then save the error(output) if appears to file called logs.txt

command echo " oh there is an error" 2> logs.txt
output: it prints the same statement and didn't store anything in the file because there was not any error 


 After every task write the command you used 
 and the output you got in this README.md file


**Always remember to use man command to explore the commands you are using!**



