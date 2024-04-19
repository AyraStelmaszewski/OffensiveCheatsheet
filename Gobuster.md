
================================================================================ <br>
***source*** 
https://erev0s.com/blog/gobuster-directory-dns-and-virtual-hosts-bruteforcing/ <br>
================================================================================
**Subdomain enumeration**
<br>
gobuster vhost -w /usr/share/wordlists/SecLists/Discovery/DNS/subdomains-top1million-5000.txt -u http://thetoppers.htb <br>
gobuster dns -d usage.htb -w dnsmap.txt <br>
