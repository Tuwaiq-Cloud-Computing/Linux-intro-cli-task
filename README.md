# Linux-intro-cli-task


-	Use Command ` whoami ` and figure out the output.
You can use man to know more about whoami.

command: whoami          

Output:kali

command:hostname

Output:kali

command:wc -w file.txt

Output:2 file.txt

command:w
Output:07:55:49 up  3:25,  1 user,  load average: 0.20, 0.12, 0.10
USER     TTY      FROM             LOGIN@   IDLE   JCPU   PCPU WHAT
kali     tty7     :0               04:30    3:25m  3:01   0.80s xfce4-session

command:!71
                                                                                                                                                                                             
Output:┌──(kali㉿kali)-[~]
└─$ id
uid=1000(kali) gid=1000(kali) groups=1000(kali),4(adm),20(dialout),24(cdrom),25(floppy),27(sudo),29(audio),30(dip),44(video),46(plugdev),109(netdev),119(wireshark),121(bluetooth),133(scanner),141(vboxsf),142(kaboxer)


command:uptime

Output:07:57:34 up  3:27,  1 user,  load average: 0.09, 0.10, 0.09

command:TZ="Asia/Dubai" date

Output: Tue Oct 11 04:13:23 PM +04 2022

command:cal>>calendar.txt 

Output: cat calendar.txt 
    October 2022      
Su Mo Tu We Th Fr Sa  
                   1  
 2  3  4  5  6  7  8  
 9 10 11 12 13 14 15  
16 17 18 19 20 21 22  
23 24 25 26 27 28 29  
30 31             

command :echos "Oh There is an error" 2> logs.txt

Output: cat logs.txt                            
Command 'echos' not found, did you mean:
  command 'echo' from deb coreutils
Try: sudo apt install <deb name>




-	Use Command ` hostname ` and figure out the output.
You can use man to know more about hostname.
-	Count how many words in any file in your system?
-	Find the logged in users in your system?
-	Use history command and run one of the processes that appears in the history without re-write the command?
-	Find since when your system was running?
-	Get the data and time in Dubai using CLI?
-	Store calendar output to a file called calender.txt
-	Use this command echos “Oh there is an error” then save the error(output) if appears to file called logs.txt

 After every task write the command you used 
 and the output you got in this README.md file


**Always remember to use man command to explore the commands you are using!**



