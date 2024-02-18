<h1>SIEM + Honey Pot</h1>

<h2>Description</h2>
I setup Azure Sentinel (SIEM) and connect it to a live virtual machine acting as a honey pot. We will observe live attacks (RDP Brute Force) from all around the world. We will use a custom PowerShell script to look up the attackers Geolocation information and plot it on the Azure Sentinel Map!
<br />


<h2>Utilities Used</h2>

- <b>PowerShell</b>
- <b>Azure Sentinel</b>
- <b>Log Analytics Workspace</b>
- <b>KQL</b>

<h2>Environments Used </h2>

- <b>Azure</b>
- <b>Windows 10</b> (21H2)

<h2>Program walk-through:</h2>

<p align="center">
Azure Setup: <br/>
<img src="https://i.imgur.com/VhqSfrQ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Setting Up NIC or Firewall:  <br/>
<img src="https://i.imgur.com/p7R69ga.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Inbound Rules: <br/>
<img src="https://i.imgur.com/wfvI2UW.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
VM Being Created:  <br/>
<img src="https://i.imgur.com/4xX0ONi.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Log analytics workspace creation:  <br/>
<img src="https://i.imgur.com/ZT4zr3u.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Enable VM gathering logs:  <br/>
<img src="https://i.imgur.com/80rrJvL.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Log into VM with remote desktop:  <br/>
<img src="https://i.imgur.com/mUHTP4n.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
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
