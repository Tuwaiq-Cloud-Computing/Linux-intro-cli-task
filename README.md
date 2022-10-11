

--

Command: whoami
output:  kali

---

Command: hostname
output:  kali

---

Command: wc -w  /home/kali/Desktop/test.txt
output:  2 /home/kali/Desktop/test.txt

---

Command: w
output:  USER     TTY      FROM             LOGIN@   IDLE   JCPU   PCPU WHAT
		 kali     tty7     :0               06:12    1:44m  2:17   0.47s xfce4-session

---

Command: history
Command: !75
Command: clear
output:

---

Command: uptime
output:  08:01:35 up  1:49,  1 user,  load average: 0.06, 0.08, 0.08

---

Command: zdump 'Asia/Dubai'
output:  Asia/Dubai  Tue Oct 11 16:07:44 2022 +04

---

Command: cal >>  /home/kali/Desktop/calender.txt
Command: cat  /home/kali/Desktop/calender.txt
output:   
    October 2022      
Su Mo Tu We Th Fr Sa  
                   1  
 2  3  4  5  6  7  8  
 9 10 11 12 13 14 15  
16 17 18 19 20 21 22  
23 24 25 26 27 28 29  
30 31        

---

Command: echos 'Oh there is an error' 2> logs.txt 
Command: cat logs.txt  
output:	 Command 'echos' not found, did you mean:
         command 'echo' from deb coreutils
         Try: sudo apt install <deb name>


---




