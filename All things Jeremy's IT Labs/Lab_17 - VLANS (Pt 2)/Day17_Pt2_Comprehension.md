Lab 17 - August 24th 2026

VLANS (Virtual Local Area Networks, Part 2)

Jeremy's IT Labs on YouTube

-------

Comprehension: Jeremy continues to go in depth about various topics regarding VLANs, and expanding on their importance. It's great to have configured devices onto specific VLANs for the sake of organization, but there remains an issue. There might be multiple devices connected to one physical switch somewhere in the topology, and there might not be enough cables lying around to dedicate each one to a new device. This is where the configuration of trunk ports and access ports come in. An interface can have traffic flowing through it, in which data is tagged for the VLAN is destined towards it, with untagged data travelling towards a native VLAN configured. VLAN tagging is done mainly with `dot1q`. ISL is a protocol that Cisco created for proprietary purposes. Dot1q data is located after the Source MAC address in an ethernet header. Within this dot1q data, there are many two important fields that play a part in the tagging process, such as the Tag Protocol Identifier (TPID), and the Tag Control Information (TCI). When it comes to VLANs, you can only use numbers within the range 1 to 4094. By default, VLAN1 is the native. Jeremy then goes into talking about commands to configure trunk and access ports. The Router on a Stick (ROAS) is also mentioned, allowing multiple VLANs to use a single interface between a router and a switch. One physical interface is digitally subdivided into subinterfaces, allowing inter-VLAN routing to occur. The router handles passing data between VLANs, rather than the switch.

-------

Lab: First question is a refresher, asking to configure SW1 and SW2's interfaces, similar to the previous lab, for VLAN usage, and assign to the correct VLANs. Second question asked about configuring the SW1 to SW2 connection as a trunk, and using an unused VLAN as a native VLAN. This was done simply by using the Cisco CLI, privileged exec mode in a specific interface, running `switchport mode trunk`, `switchport mode trunk allow vlan ##`, and allowing specific VLANs to use this trunk for traffic. Question 3 is configuring the Router on a Stick approach, for the connection between SW2 and R1. This is simply done by using the router's Cisco CLI, entering a specific interface, enabling it, declaring a new subinterface like `interface g#/#.##`, enabling the `dot1q` encapsulation, and configuring an IP address.
