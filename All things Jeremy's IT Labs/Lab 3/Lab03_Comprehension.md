Lab 03 - July 20th 2026

OSI Model & TCP/IP Suite

Jeremy's IT Labs on YouTube

------------------

Comprehension: In this video, Jeremy teaches about a widely used networking model that network engineers use in order to discuss internet protocols and standards. These protocols and standards are in place in order for different devices and software to communicate with each other on a unified level. This is the OSI Model. Standing for "Open Systems Interconnection", it's a conceptual model that was created by the International Organization for Standardization in order to higlight the different functions in a network. From top to bottom, it looks like:

7 - Application

6 - Presentation

5 - Session

4 - Transport

3 - Network

2 - Data Link

1 - Physical

Each layer has their own responsibility, in which Jeremy talks about in full. Network engineers largely work with layers 1-4, as it largely deals with the data itself moving around from one destination to another. There are different terms when it comes to the data moving from one device to another. As it moves through the layers, becoming encapsulated, layer 4 adds a header, in which it becomes a segment, layer 3 also adds a header, now known as a packet, and layer 2 adds a header and trailer, now known as a frame. At this point, the frame of data moves across to the recieving device, dencapsulated and processed. Data, segment, packet, and frame are examples of protocol data units. There is another conceptual model used, called the TCP/IP suite. This suite looks like:

4 - Application

3 - Transport

2 - Internet

1 - Link

Layers 7, 6, and 5 of the OSI model are combined into one layer, known as layer 4 of the TCP model. The transport layer stays the same, the network layer turns into the internet layer, and layers 2 and 1 of OSI becomes layer 1, the link layer.

------------------

Lab: We use Cisco Packet Tracer in order to analyze a pre-configured network, in Simulation mode. Looking at the simulation panel after clicking a device, we see various events happening on many levels of the OSI model. Besides seeing activity on the network itself, the simulation panel highlights many protocol data units moving between layers, and ultimately between devices. This lab is largely just to see how data moves from start to finish on a network, step by step.
