Fixes IP address problems and proxy slow downs

run cmd.exe as administrator then run ip.fix.bat

ipconfig /release

Force the client to immediately give up its lease by sending the server a DHCP release

arp -d *

This command is used when you want to delete an entry from the ARP table for a particular interface. 
To delete an entry, write arp -d command along with the IP address in a command prompt you want to delete

nbtstat -R

Allows a refresh of the NetBIOS name cache and the names registered with Windows Internet Name Service (WINS)
Purges the contents of the NetBIOS name cache and then reloads the pre-tagged entries from the Lmhosts file.

nbtstat -RR

Allows a refresh of the NetBIOS name cache and the names registered with Windows Internet Name Service (WINS)
Releases and then refreshes NetBIOS names for the local computer that is registered with WINS servers.

ipconfig /flushdns

Clears DNS cache files and resets DNS resolver cache

ipconfig /registerdns

Registers dns

ipconfig /renew

Renew the IPv4 address for the specified adapter
