# [uname](https://guialinux.uniriotec.br/uname/)
# Get Current OS Name
`uname -a`
# [Grep](https://guialinux.uniriotec.br/grep/ ) 
`grep` command need this basic syntax to use.
`grep {text_to_find} {file_to_find}`
### -v
show all lines with don't have expression.
### -s
don't show error message.
# [wc](https://guialinux.uniriotec.br/wc/)
this command count lines from string or files.
### -l
count with lines exist.
### -m
count with character exits.
### -w
count with words exists.
# [df](https://guialinux.uniriotec.br/df/)
this command show info on space used or free from system partitions.
### -a
include too in list files from system with 0 blocks.
### -m
list the blocks in Mbytes.
### -k
list the blocks in Kbytes.
# [AWK](https://guialinux.uniriotec.br/awk/)
is a programming language. allows manipulation of text starting of sequence of patterns.
# [who](https://guialinux.uniriotec.br/who/)
this command show the connections info.
### -b
show the last bot.
### -m
show the users info.
# [vmstat](https://guialinux.uniriotec.br/vmstat/)
this command show the statistic from virtual memory.
`vmstat {interval_for_updates} {number_of_updates}`
### -d
show the disc statics.
# [tail](https://guialinux.uniriotec.br/tail/)
this command show the last lines from text file.
### -n 20
get the last 20 lines from text file.
# [expr](https://guialinux.uniriotec.br/expr/)
this command allow with you make the expression math
`expr 5 / 2` get the quocinte of the division of two numbers,
`expr 5 \* 2` get the multiplication of two numbers.
# [ss](https://www.certificacaolinux.com.br/comando-linux-ss/)
this command investigate the current network connection.
its investigate the sockets and return much informations.
this command is a evolution of netstat from old Net-tools.
### -a
list all sockets
### -l
list only opened ports
### -m
show the allocation memory to socket.
### -K
force close of socket.
### -t
show only [[TCP]] sockets
# hostname
### -I
this command give the IP address.

# ip link
return all internet interfaces connected in your pc.
we need find [[MAC]]
then we filter using grep and print second item using awk print $2.
# users
Get number of existent users
# journalctl
get all commands executed with sudo.
`journalctl _COMM=sudo` return all actions with sudo.
# WALL
this command is used to transmit message to all user connected in terminal