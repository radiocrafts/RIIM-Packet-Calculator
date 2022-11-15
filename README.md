# RIIM Packet length estimation tool
## Description
This worksheet helps users to determine the number of packet sent over the air for a given payload size in a mesh network. 

When using RIIM, there can be times where it's neccesarry to determine the number of packets sendt, in order to determine parameters such as power useage, propagation delay and congestion factor. Sensors with varying payload length makes calculations more complicated. This spreadsheet are meant to help with the calculation of how many packets from a given number of bytes to be sent from a node. 

## How to use this tool:
- Input the number of bytes to be sent. 1 character = 1 byte.
- Type of packet. UDP or CoAP with, or without DTLS (encryption).
- Number of mesh hops 
- Direction of data transfer. Data going from Border router to mesh node is downlink while data going from mesh router to Border router is  uplink.

The output will be a calculation of the number of packets sent, in addition, the sheet does some calculation of the packet size. 
The start packet contains some mesh routing information, and the size of this depends on the number of mesh nodes in the network.