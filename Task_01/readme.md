**🛡️ Network Scanning using Nmap**

Project Overview
This project demonstrates the process of performing a network scan using Nmap to identify active hosts and open ports within a given subnet. The task was conducted as part of a cybersecurity lab exercise to enhance understanding of reconnaissance techniques and network mapping.

🧩 Command Used
nmap -sS 192.168.1.0/24 -oN network_scan.txt


Explanation of Command:
Flag	Description
1) -sS Performs a TCP SYN (Stealth) Scan, which is faster and less likely to be logged.
2) 192.168.1.0/24	Specifies the target subnet for scanning (scans all hosts from 192.168.1.1 to 192.168.1.254).
3) -oN network_scan.txt	Saves the output in a normal text format to a file named network_scan.txt.

📄 Output Description        
• The output file (network_scan.txt) contains:           
• A list of active hosts discovered in the subnet.     
• Information about open ports and running services for each host.       
• Scan summary including total hosts scanned and time taken.

📸 Supporting Files       
network_scan.txt  ->  Main output file generated from the Nmap scan.     
scan_output_1.png -> Screenshot showing terminal command execution.        
scan_output_2.png -> Screenshot showing result summary
