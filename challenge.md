# Security Detective

## Question 1
Answer: I am irajtaimurmalik. My home folder is /home/irajtaimurmalik.
Commands: whoami, pwd

## Question 2
Answer: The server name is ubuntu and it runs Ubuntu 26.04.1 LTS.
Commands: hostname, cat /etc/os-release | head -2

## Question 3
Answer: The server has 1.6Gi RAM in total and 2.5G of free disk space.
Commands: free -h, df -h /

## Question 4
Answer: XXX (users from the grep output) can log in with /bin/bash.
Commands: grep bash /etc/passwd

## Question 5
Answer: XXX processes are running right now.
Commands: ps aux | wc -l

## Question 6
Answer: lab5user was created at HH:MM:SS and deleted at HH:MM:SS.
Commands: sudo grep lab5user /var/log/auth.log | grep -E "useradd|userdel|deluser"
