<h1>Active Directory Powershell Project</h1>


<h2>Description</h2>
This project involves setting up a Windows Server 2019 Domain Controller (DC) that manages an internal network. The DC handles RAS/NAT and DHCP services, connecting to both the internet and an internal client running Windows 10. A key feature of this project is the automation of adding 1,000 users to Active Directory (AD) using a PowerShell script from Github.
<br />


<h2>Languages and Utilities Used</h2>

- <b>PowerShell</b> 
- <b>Virtual Box</b>

<h2>Environments Used </h2>

- <b>Windows 10</b> 
- <b>Windows Server 2019</b>
<h2>Program walk-through:</h2>


<p align="center">
Project Diagram: <br/>
<img src="https://i.imgur.com/Z0Y6hP3.png"/>
<br />
<br />
Configured the IP address for Internal NIC (Domain Controller serves as a default gateway):  <br/>
<img src="https://i.imgur.com/k2awhwD.png"/>
<br />
<br />
Installed Active Directory Domain Services (AD DS): <br/>
<img src="https://i.imgur.com/2cp9Kis.png"/>
<br />
<br />
Confirm your selection:  <br/>
<img src="https://i.imgur.com/cdFHBiU.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Wait for process to complete (may take some time):  <br/>
<img src="https://i.imgur.com/JL945Ga.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Sanitization complete:  <br/>
<img src="https://i.imgur.com/K71yaM2.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Observe the wiped disk:  <br/>
<img src="https://i.imgur.com/AeZkvFQ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
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
