# Basic Linux Commands
Linux is an operating system made from software collection based on Linux kernel and often a package management system. 
Shell takes command from a user and interprets and send it to the kernel for execution. Shell is an interactive user interface. 

 
## Types of Linux Shell: 

sh (Bourne shell) 
Bash (Bourne-Again Shell) 
Korn Shell(ksh) 
zsh 

Root Directory: / 
Home Directory: ~ or $HOME which are both alias for /home/(USER) 

Absolute path: $ cd /home/User/Folder 
Relative path : $ cd Folder 

 

$uname –a : used to identify the type of OS, version of Linux and distribution type 

$ uptime : shows how long the system has been running  

$ whoami : identify the logged in user 

$ ps : used to show all the processes running on the system  

$ top: is used to show more information about the running processes 

$ df –h : shows information about your storage (disk space and file system) 

$ pwd : present working directory  

$ ls : content of present working directory  

$ ls –a : show all hidden files 

$ls –l /ls -lh : list of all files and permission 

$ ls / all the content of the root directory 

 
### File Operation 

$ mkdir : used to create a directory  

$ touch Filename: used to create a new file  

$ cp  : used to copy file   

$ mv : can be used to move a file from one location to another or rename a file  

$ cat : used to view the content of a file 

$ rm : remove a file 

$rm –r : delete a directory  

$ rmdir : delete an empty directory  

$ rm –rf :deletes a directory without confirmation 

$ head : used to view the first 10 lines of a file  without specifying a number 

$ head –n 4 /etc/passwd - shows the first 4 users created 

$ tail : used to view the last 10 lines of file without specifying a number 

$ tail –n 4 /etc/group displays the last 4 groups created 

 

#### Text Editors 

$ vim filename 

$ vi filename (preferably, to exist escape column wq! Enter) 

$ nano filename 

 

 
##### Seeking Help 

$ man command  

$command –h eg ls –h 

$ command –help  eg df –help 