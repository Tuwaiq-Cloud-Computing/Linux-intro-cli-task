# Linux-intro-cli-task



Command: whoami
Output: kali

Command: hostname
Output: kali

Command: wc Shoug.txt
Output: 98  356 2156 Shoug.txt

Command: sudo last
Output: [sudo] password for kali: 
kali     tty7         :0               Tue Oct 11 12:32    gone - no logout
reboot   system boot  5.16.0-kali7-amd Tue Oct 11 12:32   still running
kali     tty7         :0               Tue Oct 11 12:26 - 12:32  (00:06)
reboot   system boot  5.16.0-kali7-amd Tue Oct 11 12:25 - 12:32  (00:06)
kali     tty7         :0               Thu May 12 20:19 - 20:35  (00:15)
reboot   system boot  5.16.0-kali7-amd Thu May 12 19:57 - 20:35  (00:38)

wtmp begins Thu May 12 19:57:32 2022

Command: history | grep -i id  
Output:  50  id
         57  history | grep -i id

Command: uptime
Output: 16:28:53 up  2:28,  1 user,  load average: 0.16, 0.12, 0.10

Command: timedatectl set-timezone Asia/Dubai
Output: Enter a root password

Command: timedatectl
Output:    Local time: Tue 2022-10-11 16:32:01 +04
           Universal time: Tue 2022-10-11 12:32:01 UTC
           RTC time: Tue 2022-10-11 11:04:25
           Time zone: Asia/Dubai (+04, +0400)
System clock synchronized: no
           NTP service: inactive
           RTC in local TZ: no

Command: touch calender.txt

Command: cal >> calender.txt

Command: cat calender.txt
Output:     October 2022      
Su Mo Tu We Th Fr Sa  
                   1  
 2  3  4  5  6  7  8  
 9 10 11 12 13 14 15  
16 17 18 19 20 21 22  
23 24 25 26 27 28 29  
30 31 

Command: echos "Oh there is an error" 2> logs.txt

Command: cat logs.txt
Output: Command 'echos' not found, did you mean:
  command 'echo' from deb coreutils
Try: sudo apt install <deb name>

