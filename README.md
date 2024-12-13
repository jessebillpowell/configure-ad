<p align="center">
<img src="https://i.imgur.com/pU5A58S.png" alt="Microsoft Active Directory Logo"/>
</p>

<h1>Preparing Active Directory Infrastructure in the Cloud (Azure)</h1>
This tutorial outlines the implementation of on-premises Active Directory within Azure Virtual Machines.<br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Active Directory Domain Services
- PowerShell

<h2>Operating Systems Used </h2>

- Windows Server 2022
- Windows 10 (21H2)

<h2>High-Level Deployment and Configuration Steps</h2>

- Step 1
- Step 2
- Step 3
- Step 4

<h2>Deployment and Configuration Steps</h2>

<p>
<img src="https://i.imgur.com/31Gks58.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
For step 1, I created Resources in Microsoft Azure so that Virtual machines could run to start the process of configuring Active Directory. I created a Domain Controller virtual machine in Azure, using Windows Server 2022. Also, I created a Resource Group along with a virtual network. Next, a Client Virtual Machine was created in Azure using a Microsoft Windows 10 platform. The Client Virtual Machine, called Client-1, The Domain Controller, called DC-1, and a virtual network that was created, were all stored in the same Resource Group.  
</p>
<br />

<p>
<img src="https://i.imgur.com/aqogZ52.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
For step 2, we want to login to Client-1 with Remote Desktop and execute a perpetual ping to DC-1'S private IP  address with ping -t. Then, enable ICMPv4 (ping) in the local windows Firewall settings. Afterwards, goto Client-1's virtual machine to ensure that the ping succeeded and that their is a connection between the Client machine and the Domain Controller.
</p>
<br />

<p>
<img src="https://i.imgur.com/UHUgRQn.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>

</p>
<br />
