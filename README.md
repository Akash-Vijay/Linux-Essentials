# Linux-Essentials
List of all essential linux commands. The 20% you need to know. 
<br>

### Special Notes: <br>
* This repo is not the ultimate guide to master linux, but it can be considered as a good reference for learning. 
* All commands in this repo are categorized based on their functionality.
* For further information on each command and their flags, use the **'man'** utility or **[explainshell.com](https://explainshell.com/)**
* Some of the commands mentioned below may not be available in a noraml distribution right out of the box.


<br>

### 1. File Management & Manipulation
<hr>

Terminal Code  | Functionality
-------------  | -------------
pwd  | Print Working Directory
cd | Change Working Directory
ls | List all Files & Directories
touch | Create a new empty file
echo | Display given arguement
cat | Display the contents of a file
rm | Remove files from a Directory
rmdir | Remove a Directory
mkdir | Create a Directory
cp | Copy a file
mv | Move a file
nano | Edit a file using nano editor
vim | Edit a file using vim editor

<br>

### 2. File & Directory Permissions
<hr>

Terminal Code  | Functionality
-------------  | -------------
chmod  |  Change Permissions of a file or directory
 

<br>

### 3. File & Directory Ownership
<hr>

Terminal Code  | Functionality
-------------  | -------------
chown  |  Change User Ownership of a file or directory
chgrp  |  Change Group Ownership of a file or directory

<br>

### 4. Grep & Piping
<hr>

Terminal Code  | Functionality
-------------  | -------------
grep   |  Search for patterns in a file

<br>

### 5. Search Utility
<hr>

Terminal Code  | Functionality
-------------  | -------------
locate   |  Locate a file
find     |  Find a file specifically

<br>

### 6. Enumerating Distribution & Kernel Information
<hr>

Terminal Code  | Functionality
-------------  | -------------
who  |  Display logged in users
whoami  |  Display username
hostname  |  Display current hostname
id  |  Display current User & Group ID
groups  |  Display all the groups of the user
lscpu  | Display information on the CPU
uname  |  Display information about the Kernel

<br>

### 7. Shell & Bash Configuration
<hr>

Terminal Code  | Functionality
-------------  | -------------
echo $SHELL  |  Display current shell
cat /etc/shells  |  Display all available shells
chsh  |  Change login shell

<br>

### 8. Disk Usage
<hr>

Terminal Code  | Functionality
-------------  | -------------
du  |  Display the disk usage of current directory
df  |  Display the entire disk usage

<br>

### 9. File Compression
<hr>

Terminal Code  | Functionality
-------------  | -------------
tar  |  Archive files & directories

<br>


### 10. Users and Groups
<hr>

Terminal Code  | Functionality
-------------  | -------------
useradd  |  Add a user to the system 
usermod  |  Modify a user account
userdel  |  Delete a user account
passwd  |  Change user password
su  |  switch user
groups  | Display all the groups of the user

<br>

### 11. Networking
<hr>

Terminal Code  | Functionality
-------------  | -------------
ip  | Show / Manipulate routing and devices 
ifconfig  |  Configure a network interface
dhclient  |  Dynamic Host Configuration Protocol Client
netstat  |  Print network connections and routing table 
netdiscover  |  An active/passive arp reconnaissance tool

<br>


### 12. TOR & Proxychains
<hr>

Terminal Code  | Functionality
-------------  | -------------
tor  |  Anonymize communication services
proxychains  |  Redirect connections through proxy servers

<br>


### 13. Service and Process Management
<hr>

Terminal Code  | Functionality
-------------  | -------------
top  |  Display all linux processes
htop  |  Interactive process viewer
free  |  Analyse the memory usage 
ps  |  Report a snapshot of the current processes
service  |  Give a list of all available services

<br>


### 14. SSH & SSH Security
<hr>

Terminal Code  | Functionality
-------------  | -------------
ssh  |  OpenSSH SSH client (remote login program)
ssh-keygen  |  Authentication key generation, management and conversion
scp  |  Secure copy (remote file copy program)

<br>


### 15. Curl
<hr>

Terminal Code  | Functionality
-------------  | -------------
curl  |  Transfer a URL

<br>


### 16. UFW Firewall
<hr>

Terminal Code  | Functionality
-------------  | -------------
ufw  |  Manage UFW Firewall

<br>


### 17. Clear Logs
<hr>

Terminal Code  | Functionality
-------------  | -------------
shred  |  Overwrite the specified file(s) repeatedly

<br>


## Resources to Master Linux 

* **[Bandit Labs](https://overthewire.org/wargames/bandit/)** <br>
  A website to practise your terminal skills in linux

* **[Linux Tutorial](https://www.udemy.com/course/linux-tutorials/?LSNPUBID=JVFxdTr9V80&ranEAID=JVFxdTr9V80&ranMID=39197&ranSiteID=JVFxdTr9V80-VnFUWbVcVLi_lc3okae7kg)** <br>
  Free Udemy Course on Linux
  
* **[Linux Survival](https://linuxsurvival.com/)** <br>
  Free Linux Tutorial
