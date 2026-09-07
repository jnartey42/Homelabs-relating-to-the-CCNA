Lab 12 - August 10th 2026

Material video - Life of a Packet
Lab video - Life of a Packet (Lab)

Jeremy's IT Labs on YouTube

------

Comprehension: There was a lot of material covered in the previous couple videos, as it pertains to the importance of routing. Because of this, the video "Life of a Packet" is dedicated to observing packets, the data that is involved as a device wants to send information to another device, either in or out of a network.  Jeremy talks about the entire process, and the protocols that are involved, such as ARP, encapsulation, de-encapsulation, and more. As a frame (data) travels across a network, it carries important information: the Source IP address, and the destination IP address (all layer 3 OSI model information). Before this happens, a device that wants to send information will need to make an ARP Request (layer 2) first. This ARP Request frame has the same two information IP addresses, alongside a Source MAC address, and Destination MAC address, with a MAC address representing the physical identifying set of numbers and letters unique to each device. The Dest MAC is broadcast `(FFFF.FFFF.FFFF)`, as the device sending does not know who the literal device receiving the frame will be. This ARP Request is sent, passes through switches in the topology, learning who sent the frame and noting their IP address and MAC address, and enters it in its table. The frame is then sent out. As a frame is travelling through the network overall, its source MAC address will change when passing between routers, as its a new device handing off the frame to continue in its journey.

-------

Lab: The lab largely focuses on just witnessing how packets travel between networks, observing the source and destination mac address as the frame passes through a certain segment in the topology. This is for comprehension purposes to really understand what the process is when frames travel.
