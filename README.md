<p align="center">
<img src="https://i.imgur.com/Ua7udoS.png" alt="Traffic Examination"/>
</p>

<h1>Network Security Groups (NSGs) and Inspecting Traffic Between Azure Virtual Machines</h1>
In this tutorial, we observe various network traffic to and from Azure Virtual Machines with Wireshark as well as experiment with Network Security Groups. <br />


<h2>Video Demonstration</h2>

- ### [YouTube: Azure Virtual Machines, Wireshark, and Network Security Groups](https://www.youtube.com)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Various Command-Line Tools
- Various Network Protocols (SSH, RDH, DNS, HTTP/S, ICMP)
- Wireshark (Protocol Analyzer)

<h2>Operating Systems Used </h2>

- Windows 10 (21H2)
- Ubuntu Server 20.04

<h2>High-Level Steps</h2>

- Create Virtual Machines
- Install and run wireshark
- Observe THCP Traffic


<h2>Actions and Observations</h2>

<p>
<img src=https://i.imgur.com/fJalwaP.png height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Login to your Microsoft Azure portal and create two Virtual machines by clicking create Virtual Machine. One as windows 10 OS and the other as Ubuntu OS. Make sure both machines are in the same resource group. 
</p>
<br />

<p>
<img src=https://i.imgur.com/Tgr0iPA.png height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Download wireshark while in VM-1, open wireshark to start network traffic monitoring.
</p>
<br />

<p>
<img src= https://i.imgur.com/ybsK8Ue.png height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Observe the DHCP traffic, go to powershell and request new IP adress using ipconfig/renew in the command line. Allowing you to see the new IP address.
</p>
<br />
