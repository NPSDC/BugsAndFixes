#### To clear the syslog file
sudo cat /dev/null > /var/log/syslog

#### To see what is causing the syslog file to fill up
tail -f /var/log/syslog

####URL
https://askubuntu.com/questions/746535/var-log-syslog-growing-indefinitely-in-size/747022#747022

####How much memory consumed
du -h --max-depth=1 /
