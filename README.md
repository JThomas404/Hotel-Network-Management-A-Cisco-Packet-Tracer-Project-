# Hotel-Network-Management-A-Cisco-Packet-Tracer-Project-

I am delighted to unveil my latest venture in network design, inspired by the requirements of the Vic Modern Hotel. This project, driven by insights from Bernard Otom's course on YouTube, surpasses basic network creation, aiming to revolutionise hotel management technology.

Design Overview:
---
Drawing upon the project brief, the design meticulously links the Reception, Store, and Logistics departments on the first floor; Finance, HR, and Sales/Marketing on the second; and IT and Admin on the third, into a cohesive network framework.
___
Routers & Connectivity:
---
Three routers per floor, placed in the IT department's server room, interconnect using serial DCE cables for robust intra-network communication. OSPF routing spans designated segments (10.10.10.0/30, 10.10.10.4/30, 10.10.10.8/30).
___
Floor-wise Networking: 
---
Dedicated switches on each floor extend connectivity to WiFi networks for laptops and mobile phones, ensuring comprehensive wireless coverage.
___
VLAN Implementation:
---
Each department has its VLAN for enhanced security and efficient communication. VLANs range from Reception (VLAN 80, 192.168.8.0/24) to IT (VLAN 10, 192.168.1.0/24), tailored to meet specific operational needs.
___
Dynamic IP Allocation:
---
OSPF facilitates dynamic route advertising, with DHCP on routers dynamically assigning IP addresses for seamless device connectivity.
___
Security & Accessibility:
---
SSH configuration on routers enhances network security, enabling secure remote access. Port security in the IT department, using sticky MACs, ensures only authorised devices access designated ports.
___
Expanded Lab Features:
---
This project encompasses InterVLAN Routing, WAN setups, OSPF for dynamic routing, VLAN configurations, DHCP, SSH, and Sticky MACs, alongside comprehensive wireless networking and security protocols, exceeding basic connectivity requirements.
___
Resources:
---
This project has been a profound learning experience, refining my skills in network design and troubleshooting—particularly when rectifying OSPF misconfigurations. The exploration into wireless technology, through the integration of smartphones and laptops, has broadened my understanding of network security and access point configuration.

For those interested in practising these Cisco Packet Tracer projects yourself, I invite you to explore further through this link: 
https://lnkd.in/dC2yBxzK
___
