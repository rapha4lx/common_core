# What is?
UFW is a uncomplicated firewall, a program for linux for manager firewall using command-line.
Simple alternative to iptables and nftables
# Install
`sudo` [[apt]] `install ufw`
# Commands
###### Check if is running
`which ufw`
or
`sudo service ufw status`
or 
`sudo service ufw status numbered`
###### Create Role
###### allow
`sudo ufw allow {port}
###### deny
`sudo ufw deny {port}
###### delete 
`sudo ufw delete {number}
###### or 
`sudo ufw delete {type} {port}`
