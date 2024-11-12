# What is?
Is a web server, developed to be speed, secure and flexible and compatible with norms.
Optimized for system with  less CPU and RAM.
# Install
`sudo` [[apt]] `install lighttpd`
# Allow in Firewall
`sudo ufw allow 80`
# Port Forwarding
Create this rule in port forwarding in Virtual box. Settings >> Network >> Advanced >> Port Forwarding.
Set port 80
# Commands
`sudo lighty-enable-mod fastcgi`
Enable more performance to application web
`sudo lighty-enable-mod fastcgi-php` Enable more performance to application based in PHP.
`sudo service lighttpd force-reload` Force lighttpd restart

