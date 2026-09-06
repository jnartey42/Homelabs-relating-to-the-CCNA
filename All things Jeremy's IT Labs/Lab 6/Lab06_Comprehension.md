Lab 06 - July 24th 2026

Analyzing Ethernet Switching

Jeremy's IT Labs on YouTube

---------

Comprehension: The two videos associated with Lab06, from JeremyITLabs on YouTube, are Day 5 (Ethernet LAN Switching - Day 1), and Day 6 (Ethernet LAN Switching - Day 2). These two videos mainly discussed how data travels between switches and end hosts, before it gets sent across the internet. Jeremy talks about the Ethernet frame, and what goes into it. Consisting of the Ethernet header, Packet, and Ethernet trailer, these parts are made up of smaller bits. The header contains important bits of data, which include the Preamble, SFD, Destination, Source, and Type. Discussion of the importance of each part, alongside MAC Addresses. As data is sent across a network from one computer to another, for example, the computer will send a frame towards a connected switch, the switch learns the receiver's MAC address, and then send out the frame (flood) towards other connected computers until the MAC addresses line up. Switches dynamically learn the addresses of connected devices.  Day 6 is a continuation of Day 5, focusing on IP address protocols such as ARP. Techniques include ARP Request, ARP Reply, looking at the ARP Table on a computer device, and ping.

--------

Lab: The lab's main point was to highlight how data travels throughout a network, and which processes show up at which levels of the OSI model. As a PC pings another PC, the requests that will be sent will be an ICMP Echo Request, and ICMP Echo Reply, as these are the main processes when a computer wants to know the address of another. `Screenshot Q3` shows how the request eventually gets distributed and processed on different layers of the OSI model. `Screenshot Q4 ` is in reply to Question 4 on Jeremy's lab, asking how to access the switch's MAC address table, providing information on which devices and their addresses where dynamically learned, interface ports used to connect, and their MAC address. `Screenshot Q5` is answering the last question, which is simply how to clear the switches' table. After 5 minutes of overall network activity, all learned information expires, unless more data is sent until then.
