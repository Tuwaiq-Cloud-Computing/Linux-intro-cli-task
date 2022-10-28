1- whoami
result: hudaiban  " it returned the current user"


Command:  Command  
Output: -------------------


-    Use Command  hostname  and figure out the output.
You can use man to know more about hostname.
2- hostname 
result : ubuntu " returned the hostname of the machine"

-    Count how many words in any file in your system?
3- vim words.txt " typing three seperated words"
wc -w words.txt " counting how many words with option -w " 
result: 3 words.txt

-    Find the logged in users in your system?
4- w -u 
result : kali is the onlu current user logged in
-    Use history command and run one of the processes that appears in the history without re-write the command?

5-history 
!4 "the commend was hostname so I reuse it again "

-    Find since when your system was running?

6- uptime 
result : up 28 mins with more info


-    Get the data and time in Dubai using CLI?

7- TZ=Dubai date
result: Tue Oct 11 11:51:40 AM Dubai 2022

-    Store calendar output to a file called calender.txt


8- ncal >calender.txt
cat calender.txt 
result: it shows the output of the command stored in the file

-    Use this command echos “Oh there is an error” then save the error(output) if appears to file called logs.txt

9- echo " oh there is an error" 2> logs.txt
result: it prints the same statement and didn't store anything in the file because there was not any error
