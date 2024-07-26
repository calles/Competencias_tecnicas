# Redes
## NMAP
```
nmap -p- -sV -sC --open -sS -vvv -n -Pn [IP]
```
## TELNET
```
telnet [IP]
```
## FTP
```
ftp [IP]
```
## SMB
```
nmap -p 139,445 -n -Pn -T5 10.129.206.119 --open -sV -sC -O
```
```
smbclient -L [IP]
```
```
smbclient '\\[IP]\[WorkShares]'
```
## REDIS (BD)
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
keys *
```
```
get [name key]
```
