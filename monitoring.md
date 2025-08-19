# linux-fire-wall
how to secure and hack the system using linux , preventing system from hacking securing system
## network security 
### analyzing the system network
 to check the incoming network to ur system 
```bash
sudo tcpdump
```
```bash
netstat
```
### to check only the active network connections
```bash
netstat - antop
```
*description of the flags*
* `-a` - means show all incoming and outgoing connections
* `-n` - means shows the numerical addresses
* `-t` - shows the TCP protocols\
* `-o` - shows the time stamp
* `-p` - shows the PID of the process it runs
