# learning-log
(08/05/2025) Created first public repo

(08/05/2025) Created a basic calculator using python for terminal use only.

(08/07/2025) Created a virtual machine and set up various tools like Active Directory, WireShark, Event Log Explorer, SysinternalSuite. To simulate a "Blue Team" home lab.

(08/09/2025) "Blue Team" Home Lab in depth setup. Host Machine(Windows)-Runs main VM environment for monitoring and analysis. VM(Windows Server)-Primary monitoring system with securirty tools for packet capture and log analysis. MacBook Air-Configured as a threat simulation device with the following tools: *Wireshark-Network traffic capture & analysis *Hydra-Password brute-forcing tool for login testing *Aircrack-ng Suite-Wireless network security testing(includes Airodump-ng, Aireplay-ng, Airbase-ng) *Nikto-Web vulnerability scanner *iPad-Configured for remote access into the VM/host machine and planned for basic network probing & simulated malicious activity. (FOCUS IS ON SIMULATING INTERNAL THREATS AND MONITORING SUSPICIOUS ACTIVITY ACROSS THE LAB ENVIRONMENT)  

(08/13/2025)
I added a Raspberry Pi 4 to my home lab and plan to use it as the threat device for my VM to simulate seamless attacks. I purchased another microSD card for Kali OS because the original card was running Raspberry OS, which created conflicts.

I loaded the Raspberry Pi 4 with tools such as:
Nmap – network scanning and host discovery
Hydra – password brute-forcing
Nikto – web vulnerability scanning
tcpdump – packet capture
Wireshark – network traffic analysis
Metasploit Framework – exploitation and payload delivery
dirb/dirbuster – directory brute-forcing

I created scripts for these tools to make them easier to run in the terminal.

Purpose: This setup is designed to generate realistic attack traffic for my Blue Team VM, allowing me to practice detection, logging, and response workflows.
Current Status: Still in the setup phase. I am finalizing networking between the Raspberry Pi and the VM for live packet capture during simulations.

Next Steps:
Finalize network capture in Wireshark to monitor Pi activity on the VM. Automate scheduled attack simulations from the Pi. Document detection results inside my Blue Team playbook.

(08/13/2025) I will be working on two new projects to continue building my coding skills. The first is creating an online resume website that will serve as my tech portfolio. The second is developing an “Entrepreneurial App,” which I will go into more detail about once I refine the idea. These projects are part of my ongoing effort to apply what I’m learning in practical ways, while also exploring new areas of development and design.
