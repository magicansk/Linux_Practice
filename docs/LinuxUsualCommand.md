# LINUX USUAL COMMANDS #  

## SYSTEM ## 
> * uname -a (Display linux system information)  
> `aaa.example.com 3.10.0-327.el7.x86_64 #1 SMP Thu Nov 19 22:10:57 UTC 2015 x86_64 x86_64 x86_64 GNU/Linux`
> * uname -r (Display kernel release information)  
> `3.10.0-327.el7.x86_64`
> * uptime (Show how long the system has been running + load)  
> `12:24:35 up 18:01,  4 users,  load average: 0.05, 0.11, 0.11`  
> * hostname (Show system hostname)  
> `aaa.example.com`  
> * hostname -i (Show the IP address of the host)  
> `192.168.5.200`
> * last reboot (Show system reboot history)  
> `reboot   system boot  3.10.0-327.el7.x Wed Sep 27 06:48 - 12:27 (2+05:38)`
> * date (Show the current date and time)  
> `Fri Sep 29 12:28:27 EDT 2017`
> * cal (Show the month calender )  
> ```
>    September 2017   
>Su Mo Tu We Th Fr Sa
>                1  2
> 3  4  5  6  7  8  9
>10 11 12 13 14 15 16
>17 18 19 20 21 22 23
>24 25 26 27 28 29 30
> ```  
> * w (Display who is online  )
> ```
>  12:33:17 up 18:10,  4 users,  load average: 0.01, 0.06, 0.09
>USER     TTY      FROM             LOGIN@   IDLE   JCPU   PCPU WHAT
>user     pts/0    :1               09:11   12:45   0.08s  0.08s /bin/bash
>user     :1       :1               03:51   ?xdm?   7:36   0.14s gdm-session-worker [pam/gdm-password]
>user     pts/1    :1               09:26    5.00s  0.24s  0.03s vim LinuxUsualCommand.md
>user     pts/2    :1               12:21    5.00s  0.06s  0.02s w
> ```
> * whoami (Who you are logged in)
> `user`
> * finger user (Display information about a user)
