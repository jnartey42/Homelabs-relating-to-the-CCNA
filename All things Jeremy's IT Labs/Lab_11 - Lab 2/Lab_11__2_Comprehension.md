Lab 11 Day 2 - August 10th 2026

Material video - Static Routing
Lab video - Troubleshooting Static Routes

Jeremy's IT Labs on YouTube

------
Comprehension: In this video, Jeremy expands upon connected and local routes, with a large focus on how to configure static routes in the Cisco CLI. The importance of a default gateway is mentioned. Devices send packets (data) to a default gateway address in order to communicate to devices in another network outside of its own topology. The default gateway is also called a default route. Jeremy briefly shows how a packet travels across a network, but goes into depth in the following video "Life of a Packet". He demonstrates configuring a static route on a router in the topology. Once again in privileged exec mode, running the command `ip route`, followed by the netmask, and next hop. There's that first method by specifying the next-hop (the next IP address to go to), or you can specify the exit-interface (the next physical interface to go to) instead. One must configure all the routers in the network topology in order for data to properly traverse where needed. Default routes are encouraged to be configured. 

-----
Lab: The lab is very barebones and straightforward, as it uses the same topology and configurations from the one before it. It's simply asking to find what the misconfiguration in the network is, as the two PCs were unable to ping each other. It all came down to some of the routes on each router being improperly configured. 
