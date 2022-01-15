![YDOpd3](https://user-images.githubusercontent.com/45889833/149628883-58697d75-9bb5-46b8-a4aa-ea2f84d7f032.jpg)

# MTIP - Modem Tracker IP Address

MTIP - Modem IP Address Tracker is a scanning tool looking for an ip address on a network that has CIDR or Classless Inter-Domain Routing C (CIDR C).

For those of you who don't know what CIDR is, you can just read it at the following link [There](https://exercise.smktelematikaindramayu.sch.id/blog)

## Requirement

- PHP 7 / 8
- GIT Bash
- Network Connection
- NMAP

## Tested On
```php
LINUX :
- MX Linux X86_64
```
## Installation
Clone From Github
```git
git clone https://github.com/imyhacker/MTIP.git
```


## Usage
Go To Folder
```php
cd MTIP
```
Run Tools
```php
php mtip
```

Result
```php

    \ /
    oVo
\___XXX___/   MTIP CIDR C V.0.1
 __XXXXX__    Modem Tracker IP Address CIDR C
/__XXXXX__\   Crafted By Arikun - IndoSec
/   XXX   \   Copyright (C) 2022 - Nii-sanHax0r
     V        [ Auto Make File Result In This Folder ]
 
[ MODEM TRACK IP ]
Usage : php mtip [IP Network] [Host Gateway]
Ex    : php mtip 192.168.0. 1

[ SCAN IP By NMAP.org ]
Usage : php mtip scan [IP Address]
Ex    : php mtip scan 192.168.0.1

```


## 1. Modem Track IP
```php
[ MODEM TRACK IP ]
Usage : php mtip [IP Network] [Host Gateway]
Ex    : php mtip 192.168.0. 1
```
### Usage
- In last host / last number of IP Address don't fill!.
- And Number 1 is a Host Gateway
- Scanning process up to 254 Host
- Auto Save Result in result.txt

```php
php mtip 192.168.0.{null} 1
```

Result
```php

    \ /
    oVo
\___XXX___/   MTIP CIDR C V.0.1
 __XXXXX__    Modem Tracker IP Address CIDR C
/__XXXXX__\   Crafted By Arikun - IndoSec
/   XXX   \   Copyright (C) 2022 - Nii-sanHax0r
     V        [ Auto Make File Result In This Folder ]
 
Ip Address (NETWORK): 192.168.0 
Router Gateway (HOST): 1 
Your Path : /home/arikun/BELAJAR/MTIP



 == Result == 

[+] Live : 192.168.01
[!] 192.168.02 [!]
[!] 192.168.03 [!]
[+] Live : 192.168.04

```

### 2. Scanner By NMAP
```php
[ SCAN IP By NMAP.org ]
Usage : php mtip scan [IP Address]
Ex    : php mtip scan 192.168.0.1
```
### Usage
- Must Add "scan" before IP Address
- Nb: Scan Default By [NMAP.ORG](https://nmap.org)

```php
php mtip scan 192.168.0.1
```
Result
```php

    \ /
    oVo
\___XXX___/   MTIP CIDR C V.0.1
 __XXXXX__    Modem Tracker IP Address CIDR C
/__XXXXX__\   Crafted By Arikun - IndoSec
/   XXX   \   Copyright (C) 2022 - Nii-sanHax0r
     V        [ Auto Make File Result In This Folder ]
 
Starting Nmap 7.70 ( https://nmap.org ) at 2022-01-15 22:55 WIB
NSE: Loaded 148 scripts for scanning.
NSE: Script Pre-scanning.
Initiating NSE at 22:55
Completed NSE at 22:55, 0.00s elapsed
Initiating NSE at 22:55
Completed NSE at 22:55, 0.00s elapsed
Initiating Ping Scan at 22:55
Scanning 192.168.0 (192.168.0.0) [2 ports]
Completed Ping Scan at 22:55, 3.00s elapsed (1 total hosts)
Nmap scan report for 192.168.0 (192.168.0.0) [host down]
NSE: Script Post-scanning.
Initiating NSE at 22:55
Completed NSE at 22:55, 0.00s elapsed
Initiating NSE at 22:55
Completed NSE at 22:55, 0.00s elapsed
Read data files from: /usr/bin/../share/nmap
Note: Host seems down. If it is really up, but blocking our ping probes, try -Pn
Nmap done: 1 IP address (0 hosts up) scanned in 3.63 seconds
```
## Support And Follow Me
```
Trakteer : https://trakteer.id/arkun666
Instagram : https://www.instagram.com/arkun666
Mail : arkun666@yandex.com 
```

## License
[MIT](https://choosealicense.com/licenses/mit/)
