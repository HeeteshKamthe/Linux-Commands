<h1>Linux-Commands</h1>
<h2>Basic Commands</h2>

`ls` : List files in a directory <br>
`ls -l` : Detailed list of files <br>
`ls -a` : Show hidden files <br>


`cd <directory>` : Change directory <br>
`cd ..` : Move up one level <br>


`mkdir <dir>` : Create a new directory<br>
`rmdir <dir>` : Remove an empty directory<br>
`rm <file>` : Delete a file<br>
`rm -r <dir>` : Remove a directory and contents<br>


`cp <source> <destination>` : Copy files<br>
`cp -r <source> <destination>` : Copy directories<br>


`mv <source> <destination>` : Move or rename files<br>


`touch <file>` : Create an empty file<br>
`cat <file>` : Show file contents<br>


`less <file>` : View file page-wise<br>
`more <file>` : View file with pagination<br>


`head <file>` : View first 10 lines<br>
`tail <file>` : View last 10 lines<br>
`tail -f <file>` : View file changes in real-time<br>


`echo "Hello World"` : Print text<br>


`clear` : Clear the terminal<br>
`history` : Show command history<br>
`uptime` : Show system uptime<br>
`whoami` : Show the current user<br>

<h2>File Permissions and Ownership</h2>

`chmod 777 <file>` : Full permissions<br>
`chmod 755 <file>` : Read & execute for all, write for owner<br>
`chmod u+x <file>` : Add execute permission to the user<br>


`chown user:group <file>` : Change file ownership<br>
`chgrp group <file>` : Change group ownership<br>


`ls -l` : View file permissions<br>
`umask 022` : Default permission setting<br>
`find /path -type f -perm 777` : Find files with 777 permission<br>


`chmod +r <file>` : Add read permission<br>
`chmod +w <file>` : Add write permission<br>
`chmod +x <file>` : Add execute permission<br>


`chmod -r <file>` : Remove read permission<br>
`chmod -w <file>` : Remove write permission<br>
`chmod -x <file>` : Remove execute permission<br>


`lsattr` : List file attributes<br>
`chattr +i <file>` : Make a file immutable<br>
`chattr -i <file>` : Remove immutability<br>
`chattr +a <file>` : Append only<br>
`chattr -a <file>` : Remove append-only<br>


`stat <file>` : Get detailed file information<br>
`getfacl <file>` : Get Access Control List<br>


`setfacl -m u:user:rwx <file>` : Set ACL for a user<br>
`setfacl -x u:user <file>` : Remove ACL for a user<br>
`setfacl -b <file>` : Remove all ACL entries<br>
`ls -ld <directory>` : View directory permissions<br>


<h2>User Management</h2>

`whoami` : Show current user<br>
`id` : Display user ID<br>
`who` : Show all logged-in users<br>
`w` : Show user activity<br>


`adduser <username>` : Create a new user<br>
`passwd <username>` : Set a user's password<br>
`deluser <username>` : Delete a user<br>


`usermod -aG <group> <username>` : Add a user to a group<br>


`groups <username>` : Show user groups<br>


`groupadd <groupname>` : Create a new group<br>
`groupdel <groupname>` : Delete a group<br>


`chage -l <username>` : Show password expiry info<br>
`chage -M 30 <username>` : Set password expiry<br>


`su <username>` : Switch user<br>
`sudo su` : Switch to root<br>
`sudo -i` : Open an interactive root shell<br>


`finger <username>` : Display user information<br>
`last` : Show last logins<br>
`lastlog` : Show last login for all users<br>


`pkill -u <username>` : Kill all processes of a user<br>


`who -b` : Show last system reboot<br>
`w -s` : Show short version of active users<br>
`who -r` : Show current runlevel<br>
`who -q` : Show total logged-in users<br>


`sudo` : Execute commands as root<br>
