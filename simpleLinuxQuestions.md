Linux System Administrator/DevOps Interview Questions
Simple Linux Questions
====================================================

## <a name='slq'>Simple Linux questions</a>
1. [What is the name and the UID of the administrator user?](#Administrator)
1. [How to list all files, including hidden ones, in a directory?](#listAllFiles)
1. [What is the Unix/Linux command to remove a directory and its contents?]()
* Which command will show you free/used memory? Does free memory exist on Linux?
* How to search for the string "my konfu is the best" in files of a directory recursively?
* How to connect to a remote server or what is SSH?
* How to get all environment variables and how can you use them?
* I get "command not found" when I run ```ifconfig -a```. What can be wrong?
* What happens if I type TAB-TAB?
* What command will show the available disk space on the Unix/Linux system?
* What commands do you know that can be used to check DNS records?
* What Unix/Linux commands will alter a files ownership, files permissions?
* What does ```chmod +x FILENAME``` do?
* What does the permission 0750 on a file mean?
* What does the permission 0750 on a directory mean?
* How to add a new system user without login permissions?
* How to add/remove a group from a user?
* What is a bash alias?
* How do you set the mail address of the root/a user?
* What does CTRL-c do?
* What does CTRL-d do?
* What does CTRL-z do?
* What is in /etc/services?
* How to redirect STDOUT and STDERR in bash? (> /dev/null 2>&1)
* What is the difference between UNIX and Linux.
* What is the difference between Telnet and SSH?
* Explain the three load averages and what do they indicate. What command can be used to view the load averages?
* Can you name a lower-case letter that is not a valid option for GNU ```ls```?
* What is a Linux kernel module?
* Walk me through the steps in booting into single user mode to troubleshoot a problem.
* Walk me through the steps you'd take to troubleshoot a 404 error on a web application you administer.
* What is ICMP protocol? Why do you need to use?

#### [[⬆]](#slq) <a name='Administrator'>What is the name and the UID of the administrator user:</a>
The Adminstrator user, most of the time known as ```root``` is given the UID of 0

#### [[⬆]](#slq) <a name='listAllFiles'>How to list all files, including hidden ones, in a directory:</a>
```ls -a``` to show all files, including hidden ones

Explanation:
```
ls == list directory contents

-a, or --all == do not ignore entries starting with .
```

