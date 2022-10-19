# Linux-intro-cli-task


1 -	Use Command ` whoami ` and figure out the output.
You can use man to know more about whoami.

Command: ` Command ` <br/>
Output: -------------------

Command: whoami
Output: kali

2 -	Use Command ` hostname ` and figure out the output.
Command: hostname
Output: kali
You can use man to know more about hostname.

3 -	Count how many words in any file in your system?
Command: wc Ruba.txt
Output: 1 0 1 Ruba.txt

4 -	Find the logged in users in your system?
Command: sudo last
output:
kali     tty7         :0               Tue Oct 11 04:38    gone - no logout
reboot   system boot  5.16.0-kali7-amd Tue Oct 11 04:30   still running
kali     tty7         :0               Thu May 12 12:19 - 12:35  (00:15)
reboot   system boot  5.16.0-kali7-amd Thu May 12 11:57 - 12:35  (00:38)
wtmp begins Thu May 12 11:57:32 2022

or

Command: w
output:
23:34:36 up  3:17,  1 user,  load average: 0.03, 0.04, 0.01
USER     TTY      FROM             LOGIN@   IDLE   JCPU   PCPU WHAT
kali     tty7     :0               04:38   19:03m  1:05   0.23s xfce4-sessio

5 -	Use history command and run one of the processes that appears in the history without re-write the command?
Command: history | grep -i id
output:
22  history | grip -i id

or

Command: history

6 -	Find since when your system was running?
Command: uptimee
sudo apt update
sudo apt upgrade

output:
23:28:09 up  3:10,  1 user,  load average: 0.21, 0.09, 0.03
                                                            
7 -	Get the data and time in Dubai using CLI?
Command: TZ='Asia/Dubai"date
or TZ=Dubai date
timedatectl list-timezones | grep Dubai

output:
Wed Oct 12 03:38:28 AM Dubai 2022


8 -	Store calendar output to a file called calender.txt
Command: touch calender.txt
cal >> calender.txt
TZ='Asia/Dubai' date 1>calender.txt

output:
Wed Oct 12 07:48:17 AM +04 2022
    October 2022
 Su Mo Tu We Th Fr Sa
                    1
  2  3  4  5  6  7  8
  9 10 11 12 13 14 15
 16 17 18 19 20 21 22
 23 24 25 26 27 28 29
 30 31

9 -	Use this command echos “Oh there is an error” then save the error(output) if appears to file called logs.txt
Command: echo "oh there is an error" 2> log.txt
output: oh there is an error

 After every task write the command you used 
 and the output you got in this README.md file


**Always remember to use man command to explore the commands you are using!**



