Lab 16 - August 19th 2026

VLANS (Virtual Local Area Networks, Part 1)

Jeremy's IT Labs on YouTube

--------

Comprehension: The topic of VLANs is covered very extensively on JeremyITLab's channel, so he decided to split it into three different videos, each building off of the one before it. He discusses the purpose of Local Area Networks (LANs), in which its a collection of devices in a single location sharing resources. Devices in the same LAN are part of the same broadcast domain. When a broadcast frame is sent out to find a device's destination MAC address, all devices are bound to receive it, as it pertains to activity on Layer 2 (data link layer of the OSI model). The issue with this comes down to efficiency and security. The bigger a LAN is, with more and more devices connected, the more devices are bound to receive internet traffic that doesn't apply to them, causing performance issues. This is where VLANs (Virtual Local Area Networks) come in, helping seperate a LAN digitally. The seperation occurs as one configures a switch's interfaces, grouping specified ones to be apart of one VLAN.

--------

Lab: This lab largely focuses on the configuration of these virtual LANs, all on the switches' interfaces. Question 1 is simply asking to configure the correct IP address and subnet mask on each PC, setting the gateway address as the last usable address on the subnet. It's easy as clicking on each PC in the topography, following the rules of subnetting, and assigning the appropriate addresses. The gateway address is the IP address used when any computer wants to send data outside of its current network. The last usable addresses in each subnet is whatever the address is before the dedicated broadcast address in each subnet. Question 2 asks to make three connections between R1 and SW1, configuring an interface for each of the three VLANs, and with each IP address is the same gateway address. This was done by entering Cisco's CLI, in privileged exec mode, entering the appropriate interface, configuring the same IP address and subnet mask, and enabling each one with `no shutdown`. Question 3 asked to configure SW1's interfaces into the correct VLANs, and to name them accordingly. This was done by running commands `int range`, specifying the interface range, enabling VLANs with `switchport mode access`, followed by `switchport access vlan 10` (or whatever vlan number designated). Continued doing this for the other VLAN ranges mentioned in the lab. Connectivety worked between all VLANs.
