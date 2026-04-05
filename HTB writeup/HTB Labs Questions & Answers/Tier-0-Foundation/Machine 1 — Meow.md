# Machine 1 — Meow

### **About**

Meow is a very easy Linux machine that guides players through setting up an attacking machine, connecting to HTB labs via VPN, and learning a strategy for completing labs. It focuses on beginner enumeration techniques and demonstrates exploiting a vulnerable Telnet service using default credentials.

### Questions:

**What does the acronym VM stand for?
A:** Virtual Machine

**What tool do we use to interact with the operating system in order to issue commands via the command line, such as the one to start our VPN connection? It's also known as a console or shell.
A:** terminal

**What service do we use to form our VPN connection into HTB labs?
A:** openvpn

**What tool do we use to test our connection to the target with an ICMP echo request?
A:** ping

**What is the name of the most common tool for finding open ports on a target?**
**A:** nmap

**What service do we identify on port 23/tcp during our scans?**
**A:** telnet

![image.png](images/M1-I1.png)

**What username is able to log into the target over telnet with a blank password?
A:** root

![image.png](images/M1-I2.png)

**Submit root flag**
**A:** b40abdfe23665f766f9c61ecba8a4c19

![image.png](images/M1-I3.png)