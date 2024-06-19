
# RIIM Packet Length Estimation Tool

## Description

This worksheet helps users determine the number of packets sent over the air for a given payload size in a mesh network.

When using RIIM, there can be times when it is necessary to determine the number of packets sent in order to evaluate parameters such as power usage, propagation delay, and congestion factor. Sensors with varying payload lengths make calculations more complicated. This spreadsheet is meant to assist with calculating the number of packets required to send a given number of bytes from a node.

## How to Use This Tool

- **Input the Number of Bytes:** Enter the number of bytes to be sent. Remember, 1 character equals 1 byte.
- **Type of Packet:** Select the type of packet: UDP or CoAP, with or without DTLS (encryption).
- **Number of Mesh Hops:** Specify the number of mesh hops.
- **Direction of Data Transfer:** Indicate whether the data is going from the Border Router to a mesh node (downlink) or from a mesh node to the Border Router (uplink).

The output will include a calculation of the number of packets sent. Additionally, the sheet performs some calculations regarding the packet size. The start packet contains some mesh routing information, and the size of this depends on the number of mesh nodes in the network.
