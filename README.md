# Task-1--Foundations-of-cybersecurity
PROJECT-1:FOUNDATION-OF-CYBERSECURITY -internship at ApexPlanet software pvt.ltd.
objective: Build strong fundamentals in cybersecurity, networking, cryptography, and set up a professional hacking lab.

Lab Environment Setup Install VirtualBox or VMware. Install Kali Linux as the attacker machine. Install Metasploitable2 or DVWA (Damn Vulnerable Web App) as target machines. Configure a private lab network (Host-Only Adapter)

LINUX FUNDAMENTALS . Networking ifconfig / ip addr — Network interface info ping [host] — Ping host netstat -tuln — List open ports ssh [user]@[host] — Secure shell login scp [src] [user]@[host]:[dest] — Secure copy remote

.File Search/Text Processing find [dir] -name [pattern] — Find files by name grep [pattern] [file] — Search pattern in file wc [file] — Word, line, and byte count head [file] — First lines of file tail [file] — Last lines of file sort [file] — Sort lines diff [file1] [file2] — Show differences

.Package Management (Debian/Ubuntu) apt update — Update package index apt upgrade — Upgrade installed packages apt install [package] — Install package

.User Management adduser [name] — Add user passwd [name] — Change user password whoami — Current user

.Shortcuts Tab — Autocomplete command/file Ctrl+C — Kill current process Ctrl+Z — Suspend current process Ctrl+D — Logout/close terminal This cheat-sheet provides a solid overview for working with Linux at the command line.

3.TOOL FAMILARIZATION Wireshark (Packet Capture) Wireshark is a powerful network packet analyzer that captures and displays data packets traveling through a network interface in real-time. It allows detailed inspection of each packet, useful for troubleshooting, analysis, and security auditing. Start a capture by selecting the network interface and clicking "Start," then stop when enough data is collected. The interface shows packet lists, detailed packet contents, and protocol hierarchy for analysis.

Nmap (Network Scanning) Nmap (Network Mapper) is a command-line tool for discovering devices and open ports on a network. It can perform ping scans to identify active hosts and various port scans (TCP, UDP, stealth) to discover open or filtered ports. Nmap also attempts to detect service versions and operating systems on targets. For example, nmap runs a basic TCP scan, and nmap -sV detects service versions.

Burp Suite (Web Proxy) Burp Suite is a web application security testing tool with a main component called Burp Proxy, which acts as an intermediary between your browser and target web applications. It intercepts, inspects, and allows modification of HTTP/S requests and responses, enabling detailed manual security testing. Users can intercept requests, modify them before forwarding, and replay requests to find vulnerabilities such as XSS or injection flaws.

Netcat (Network Debugging) Netcat is a versatile command-line tool used for reading from and writing to network connections using TCP or UDP. It can perform port scanning, listen for incoming connections, transfer files, or act as a simple backdoor. Example commands include scanning ports on a host, establishing TCP connections, or listening on a port for inbound data. It's often called the "Swiss army knife" of networking.

These tools form core utilities for network analysis, security testing, and troubleshooting in cybersecurity and networking contexts.
Video link:https://www.linkedin.com/posts/balla-rakshitha-761b27329_cybersecurity-ethicalhacking-internship-activity-7384577493040807937-MQhj?utm_source=share&utm_medium=member_desktop&rcm=ACoAAFLtKXkBPxi_Ut6aeFSfOFwRz4efHxC0EVg
