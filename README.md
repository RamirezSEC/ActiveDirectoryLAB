<h1>Active Directory Home Lab</h1>

<h2>Description</h2>
This lab demonstrates the deployment and management of a Windows Active Directory Domain Services (AD DS) environment in a virtualized Lab. The goal of this lab was to gain hands-on experience with identity and access management (IAM), Windows domain infrastructure, and basic security monitoring in an enterprise-style setup.

The environment was built using Oracle VirtualBox and simulates common administrative and security tasks performed by system administrators and SOC analysts.
<br />

<h2>Languages</h2>

- <b>PowerShell</b> 

<h2>Virtualization Enviornment</h2>

- <b>VirtualBox</b>

<h2>Operating Systems</h2>

- <b>2019 Windows Server (Domain Controller)</b>
- <b>Windows 10 (Domain Client)</b>

<h2>Directory & Infrastructure Services</h2>

- <b>Active Directory Domain Services (AD DS)</b>
- <b>DNS</b>
- <b>DHCP</b>

<h2>Program walk-through:</h2>

<p align="center">
Download VirtualBox: <br/>
<img src="https://i.imgur.com/TZQP6vz.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Download VirtualBox Extention Pack:  <br/>
<img src="https://i.imgur.com/8JSyXeX.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Download Windows Server2019 ISO: <br/>
<img src="https://i.imgur.com/d2la4h6.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Download Windows 10 ISO:  <br/>
<img src="https://i.imgur.com/lkeF0E1.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Follow these steps to create ISO file (Make sure to select "ISO file" & save to desktop or somewhere you wont forget):  <br/>
<img src="https://i.imgur.com/3UTXHcO.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Open VirtualBox and click New:  <br/>
<img src="https://i.imgur.com/2oSIdLE.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Use these settings to setup Windows Server VM / Select Finish:  <br/>
<img src="https://i.imgur.com/RYBxoE1.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/SvgNCNH.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/Ts8iBUM.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Right click the VM you just created (DC) and click settings: 

 - Make sure you are on the Expert tab> General> Click on Features
 - Set both the Shared Clipboard & Drag and Drop to "Bidirectional"  <br/>
<img src="https://i.imgur.com/d13qgiV.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<p align="center">
Under Settings go to Network and click Adapter 1: 

- Check the box to Enable Network Adapter
- Set the Attached to option to "NAT"  <br/>
<img src="https://i.imgur.com/JA9s4b5.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
Select Adapter 2:

- Check the box to Enable Network Adapter
- Set the Attached option to "Internal Network"
- Press OK.  <br/>
<img src="https://i.imgur.com/m4sf1ra.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Under Settings go to Network and click Adapter 1: <br/>
<img src="https://i.imgur.com/nCIbXbg.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
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
