# Linux-intro-cli-task


1-	Use Command ` whoami ` and figure out the output.
You can use man to know more about whoami.
command: whoami
output: kali

2 -	Use Command ` hostname ` and figure out the output.
You can use man to know more about hostname.
command: hostname
output: kali

3 -	Count how many words in any file in your system?
command: wc -w err.log 
output: 18 err.log 

4 -	Find the logged in users in your system?
command: w 
output: 
07:51:13 up  2:12,  1 user,  load average: 0.34, 0.22, 0.15
USER     TTY      FROM             LOGIN@   IDLE   JCPU   PCPU WHAT
kali     tty7     :0               04:45    3:06m  1:03   0.32s xfce4-sessio

5 -	Use history command and run one of the processes that appears in the history without re-write the command?
command: history 
output: 1  
    2  man print
    3  man printf
    4  man -a intro 
    5  man man 
    6  man -k cd
    7  man -w ls 
    8  cal 
    9  man -w ls 
   10  man ls
   11  man man 
   12  man -k printf
   13  cat /etc/passwd
   14  cat /etc/shadow
   15  sudo cat /etc/shadow
   16  ls -a /home
   17  hostname
   18  uptime
   19  date 
   20  date +"%Y, %m, %d"
   21  cal 
   22  echo 'Hi!!!!'
   23  history
   24  h
   25  history | grep -i date
   26  eccho 'hello'
   27  eccho 'hello'2> err.log
   28  eccho 'hello' 2> err.log
   29  cat err.log 
   30  whoami 
   31  hostname 
   32  wc err.log 
   33  wc -w err.log 
   34  w 
   35  who 
   36  w -u 
   37  history
   38  history 30 
   39  sudo apt update && upgrade 
   40  cal 

command: !30  
output: whoami 

6 -	Find since when your system was running?
command: uptime
output: 08:10:48 up  2:31,  1 user,  load average: 0.14, 0.21, 0.18

7 -	Get the data and time in Dubai using CLI?
command: TZ=Dubai date 
output: Tue Oct 11 12:19:06 PM Dubai 2022

8 -	Store calendar output to a file called calender.txt
command: cal > calender.txt
cat calender.txt 

output: October 2022      
Su Mo Tu We Th Fr Sa  
                   1  
 2  3  4  5  6  7  8  
 9 10 11 12 13 14 15  
16 17 18 19 20 21 22  
23 24 25 26 27 28 29  
30 31    

9 -	Use this command echos “Oh there is an error” then save the error(output) if appears to file called logs.txt
command: echos "Oh there is an error" 2> logs.txt
cat logs.txt 
output: Command 'echos' not found, did you mean:
  command 'echo' from deb coreutils
Try: sudo apt install <deb name>


 After every task write the command you used 
 and the output you got in this README.md file


**Always remember to use man command to explore the commands you are using!**



