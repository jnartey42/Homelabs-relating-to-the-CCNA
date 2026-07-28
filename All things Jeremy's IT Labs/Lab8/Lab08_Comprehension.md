Lab 08 - July 27th 2026

Configuring Interfaces

Jeremy's IT Labs on YouTube

--------------
Comprehension: Another lab that involves two videos, Day 7 (IPv4 Addressing Part 1) and Day 8 (IPv4 Addressing Part 2). Jeremy talks about activity happening on the third layer of the OSI model - the Network layer. With the network layer providing connectivity between end hosts on different networks, as well as providing IP addresses for hosts, its one of the many important layers in the OSI model, and networking overall. 

Day 7 largely has Jeremy focusing on the IPv4 header, how an IP address is really a connection of 32 binary bits in length, how to convert it from binary to dotted-decimal notation (the way we read IP addresses) and vice versa, and how to indicate which bits are used to dictate the network address, and which are saved for the hosts. For example, seeing /24 or /16 signifies that the first 24, or the first 16 bits respectively, are reserved to indicate the address of a network. The amount of usable IP addresses for a host is (2^n) - 2, as the addresses at 2^0 and 2^n are for the network, and the broadcast. There are 5 different IPv4 address classes, lettered A to E, but we largely use A, B, and C. It makes sense that the network address can't be assigned to a host. 

Day 8 focuses more on calculations, specifically how to calculate the maximum number of hosts, finding the network address, broadcast address, first usable and last usable address, and how to configure an IP address on a Cisco device. The rule of (2^n) - 2 applies when doing those calculations mentioned above. The second half of the video is Jeremy talking about how to use the Cisco CLI on a Router, in order to look at the IP interfaces, which provide info on each interface, their IP address, if they're configured properly for service, and so on. More commands are provided in his video.

--------------

Lab: 
