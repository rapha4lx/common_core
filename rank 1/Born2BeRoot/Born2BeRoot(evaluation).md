# Check Graphics Interface
`ls /usr/bin/*session`
# Check UFW
`sudo ufw status`
or 
`ufw version`
##### Check With is Running
`sudo service ufw status`
# Check SSH
`sudo service ssh status`
# Check current OS
`uname -v` or `uname -a`
# Group Commands
###### Check users in group 
`getent group {group_name}`
###### Create Group
`sudo addgroup {group_name}`
###### Add user In Group
`sudo adduser {user_name} {group_name}`
# Users Commands
Create new user
`sudo adduser {user_name}`
# Get Hostname
command: `hostmane`
###### Change hostname
`sudo hostname set-hostname {host_name}`
# Check Partitions
`lsblk`
# Check sudo is installed
`which sudo` or `sudo -V`
# Change Current User Pass
`passwd`
