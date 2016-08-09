# Redis-Server-Exploit
This will give you shell access on the target system if redis server is not configured properly and faced on the internet without any authentication

# Disclaimer
This exploit is purely intended for educational purposes. I do not want anyone to use this exploit to actually hack into computers or do other illegal things. So I cannot be held responsible for any illegal purposes. If you don’t agree, then you are not allowed to use/run/see the exploit… so leave it immediately..

# Pre-Requesties
1. A valid Username of the target system

# Things to keep in mind
 1.  This script is created by treating default port of SSH 22/TCP
 2.  This script is created by treating default port of REDIS Server 6379/TCP
 3.  IP address of the target system and User of the target system served to script as arguments
 4.  Script is created using libraries like termcolored..So, install these libraries before running.

#When you require to use this ?															   															
    When you got something like this:														   															
      Nmap scan report for  (127.0.0.1) 							                                           										
  		 Host is up (0.27s latency).												
		 PORT     STATE SERVICE VERSION                                                                                           	
  		 6379/tcp open  redis   Redis key-value store                                                                               
