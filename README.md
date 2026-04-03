<h1>Active Directory Home Lab</h1> 


<h2>Description</h2> 

This project demonstrates the deployment and management of a Windows Active Directory Domain Services (AD DS) environment in a virtualized lab. The goal was to gain hands-on experience with identity and access management (IAM), Windows domain infrastructure, and enterprise-level system administration tasks. The lab simulates real-world environments used by IT support and security professionals.

<h2>Technologies Used</h2>

- Oracle VirtualBox
- Windows Server 2019
- Windows 10
- PowerShell

<h2>Core Services Configured</h2>

- Active Directory Domain Services (AD DS)
- DNS (Domain Name System)
- DHCP (Dynamic Host Configuration Protocol)

<h2>Lab Architecture</h2>

- Configured a Domain Controller with dual network interfaces (NAT + Internal Network)
- Established a private internal network for domain communication
- Connected a Windows 10 client machine to the domain environment

<h2>Key Configurations & Tasks</h2>

- Installed and configured Active Directory Domain Services (AD DS)
- Promoted the server to a Domain Controller
- Configured DNS and DHCP services for internal network management
- Created and managed users and security groups
- Automated bulk user creation using PowerShell
- Joined a client machine to the domain
- Verified domain authentication and connectivity


<h2>Real-World Scenarios Simulated</h2>

- User account creation and management
- Group-based access control
- Domain login authentication troubleshooting 

<h2>Screenshots</h2>

<p align="center">
This diagram illustrates a virtual Active Directory environment consisting of a Domain Controller and a client machine. The Domain Controller provides AD DS, DNS, and DHCP services, while the client connects to the internal network and authenticates through the domain:  <br/>
<img src="https://i.imgur.com/oVfbAbG.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
 Windows Server configured as a Domain Controller with Active Directory Domain Services installed, along with DNS and DHCP for domain management: <br/>
<img src="https://i.imgur.com/rtMOYC0.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/D30xVEI.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
PowerShell script used to automate bulk creation of Active Directory users from a list of names:  <br/>
<img src="https://i.imgur.com/wkH05ak.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Active Directory Users & Computers showing users created automatically via PowerShell and organized into OUs:  <br/>
<img src="https://i.imgur.com/j4a5vs0.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Windows 10 client machine successfully joined to the Active Directory domain, mydomain.com:  <br/>
<img src="https://i.imgur.com/22FwMw6.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Client machine IP configuration showing DHCP-assigned address and DNS pointing to the Domain Controller:  <br/>
<img src="https://i.imgur.com/Z846ttp.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Command prompt output showing authenticated domain user, verifying successful Active Directory login:  <br/>
<img src="https://i.imgur.com/MMutlFI.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />


<h2>What I Learned</h2>

This lab strengthened my understanding of identity and access management, domain services, and real-world IT support tasks in a Windows environment. It also improved my ability to troubleshoot authentication and network-related issues within a domain.


<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
