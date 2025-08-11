Cyber Security Internship – Task 5

Title: Capture and Analyze Network Traffic Using Wireshark  
Author: Gitika Khira 
Date: 11-08-2025  

---

Overview
In this task, I used Wireshark on Kali Linux to capture and analyze live network traffic from the 'eth0' interface.  
The goal was to identify at least three protocols, study their behavior, and understand their role in communication.

---

Tools & Setup
- OS: Kali Linux (Wireshark pre-installed)
- Interface: Ethernet ('eth0')
- Tool: Wireshark

---

Summary of Findings
Captured and analyzed traffic for:
- QUIC – Encrypted transport protocol over UDP (used by HTTP/3)
- ARP – Address Resolution Protocol for mapping IP to MAC
- DNS – Domain Name System for translating domain names to IPs

---

Deliverables
- Packet Capture File: [cybersecurity_task_5.pcap](capture/cybersecurity_task_5.pcap)
- Report (PDF): [Task5_Report.pdf](report/Task5_Report.pdf)

---

How to View the Capture
1. Download the '.pcap' file from this repository.
2. Open it in Wireshark.
3. Apply filters:
   - quic
   - arp
   - dns
4. Observe packet details in each filtered view.

---

Submission

