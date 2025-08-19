# why it is neccesary to block the protocols
## install the openssh server
```bash
sudo apt-get install openssh-server
```
## to check the status of the installation
```bash
sudo service ssh status
```
## to check the devices that are currently connected to the network
```bash
sudo arp-scan --localnet
```
> `arp` stands for address resolution protocol . helps in identifying all connected devices to our network

## to check the protocols active 
```bash
nmap <IP>
```
> `nmap` stands for network mapping . provides details of all active protocols on the system

## brute forcing into target computer using kali in hydra
requirements
1. username of the target machine
2. ip address of the machine
3. rockyou.txt file customise this with the name,dob, roll no etc
4. use hydra to brute force in kali linux
   
