<p align="center" 300px>
<img src="https://i.imgur.com/Ua7udoS.png" alt="Traffic Examination"/>
</p>

<h1>Network Security Groups (NSGs) and Inspecting Traffic Between Azure Virtual Machines</h1>
In this tutorial, we observe various network traffic to and from Azure Virtual Machines with Wireshark as well as experiment with Network Security Groups. <br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Various Command-Line Tools
- Various Network Protocols (SSH, RDH, DNS, HTTP/S, ICMP)
- Wireshark (Protocol Analyzer)

<h2>Operating Systems Used </h2>

- Windows 10 (21H2)
- Ubuntu Server 20.04

<h2>High-Level Steps</h2>

- Install Wireshark
- Create Network Security Groups (NSGs)
- Configure NSG Flow Logs
- Inspect Traffic Using Azure Network Watcher
- Set Up Azure Firewall
  
<h2>Actions and Observations</h2>

<p>
<img src="https://www.freecodecamp.org/news/content/images/size/w2000/2020/08/wireshark-1.png"/>
</p>

<p>
With Wireshark, you can capture and interactively browse the traffic running on a computer network. It's like having a microscope for your network traffic, allowing you to see what's happening on your network at a very detailed level
</p>
<br />

- ### [Youtube: Install Wireshark on a Azure Virtual Machine](https://www.youtube.com/watch?v=eOQ-TWQUFdo)

- ### [Youtube: Filtering and Viewing Portocols](https://www.youtube.com/watch?v=U0brUisYQPk)

<p>
List of some popular network ports and their associated protocols:

1. HTTP (HyperText Transfer Protocol):
Port: 80
Purpose: Used for web traffic.

2. HTTPS (HyperText Transfer Protocol Secure):
Port: 443
Purpose: Secure version of HTTP.

3. FTP (File Transfer Protocol):
Ports: 20 and 21
Purpose: Transfers files between computers.

4. SMTP (Simple Mail Transfer Protocol):
Port: 25
Purpose: Sends email.

5. IMAP (Internet Message Access Protocol):
Port: 143
Purpose: Retrieves email from a server.

6. POP3 (Post Office Protocol version 3):
Port: 110
Purpose: Retrieves email from a server.

7. DNS (Domain Name System):
Port: 53
Purpose: Resolves domain names to IP addresses.

8. SSH (Secure Shell):
Port: 22
Purpose: Securely accesses network services over an unsecured network.

9. Telnet:
Port: 23
Purpose: Unsecure remote login service.

10. RDP (Remote Desktop Protocol):
Port: 3389
Purpose: Accesses a remote desktop or application.
</p>
<br />
