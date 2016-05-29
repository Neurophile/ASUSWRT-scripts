# ASUSWRT-scripts
scripts for ASUSWRT-Merlin based routers
tested on RT-N66U and firmware 380.58

put these in /jffs/scripts/ and remember to chmod +x for each
firewall-start
firewall-update
services-start

put this in /jffs/filters/
malware-filter.list

run firewall-update manually once to populate the cache file malware-filter.txt
manually run firewall-start or reboot to go live with the block list
the cron job in services start runs every night at 3 am
