Lab 11 Day 1 - August 5th 2026

Material video - Routing Fundamentals

Lab video - Static Route Configuration

Jeremy's IT Labs on YouTube

----

Comprehension: Jeremy goes into depth on the purpose of routing within a network. Routing is all about how routers determine the journey that packets (groups of data) take to travel from their starting location, to their destination. All routers have a table (a routing table) that indicates where to move data, based on the destination IP address. There are two main routing methods. `Dynamic Routing` uses specific routing protocols to quickly share information with each other automatically in order to build their own routing tables. `Static Routing` is the process of a network engineer manually configuring routes on a router. More specifically, a route indicates to the router that, in order to send a packet (amount of data) to its destination, send the packet to a next-hop (another IP address that's available). For these routers, showing the routing table will give you a list of connected and local routes, with the former meaning that its a route to the network the interface is connected to, and a local route is one that sends data to a specific IP address configured on the own device's interface. When working with all this data travelling around a network, the router makes sure that the data travels along the most specific matching route -- meaning the closest suitable route with the longest prefix length `(ex /32 is longer than /24. A packet destined for 192.168.1.1 with the available options of 192.168.1.0/24 and 192.168.1.1/32 will end up using the second choice)`.

-----
Lab: This lab wasn't super crazy. First question just asks to configure the PCs and routers according to the given network topology diagram with nearby text. Configuring hostnames is straightforward through the Cisco CLI, as well as IP addresses. Second question just asks to configure static routes on the routers to enable PC1 to ping PC2. It's as simple as configuring an interface, making sure its enabled with `no shutdown`, then specifying the destination IP address, subnetmask, followed by next-hop.
