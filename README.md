# IP-Addressing-and-Subnetting

## What is an IP Address?
An IP Address (Internet Protocol Address) is a unique identifier assigned to each device connected to a network. It allows devices to send and receive data over the internet or local network.
#### Type	Example	Use
IPv4 ----------  (32-bit)----------	   192.168.1.1 -----------       	Most common (uses 4 octets) <br>
IPv6 ----------  (128-bit)----------	 2001:0db8::1 -----------        Newer, supports more devices


![IP](https://www.astrill.com/blog/wp-content/uploads/2022/06/ipv4-vs-ipv6.png)

# What is Subnetting?
Subnetting is the process of dividing a large IP network into smaller sub-networks (subnets).

## Purpose:

Better network management

Improved performance

Enhanced security

Efficient use of IP addresses

## Subnet Mask
A subnet mask separates the network and host portions of an IP address.

## Example:
IP Address: 192.168.1.10

Subnet Mask: 255.255.255.0

In binary:

yaml
Copy
Edit <br>
IP Address:    11000000.10101000.00000001.00001010 <br>
Subnet Mask:   11111111.11111111.11111111.00000000 <br>
→ Network: 192.168.1.0 <br>
→ Host: 10 <br>
