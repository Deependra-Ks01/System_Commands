Network
- Public
- Private

Ways to gain remote access
-VPN access
-ssh tunneling
-Remote desktop: x2go, rdp, pcoip
-Desktop over browser: Apache Guacomole
-Commercial, over internet : Teamviewer, AnyDesk, zoho assist, ...

Some important port numbers
- port number 21 : ftp
- port number 22 : ssh (Secure Shell)
- port number 25 : smtp (Somple Mail Transfer Protocol)
- port number 80 : http
- port number 443 : https
- port number 631 : cups (Common Unix Printing System)
- port number 3306 : mysql

Firewall

SELinux
- Additional layer of access control on files to services
- Role Based Access Control
- Process sandboxing, least privilege access for subjects
- Check using "ls -lz" and "ps -ez"
- RBAC items: user, role, type, level
- Modes: disabled, enforcing, permissive
- Tools: semanage, restorecon

Network tools
- ping : To see if the remote machine is up
- traceroute : Diagnostics the hop timings to the remote machine
- nslookup : Ask for conversation of IP address to name
- dig : DNS lookup utility
- netstat : Print Network connections
- mxtoolbox.com : For help with accessibility from public network
- whois lookup : who owns which domain name
- nmap : (careful !) Network port scanner
- wireshark : (careful !) Network protocol analyzer

- To see the networks
    ```bash
    ifconfig
    ```

- To ssh to any machine
    ```bash
    ssh mme.iitm.ac.in 
    ```