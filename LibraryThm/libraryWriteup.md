# Library CTF

Room: [https://tryhackme.com/room/bsidesgtlibrary](https://tryhackme.com/room/bsidesgtlibrary)

**nmap**  
We will first run nmap on our target ip machine to find which ports are open and what services they are running
nmap -p- -A -T4 <IP> -o map.txt
![Nmap](./nmap.png)