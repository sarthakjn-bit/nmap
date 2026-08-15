** ADVANCED FLAGS 
## TIME TEMPLATE 
> nmap allow us to used time template which means we can increase scanning speed or decrease accorindly 
  ** There are 5 time template flags
1. nmap -t1 192.168.1.1                           -> T1  used for very slow scan > high accuracy 
2. nmap -t2 192.168.1.1                           -> T2 is also slow scan but faster than t1 
3. nmap -t3 192.168.1.1                           -> T3 bydefault use . meduim scanning speed > accuracy also stable
4. nmap -t4 192.168.1.1                           -> T4 scanning speed increased > accuracy less reliable
5. nmap -t5 192.168.1.1                           ->T5 fast scan speed > accuracy very low 

## version and os flag 
1. nmap -v 192.168.1.1                             -> this flag show port versions
2. nmap -O 192.168.1.1                             -> this flag help to identify os detection 
3. nmap -A 192.168.1.1                             ->  this flag show os detail version used  , traceroute 

## ANONMYOUS FLAGS 
1. nmap --reason -p 192.168.1.1                     ->  give the reason  during scan 
2. nmap -open 192.168.1.1                           -> show only open ports
3. nmap -top-ports 192.168.1.1                      -> scan 100 most common port
4. nmap -p 80,443 192.168.1.1                       -> scan selective ports scan
5. nmap  192.168.1.1  192.168.1.2                   -> scan multiple IP at once
6. nmap - 192.168.1.1                               ->

## save output  
** there are several ways to save nmap output 
1. nmap -oN 192.168.1.1                                -> save nmap output in normal txt format
3. nmap -oG 192.168.1.1                                ->save output in grepable format
4. nmap -oX 192.168.1.1                                ->save output in xml format
