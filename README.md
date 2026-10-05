# campus-network-design
Multi-floor company LAN design in Cisco Packet Tracer with VLAN segmentation, DHCP, and inter-VLAN routing.

Overview

This project demonstrates a realistic enterprise network design where each department or functional zone is isolated on its own VLAN with its own subnet and gateway. The network is centrally routed through a main router, with a multilayer switch handling inter-VLAN routing for busier floors.

Tools used: Cisco Packet Tracer

Topology Summary
Main Router — central routing point, uplinked to the Server Room and all three floor-distribution switches
First Floor multilayer switch — routes and switches traffic for HR, Sales, and Marketing
Second Floor distribution switch — connects Developers, IT, Office, and the Meeting Room wireless AP
Ground Floor switch — connects Reception and a wireless AP for Guest Wi-Fi
Server Room — hosts the Application Server and DHCP Server, uplinked directly to the main router
