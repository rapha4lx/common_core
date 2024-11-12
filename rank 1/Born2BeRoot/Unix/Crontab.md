Is a manager of background processor. The processor is executed in the 

# Command for manager task
`sudo crontab -u root -e`
# Commands
### m
```Correnponds a the minute in the script is executed```
### h
`The hour exatle in format 24 houers`
### dom
`Refer the day in the month`
### dow 
`Refer the day in the week`
### user
`Define the user of execute the command, can the root or the other user as long as you have perm`
# Stop Crontab
`sudo /etc/init.d/cron stop`
# Start Crontab
`sudo /etc/init.d/cron start`
# Stop From systemctl
`sudo systemctl stop cron`
with you restart this run again.
`sudo systemctl disable cron`
with this command cron is disabled after rebot.
for enable send systemctl `enable` and `start`
# Start From systemctl
`sudo systemctl start cron`