# Users and Groups Administration 
Super user account is the root which had unrestricted access and control  

/etc/passwd : contains information about user account. User account contains UID unique identifier for each user.  

/etc/shadow users password are store here  

 ![/etc/passwd output ](image.png)

 ## Output of command breakdown  

$ useradd username : Add user. $ useradd Yetunde-Yusuf 

$ passwd username : Set password for user. $ passwd Yetunde 

$ useradd -m username : Create user with Home Directory. $ useradd –m Yetunde 

$ useradd username : Create user without an home directory. $ useradd Yetunde 

$ useradd -g users username : create user with login group. 

useradd: This is the command itself for adding a new user. 

-g users: This option specifies the initial primary group for the new user. In this case, the group name specified is users. The users group is a common default group for regular users. 

username: Replace this with the desired username for the new user. 

$ id username : Confirm user IDs eg id Michael 

$ useradd -s /usr/bin/zsh username : Create user with a specified Shell 

$ sudo su : run command as root user  sudo cahces password for 5 minutes 

$ su username : switch from user A to user B 

 

### Managing Groups 

$ groupadd groupname : Create new group 

$ usermod -a -G groupa,groupb username : Add user to groups 

$ groupmod -n oldname newname : Rename Group 

$ groupdel groupname : delete group 

/etc/group : contains list of all groups. Each group has a unique identifier called gid 