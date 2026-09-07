Lab 18 - August 29th 2026

VLANS (Virtual Local Area Networks, Part 3)

Jeremy's IT Labs on YouTube

------

Comprehension: This is the last of the VLAN videos that Jeremy put out. In this one, he focuses on configuring a native VLAN on a router, looking at Wireshark (similar to Cisco Packet Tracer), and the purpose of a Layer 3 (or Mutlilayer) switch. With a native VLAN configured on a switch, data (frames) that are travelling across it are smaller in size, allowing more of these to travel per second. The main two ways of configuring a native VLAN on a router is either the `dot1q` method, allowing a subinterface to be used, or just configure an IP address fo the native VLAN on a router's physical interface. Jeremy then walks through what one would see on a Wireshark capture. He does this for a few minutes, then introduces a new network tool, the Layer 3 switch. This can handle switching and routing, able to assign IP addresses to its interfaces like a router. Essentially a mashup, taking the best bits from both a router and a switch.. 

--------

Lab: 
