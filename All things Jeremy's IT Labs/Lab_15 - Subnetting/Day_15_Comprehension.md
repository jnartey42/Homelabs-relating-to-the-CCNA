Lab 15 - August 17th 2026

Material video - Subnetting (Pts 1 to 3)

Lab video - Subnetting (VLSM) Day 15 Lab

Jeremy's IT Labs on YouTube

---------
Comprehension: The importance of subnetting is largely discussed in this video. This is a skill that's essential to the career of a network engineer, and one of the most important topics on the CCNA. Jeremy goes over CIDR (Classless Inter-Domain Routing), and the overall process of subnetting. There are three videos, as there are 3 main types of subnets classes utilized in networking: A, B, and C. D is not used, as its for multicast, and class E is for experimental reasons. Each class has its own range of usable IP addresses. Different companies get assigned different sets of IPv4 addresses and networks based on their size, thanks to the Internet Assigned Numbers Authority (IANA). In the instance that there's a point to point network (a network carries two points), you don't really need a lot of usable IP addresses, at most two. The issue initially is that you can't get down to the exact amount of IP addresses needed for a network, there's usually some extras left over when using the regular method of allocating addresses, which is CIDR (Classless Inter-Domain Routing). The second part of the subnetting series talks about how to subnet class B networks, and the mathematical tricks of writing it out the IP address in octets, borrowing bits when needed, depending on the subnet mask. Different prefix lengths (/24, /25, etc) all correspond to a differnet number of subnets, and allowable number of hosts. The last video talks about VLSM, Variable Length Subnet Masks. This allows the right amount of IP addresses to be allocated, without wasting unnecessary space. Throughout all three videos, there are a multitude of subnet exercises, which all felt straightforward to me. Subnets operate on layer 3 of the OSI model.

-------

Lab: The lab deals with a topology of one network. Asks you to separate into 4 subnets, given a number of hosts, and assign the right IP address when needed. This was a very straightforward process, with me simply following along to the mathematical way that Jeremy explains in the video. Start with the largest amount of hosts, assigning IP addresses, and then continue with the next smallest one, making sure all of them are in the correct ranges, until you've cycled through all the subnets asked for.
