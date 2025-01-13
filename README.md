# TCPDump-Logging
This project is focused on learning and applying TCPDump, a powerful command-line packet analysis tool, to monitor, capture, and analyze network traffic.

Project Scenario
Your Role: Intermediate-level Network Administrator
You are a network administrator for an accounting firm. The company suspects that some of its workstations are hacked. Your job is to develop a script that will run in the background and sample network traffic that meets certain criteria and save them for cyber forensic analysis.

Objectives:
Understand Network Traffic Capture:

Gain familiarity with TCPDump commands and options to filter, capture, and display network traffic.
Learn the fundamentals of protocols such as TCP, IP, and SSL/TLS encryption.
Develop a Logging Tool Script:

Automate packet capturing using a shell script.
Include advanced features like file rotation, size limits, and filtering to streamline packet analysis.
Analyse Captured Traffic:

Save captured packets into PCAP files for post-analysis.
Use tools like Wireshark to decrypt and interpret encrypted traffic (e.g., HTTPS).
Simulate Real-World Scenarios:

Identify unauthorised access attempts (e.g., SSH attacks).
Monitor specific hosts, ports, or traffic types using custom filters.
Key Tasks:
Introduction to TCPDump:

Learn the basic syntax and options of TCPDump for capturing and analysing network packets.
Explore formatting options to display packet data in different views (e.g., ASCII, hexadecimal).
Create a Logging Tool Script:

Write a shell script to automate TCPDump commands.
Configure the script to filter traffic, set capture limits, and save output to files.
Save Captured Packets in Dump Files:

Use the -w and -r options to save and read PCAP files.
Verify the contents of captured packets using TCPDump and other tools.
Sequence Dump Files with Time and Size Limits:

Apply -G (time limit) and -C (size limit) options to generate sequentially numbered PCAP files.
Avoid large files by splitting captured data into manageable chunks.
Decrypt Encrypted Traffic:

Set up the SSLKEYLOGFILE environment variable to log SSL/TLS keys.
Use Wireshark to decrypt and analyse HTTPS traffic by referencing the captured keys.
Cumulative Challenge:

Develop a surveillance script (checkspy.sh) to monitor and capture SSH traffic (port 22).
Test the script using simulated traffic and analyse results in Wireshark.
Skills Developed:
TCPDump Expertise:

Mastered TCPDump commands to capture and filter traffic based on interfaces, ports, hosts, and protocols.
Gained proficiency in advanced options like -i, -G, -C, and -w.
Shell Scripting:

Automated TCPDump operations through custom shell scripts.
Managed file permissions and executed commands efficiently.
Network Traffic Analysis:

Captured and analysed network traffic, including encrypted HTTPS and SSH sessions.
Used Wireshark to interpret packet data for forensic insights.
SSL/TLS Decryption:

Configured tools to log SSL/TLS keys and decrypt encrypted traffic.
Understood the encryption and handshake processes used in secure communications.
Cybersecurity Awareness:

Simulated real-world scenarios like unauthorised SSH attempts.
Built tools to monitor and detect suspicious activity.
File Management and Efficiency:

Implemented size and time limits to manage captured data effectively.
Organised sequential dump files for streamlined analysis.
Deliverables:
Logging Tool Script:

A functional shell script that captures network traffic based on specific criteria.
Includes advanced features like file rotation and size limits.
PCAP Files:

Sequentially captured network traffic data stored in PCAP format for further analysis.
Wireshark Analysis:

Decrypted HTTPS traffic and analysed HTTP headers, payloads, and communication flows.
Surveillance Script:

A custom script (checkspy.sh) for monitoring SSH traffic across all interfaces, detecting potential unauthorised access.
Applications:
Network Troubleshooting: Monitor network interfaces, identify connectivity issues, and analyse packet flows.
Cybersecurity: Detect and analyse unauthorised access attempts or suspicious activity.
Forensic Analysis: Capture and decrypt network traffic for investigative purposes.
Learning and Research: Deepen understanding of network protocols, encryption, and monitoring tools.
