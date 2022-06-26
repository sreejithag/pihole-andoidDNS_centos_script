# pihole-andoidDNS_centos_script

To install pihole with android private DNS in cent os 8

Run the script as super user 

1. `sudo su`
2. `wget https://bit.ly/3OKDGXM -O setup.sh`
3. `chmod +x setup.sh`
4. `./setup.sh <your domain> <email>`

Important 
Don't install lighttpd web server while pihole installtion 
as we already have nginx as web server 
