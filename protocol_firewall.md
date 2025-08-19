# protocol firewall
## ufw - uncomplicated firewall 
for allowing and blocking the protocols
1. installing using this command
```bash
sudo apt-get install ufw
```
2. check the installation is done or not
```bash
sudo ufw status
```
3. enabling the ufw
```bash
sudo ufw enable
```
4. allowing or denying certain protocols
```bash
sudo ufw deny <port_name>
```
```bash
sudo ufw allow <portname>
```
5. to reset the ufw
6. ```bash
   sudo ufw reset
   ```
   
