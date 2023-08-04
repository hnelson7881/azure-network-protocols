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

- Create some sample file shares with various permissions
- Attempt to access file shares as a normal user
- Create an “ACCOUNTANTS” Security Group, assign permissions, an test access
  

<h2>Actions and Observations</h2>

<p>
<img src="https://i.imgur.com/QAQWcAE.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Log in as an individual onto DC-1
</p>
<br />

<p>
<img src="https://i.imgur.com/31acIZj.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Sign back into Client-1 as <someuser> and try to access the “accounting” share in \\DC-1\ 

</p>
<br />

<p>
<img 
</p>
<p>

</p>
<br />
