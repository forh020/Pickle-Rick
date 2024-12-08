# Pickle-Rick
nmap 10.10.10.7 -p- -T5 -v
nmap 10.10.78.51 -p22,80 -A

gobuster dir -u http://10.10.10.7/ -w /usr/share/wordlists/dirb/common.txt
gobuster dir -u http://10.10.10.7/ -w /usr/share/wordlists/dirb/common.txt -x .php
