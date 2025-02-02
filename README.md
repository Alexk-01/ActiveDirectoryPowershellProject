<h1>Active Directory Powershell Project</h1>


<h2>Description</h2>
This project involves setting up a Windows Server 2019 Domain Controller (DC) that manages an internal network. The DC handles RAS/NAT and DHCP services, connecting to both the internet and an internal client running Windows 10. A key feature of this project is the automation of adding 1,000 users to Active Directory (AD) using a PowerShell script from Github.
<br />


<h2>Environments Used </h2>

- <b>Windows 10</b> 
- <b>Windows Server 2019</b>
<h2>Program walk-through:</h2>


<p align="center">
Project Diagram: <br/>
<img src="https://raw.githubusercontent.com/Alexk-01/ActiveDirectoryPowershellProject/refs/heads/main/ActiveDirectoryPowershellProject/Screenshot%202024-08-25%20100203.png"/>
<br />
<br />
Configured the IP address for Internal NIC:  <br/>
<img src="https://raw.githubusercontent.com/Alexk-01/ActiveDirectoryPowershellProject/refs/heads/main/ActiveDirectoryPowershellProject/Screenshot%202025-02-01%20095623.png"/>
<br />
<br />
Installed Active Directory Domain Services and created a domain: (AD DS): <br/>
<img src="https://raw.githubusercontent.com/Alexk-01/ActiveDirectoryPowershellProject/refs/heads/main/ActiveDirectoryPowershellProject/Screenshot%202025-02-01%20100621.png"/>
 <br />
<img src="https://raw.githubusercontent.com/Alexk-01/ActiveDirectoryPowershellProject/refs/heads/main/ActiveDirectoryPowershellProject/Screenshot%202025-02-01%20103108.png"/>
<br />
<br />
Created a Domain admin account :  <br/>
<img src="https://raw.githubusercontent.com/Alexk-01/ActiveDirectoryPowershellProject/refs/heads/main/ActiveDirectoryPowershellProject/Screenshot%202025-02-01%20103703.png"/>
<br />
<br />
Configured Remote Access Server (RAS) & Network Address Translation (NAT) which creates a private virtual network that accesses the internet through the Domain Controller for the Client machine:  <br/>
<img src="https://raw.githubusercontent.com/Alexk-01/ActiveDirectoryPowershellProject/refs/heads/main/ActiveDirectoryPowershellProject/Screenshot%202025-02-01%20105516.png"/>
 
 <img src="https://raw.githubusercontent.com/Alexk-01/ActiveDirectoryPowershellProject/refs/heads/main/ActiveDirectoryPowershellProject/Screenshot%202025-02-01%20111044.png"/>
 
<br />
<br />
Configured DHCP service & IP address range, which allows the Windows 10 client machine to get an IP address to access the internet:  <br/>
<img src="https://raw.githubusercontent.com/Alexk-01/ActiveDirectoryPowershellProject/refs/heads/main/ActiveDirectoryPowershellProject/Screenshot%202025-02-01%20112102.png"/> 
<img src="https://raw.githubusercontent.com/Alexk-01/ActiveDirectoryPowershellProject/refs/heads/main/ActiveDirectoryPowershellProject/Screenshot%202025-02-01%20113212.png"/>
<br />
<br />
 
This PowerShell script is designed to automate the creation of Active Directory (AD) users. It reads a list of names from a file, splits each name into first and last names, and then uses these details to create a new AD user for each entry. :  <br/>
<img src="https://raw.githubusercontent.com/Alexk-01/ActiveDirectoryPowershellProject/refs/heads/main/ActiveDirectoryPowershellProject/Screenshot%202025-02-01%20124314.png"/>
<br />
<img src="https://raw.githubusercontent.com/Alexk-01/ActiveDirectoryPowershellProject/refs/heads/main/ActiveDirectoryPowershellProject/Screenshot%202025-02-01%20131459.png"/>
<br />
Testing configurations on client machine  :  <br/>
<img src="https://i.imgur.com/CScphL9.png"/>
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
