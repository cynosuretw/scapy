#### some stuff i wrote in python using scapy:

##### Coffee
If you find this useful you can buy me a coffee :) https://ko-fi.com/markor

##### dhcp-discover-transaction.py
	initiate DHCP discover, wait for offer, send request, wait for ack

##### dhcp-release.py
	send DHCP release

##### ipv6-ra.py
	script to send IPv6 RA packet with validlifetime and preferredlifetime set to zero

##### icmpdump.py
	first time ever that i used threads
	the tool i use to sniff defined interface, recognise ICMP echo request/response packets and print delta time between them
	it also recognizes udp and arp packets
	prints timestamp and VLAN tag

##### ministack.py
	sniffs defined interface and responds to ARP who-has and ICMP echo requests
	threaded

##### scapy-packets.txt
	just some oneliners for packets i needed for testing purposes
