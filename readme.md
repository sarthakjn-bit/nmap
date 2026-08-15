## NMAP LEARNING 
**nmap is a networking tool used to scan hosts device and showshe state and their open /closed & filterred services . 

 **BASIC SCAN ** 
 ## HOST DISCOVERY AND SCAN PORT SERVICE
 1. -SN flag -> This flag used for scanning host discovery in local network
 2. --nmap -sn 192.168.1.1/24                       ->subnet class c 
 3. -- nmap -p- 192.168.1.1                         -> This flag help to scan all 65535 ports 
 4. --nmap -p 10000-45200 192.168.1.1               -> This flag used for scan specific port ranges
 5. --nmap -F 192.168.1.1                           -> This flag is used for  fast scanning 
 
 ## SCAN TYPES 
 1. nmap -sS 192.168.1.1                            ->This flag is used for scan syn scanning  
 2. nmap -sT 192.168.1.1                            ->This flag is used for scan tcp port scanning
 3. nmap -sU1 92.168.1.1                            ->This flag is used for scan udp port scanning 
 4. nmap -sA 192.168.1.1                            ->This flag is used for scan TCP ACK scan **tell firewall applied or not
 5. nmap -sX 192.168.1.1                            ->This flag is used for scan xmas ** fin+psh+urg packet 
 