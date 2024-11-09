# What is?
This is a system focused in creating any type of web page and content management.
# How Install?
using [[WGET]] in /var/www send a command
`sudo wget https://wordpress.org/latest.zip`
### Decompress
`sudo unzip latest.zip`
### Rename
Rename the folder html to html_old.
now wordpress is a html
commands:
`sudo mv html/ html_old/`
`sudo mv wordpress/ html/`
# Set Perms
send a `sudo chmod -R 755 html`
-R is a recursive. include all objects in subdirectories.
4 is read
2 is write
1 is executable
\*\*\* first is user, second is group and last is others
