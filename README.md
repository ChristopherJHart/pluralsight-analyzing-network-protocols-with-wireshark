# Analyzing Network Protocols with Wireshark

This GitHub repository contains packet captures used in demonstrations for the *Analyzing Network Protocols with Wireshark* Pluralsight course.

The overwhelming majority of these packet captures are sourced from [Nick Russo's packet capture job aids](https://njrusmc.net/jobaid/jobaid.html).

The below sections are a "table of contents" for the packet captures in this repository.

## Module 2

* **[Clip 2](https://github.com/ChristopherJHart/pluralsight-analyzing-network-protocols-with-wireshark/raw/main/m2/m2c2_eth_untagged.pcapng)**: Demonstrates untagged Ethernet frames.
* **[Clip 3](https://github.com/ChristopherJHart/pluralsight-analyzing-network-protocols-with-wireshark/raw/main/m2/m2c3_eth_dot1q_trunk.pcapng)**: Demonstrates Ethernet frames with IEEE 802.1Q tags representing VLANs.
* **[Clip 5](https://github.com/ChristopherJHart/pluralsight-analyzing-network-protocols-with-wireshark/raw/main/m2/m2c5_arp_broadcast.pcapng)**: Demonstrates an exchange of ARP Request and ARP Reply messages.
* **[Clip 6](https://github.com/ChristopherJHart/pluralsight-analyzing-network-protocols-with-wireshark/raw/main/m2/m2c6_arp_gratuitous.pcapng)**: Demonstrates Gratuitous ARP messages.
* **[Clip 7](https://github.com/ChristopherJHart/pluralsight-analyzing-network-protocols-with-wireshark/raw/main/m2/m2c7_arp_scan.pcapng)**: Demonstrates ARP-specific behavior of scanning tools, including (but not limited to) nmap, Nessus, and Qualys.

## Module 3

* **[Clip 3](https://github.com/ChristopherJHart/pluralsight-analyzing-network-protocols-with-wireshark/raw/main/m3/m3c3_ipv4_packet_too_big.pcapng)**: Demonstrates IPv4 packets with Don't Fragment (DF) bit variations through ICMP Echo Request and ICMP Echo Reply messages.
* **[Clip 4](https://github.com/ChristopherJHart/pluralsight-analyzing-network-protocols-with-wireshark/raw/main/m3/m3c4_ipv4_fragments.pcapng)**: Demonstrates IPv4 fragmentation through large ICMP Echo Request and ICMP Echo Reply messages.
* **[Clip 5](https://github.com/ChristopherJHart/pluralsight-analyzing-network-protocols-with-wireshark/raw/main/m3/m3c5_ipv4_traceroute.pcapng)**: Demonstrates IPv4 TTL value analysis.
* **[Clip 8](https://github.com/ChristopherJHart/pluralsight-analyzing-network-protocols-with-wireshark/raw/main/m3/m3c3_ipv6_packet_too_big.pcapng)**: Demonstrates IPv6 packets where the packet is noted as too large to traverse the network path as dictated by an ICMPv6 Packet Too Big message sent in response to an ICMPv6 Echo Request message.
* **[Clip 9](https://github.com/ChristopherJHart/pluralsight-analyzing-network-protocols-with-wireshark/raw/main/m3/m3c9_ipv6_traceroute.pcapng)**: Demonstrates IPv6 Hop Limit value analysis.

## Module 4

* **[Clip 2](https://github.com/ChristopherJHart/pluralsight-analyzing-network-protocols-with-wireshark/raw/main/m4/m4c2_udp_tftp_put.pcapng)**: Demonstrates UDP traffic through uploading a file to a TFTP server.
* **[Clip 4](https://github.com/ChristopherJHart/pluralsight-analyzing-network-protocols-with-wireshark/raw/main/m4/m4c4_tcp_ftp_put.pcapng)**: Demonstrates TCP traffic through uploading a file to an FTP server.

## Module 5

* **[Clip 2](https://github.com/ChristopherJHart/pluralsight-analyzing-network-protocols-with-wireshark/raw/main/m5/m5c2_icmp_ping.pcapng)**: Demonstrates ICMP Echo Request and ICMP Echo Reply messages.
* **[Clip 3](https://github.com/ChristopherJHart/pluralsight-analyzing-network-protocols-with-wireshark/raw/main/m5/m5c3_icmp_destination_unreachable.pcapng)**: Demonstrates ICMP Destination Unreachable messages with the Host Unreachable code.
* **[Clip 4](https://github.com/ChristopherJHart/pluralsight-analyzing-network-protocols-with-wireshark/raw/main/m5/m5c4_icmp_ttl_exceeded.pcapng)**: Demonstrates ICMP Time Exceeded messages with the TTL Exceeded in Transit code through a traceroute.

## Module 6

Coming soon!

## Module 7

Coming soon!
