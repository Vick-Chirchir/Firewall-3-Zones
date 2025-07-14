
<h1>Firewall with 3-Zones</h1>

<!-- ### [Kaltura Capture Recording](https://mediaspace.minnstate.edu/media/Kaltura+Capture+recording+-+April+26th+2025%2C+11%3A11%3A10+pm/1_sp0j5ef9) -->

<h2>Description</h2>
This project demonstrates the implementation of a Cisco ASA Firewall to secure a segmented network architecture with three zones:

Zone 1 (DMZ) — Hosts a public-facing DMZ server (192.168.2.3)

Zone 2 (LAN 1) — Internal client network (192.168.1.0/24)

Zone 3 (LAN 2) — Remote branch network connected via WAN (172.16.3.0/24)


**To simulate enterprise-level network security, where the firewall:**

Filters traffic between the internet, DMZ, and internal LANs

Enforces zone-based policies to segregate traffic and minimise attack surfaces

Demonstrates NAT, ACLs, and stateful inspection using ASA

**Skills Highlighted:**

Network segmentation

DMZ design principles

Cisco ASA firewall interface configuration

Access Control Lists (ACLs)

Static and dynamic routing across zones

WAN simulation between HQ and the branch
<br />


<h2>Languages and Utilities Used</h2>

- <b>Cisco IOS CLI commands</b> 

<h2>Environments Used </h2>

- <b>Cisco Packet Tracer</b> (8.2)

<h2>Program walk-through:</h2>

<p align="center">
Network Design: <br/>
<img src="https://i.imgur.com/7GNSrpg.png" style="width:80%; height:auto;" alt="Disk Sanitization Steps"/>
<br />
<br />
DHCP Server Config on the Router(Router 1):  <br/>
<img src="https://i.imgur.com/okCHFdZ.png" style="width:80%; height:auto;" alt="Disk Sanitization Steps"/>
<br />
<br />
Interface Config with Loopback interface as the IP address to the DHCP Server: <br/>
<img src="https://i.imgur.com/8QABK5s.png" style="width:80%; height:auto;" alt="Disk Sanitization Steps"/>
<br />
<br />
Router Configuration (Router 2) using (ip helper-address):  <br/>
<img src="https://i.imgur.com/uH3Mw58.png" style="width:80%; height:auto;" alt="Disk Sanitization Steps"/>
<br />
<br />
Router Configuration (Router 2) using (ip helper-address):  <br/>
<img src="https://i.imgur.com/uH3Mw58.png" style="width:80%; height:auto;" alt="Disk Sanitization Steps"/>
<br />
<br />
Router Configuration (Router 2) using (ip helper-address):  <br/>
<img src="https://i.imgur.com/uH3Mw58.png" style="width:80%; height:auto;" alt="Disk Sanitization Steps"/>
<br />
<br />
Router Configuration (Router 2) using (ip helper-address):  <br/>
<img src="https://i.imgur.com/uH3Mw58.png" style="width:80%; height:auto;" alt="Disk Sanitization Steps"/>
<br />
<br />
Router Configuration (Router 2) using (ip helper-address):  <br/>
<img src="https://i.imgur.com/uH3Mw58.png" style="width:80%; height:auto;" alt="Disk Sanitization Steps"/>
<br />
<br />
Verify Communication between Devices on both Sites:  <br/>
<img src="https://i.imgur.com/wdv5L5x.png" style="width:80%; height:auto;" alt="Disk Sanitization Steps"/>
<br />
</p>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>

