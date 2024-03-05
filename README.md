
###### X-Cam
***
### <p align="center">Hack any device camera by sending a link.
***

### [+] Features
 - Three Templates (More Templates Coming Soon)
 - Get IP, Location, Device type and Browser
 - Dual Tunneling (Cloudflare && ngrok)
 - Choose where to save images(custom directory) 
 - Error Diagnoser
 - Argument support for templates, tunnelers and directory
       
 ## The Tool is for :
- Kali Linux
- Termux
- MacOS
- Ubuntu
- Perrot Sec OS
- Garuda Linux     
 
 ## Language is used to Make this tool
- Bash Script
- HTML
- PHP
- JavaScript
- CSS
       
## How Works ?
First of all This tool host a phishing site on attacker local network. This tool gives two port forwarding option (NGROK or CloudFlare) to take website over the internet. Now come on the main Point, attacker simply open the tool by using terminal and generate a link, when Link is generated attacker send that link to the target. If target open the link, target ip will transfer to the attacker. After Website load, the website ask for Camera access and when target give the permission the website will take cam shots one by one and send it to the Attacker
       
###### Installation
```bash
apt update && apt upgrade -y
```
```bash
apt install git -y
```
```bash
apt install php
```
```bash
apt install curl -y
```
```bash
apt install wget -y
```
```bash
git clone https://github.com/DetaSploit/X-Cam
```
```bash
cd X-Cam
```
```bash
chmod +x xcam.sh (optional)
```
```bash
bash setup
```
```bash
bash xcam.sh
```
###### For Termux Additional Command 
```bash
 termux-setup-storage
 ```
 ###### Disclaimer
 
- Tool is Made of Educational Purposes only. Please try not to harm anyone device. 