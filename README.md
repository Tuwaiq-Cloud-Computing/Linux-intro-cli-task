# Linux-intro-cli-task


command: whoami
 
output: kali

command: hostname

output: kali


command: wc -w text.txt

output: 2 text.txt


command: w

output:
07:56:00 up  1:46,  1 user,  load average: 0.22, 0.31, 0.15
USER     TTY      FROM             LOGIN@   IDLE   JCPU   PCPU WHAT
kali     tty7     :0               06:10    1:45m 60.91s  0.47s xfce4-session



command: history
 
output:
1  
    2  ls
    3  man
    4  man man
    5  man la
    6  man ls
    7  man cd
    8  man ls
    9  ls
   10  cd Documents
   11  ls
   12  cd Desktop
   13  back
   14  ls
   15  man man 
   16  man man
   17  man history
   18  man cal
   19  cal
   20  calender
   21  cal
   22  date
   23  sudo apt install ncal
   24  cal
   25  sudo apt install ncal
   26  date
   27  man man
   28  man ls
   29  cal -3
   30  man cmd
   31  sudo apt install ncal
   32  sudo apt update
   33  sudo apt upgrade
   34  /etc/passwd
   35  cat /etc/passwd
   36  etc/shadow
   37  sodu etc/shadow
   38  sodo etc/shadow
   39  sudo etc/shadow
   40  ls -a/Desktop
   41  ls -a /Desktop
   42  cd Desktop
   43  ls -s
   44  ls -a
   45  whoami
   46  id
   47  uptime
   48  date +"%Y,%m,%d"
   49  date
   50  cal
   51  echo 'hi'
   52  history
   53  whoami
   54  cd kali
   55  history | grep -i who
   56  touch  text.txt text2.txt
   57  cat text.txt
   58  nano text.txt
   59  cat text.txt
   60  text.txt 1> text1.txt
   61  text.txt 1> text2.txt
   62  whoami 1>  text2.txt
   63  echo text2.txt
   64  ca
   65  cat text2.txt
   66  cat text1.txt
   67  whow
   68  whoami
   69  hostname
   70  wc -l text.txt
   71  nano text.txt
   72  cat text.tx
   73  cat text.txt
   74  wc -l text.txt
   75  wc -w text.txt
   76  w


command: !51

output: echo 'hi'

output: hi


command: uptime

output: 08:01:22 up  1:51,  1 user,  load average: 0.15, 0.16, 0.12



command: zdump 'Asia/Dubai'

output: Asia/Dubai  Tue Oct 11 16:11:55 2022 +04



command: cal>>calender.txt 

output: cat calender.txt 
    October 2022      
Su Mo Tu We Th Fr Sa  
                   1  
 2  3  4  5  6  7  8  
 9 10 11 12 13 14 15  
16 17 18 19 20 21 22  
23 24 25 26 27 28 29  
30 31                



command: echos 'oh there is an error' 2> logs.txt

output: cat logs.txt    
Command 'echos' not found, did you mean:
  command 'echo' from deb coreutils
Try: sudo apt install <deb name>







