# Redes
## NMAP
```
sudo apt-get install nmap
```
```
nmap -p- -sV -sC --open -sS -vvv -n -Pn [IP]
```
## TELNET (CONECTION)
```
telnet [IP]
```
## FTP (CONECTION)
```
ftp [IP]
```
## SMB (CONECTION)
```
nmap -p 139,445 -n -Pn -T5 10.129.206.119 --open -sV -sC -O
```
```
sudo apt install smbclient
```
```
smbclient -L [IP]
```
```
smbclient '\\[IP]\[WorkShares]'
```
## REDIS DB (CLIENT)
```
sudo apt install redis-tools
```
```
redis-cli -h [IP] -p 6379
```
```
redis-cli -h [IP] -p 6379
```
```
> info
```
```
> keys *
```
```
> get [name key]
```
## MARIADB (CLIENT)
```
sudo apt install mariadb-client
```
```
mariadb -h [IP] -u [user]
```
```
> show databases;
```
```
> use [database];
```
```
> show tables;
```
```
> use [table];
```
```
> select * from [table];
```
## GOBUSTER
```
sudo apt install gobuster 
```
```
DOWNLOAD: https://github.com/digination/dirbuster-ng/blob/master/wordlists/common.txt
```
```
gobuster dir -u http://[IP]:[PORT] -x .php -w [PATH-WORDLIST]
```
## RESPONDER
```
responder-I [NetworkInterface]
```
## WINRM
```
evil-winrm -i [IP] -u [USER] -p [PASS]
```
## JOHN 
```
john -w=/usr/share/wordlists/rockyou.txt hash.txt
```
