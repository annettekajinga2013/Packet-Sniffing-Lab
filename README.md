# Packet-Sniffing-Lab

## Objective

The Packet Sniffing Lab aimed to provide hands-on experience in capturing, analyzing, and interpreting network traffic. The lab focused on using packet sniffing tools to monitor data transmission over a network, identify protocols, detect anomalies, and understand how unencrypted data can be intercepted. This exercise emphasized the importance of network security and encryption in protecting sensitive information.

### Skills Learned
-Proficient use of packet sniffing tools like Wireshark to capture and inspect network traffic.

-Understanding of the OSI and TCP/IP models through real-time packet analysis.

-Ability to recognize common protocols (HTTP, DNS, TCP, UDP, ARP, etc.) and their typical behavior.

-Detection of potentially malicious or abnormal traffic patterns.

-Awareness of security risks related to unencrypted communications.


### Tools Used
-Wireshark – for capturing and analyzing packet-level network traffic.

-tcpdump – command-line tool for lightweight packet capturing.

-Virtual lab network – with devices simulating typical user and server activity.

-Test applications – including web browsers, ping, FTP, and DNS tools to generate traffic.

-Kali Linux / Windows VMs – for attacker and victim simulation environments.


## Steps

(Insert screenshots here with captions explaining each one. Example below.)

Ref 1: Initial Packet Capture with Wireshark

This screenshot shows Wireshark capturing live packets from the lab network interface. Various protocols like ARP, DNS, and TCP are visible in the capture window.

Ref 2: HTTP Packet Dissection

Here, an unencrypted HTTP request is dissected to show the GET request and readable content, highlighting risks of transmitting sensitive data without encryption.

Ref 3: DNS Query Traffic

This image illustrates DNS queries being made to resolve domain names. The source and destination IPs, along with query types, are displayed.

Ref 4: Suspicious Activity Detection

Unusual traffic patterns, including repetitive SYN packets and port scanning behavior, are identified and analyzed, mimicking reconnaissance activities by attackers.

