<h1></h1>

 ### [YouTube Demonstration](https://youtu.be/AvRh61ei2n8?si=j9-1ym3XNZVIntpr)

<h2>Description</h2>
Creating an Active Directory (AD) environment in VirtualBox involves setting up a virtual machine with Windows Server 2019 privileges, installing the AD DS Role on Server Manager, & promoting it to a Domain Controller (DC). 


<h2>Prerequisites</h2>
- <b>Ensure you have VirtualBox installed and the Windows Server ISO (Windows Server 2019-<b>
- <b>Allocate at least 4GB RAM & 50 GB HDD-<b>

<br />

<h2>Languages & Utilities:</h2>

- <b> Oracle VirtualBox (www.virtualbox.org) </b>
- <b>VirtualBox Extension Pack (https://www.virtualbox.org/Downloads) </b>
- <b>Microsoft Server 2019 Evaluations ISO (https://info.microsoft.com/ww-landing-windows-server-2019.html)</b>
- <b>Microsoft Windows 10 Bootable USB ISO (https://support.microsoft.com/en-us/windows/create-installation-media-for-windows-99a58364-8c02-206f-aa6f-40c3b507420d) (for new workstations) </b>

<h2>Environments:</h2>

- <b>Active Directory</b>
- <b>Virtualization Machine - Oracle VirtualBox </b>


<h2>Step Demonstration:</h2>
<p align="center">
Install Server 2019 Evaluations Center ISO (Contains AD DS) : <br/>
<img src="https://i.imgur.com/H7eG02q.png" height="80%" width="80%" alt=
<br />
<br />
Install Oracle VirtualBox (Virtualization Tool): <br/>
<img src="https://i.imgur.com/FkbLDsc.png" height="80%" width="80%" alt= 
<br />
<br />
Mount the Server 2019 Evaluations ISO: <br/>
<img src="https://i.imgur.com/9vyAlM4.png" height="80%" width="80%" alt=
<br />
<br />
Create a Host Name, Domain Name, & User Account Credentials: <br/>
<img src="https://i.imgur.com/PkfaTpo.png" height="80%" width="80%" alt=
<br />
<br />
Configure New Virtual Machine & System (Windows) Settings: <br/>
<img src="https://i.imgur.com/DctXt3S.png" height="80%" width="80%" alt=
<br />
<br />
Finish the Windows Install & Start Virtual Machine:  <br/>
<img src="https://i.imgur.com/lkv3pcy.png" height="80%" width="80%" alt=
<br />
<br />
Open Server Manager & Install AD DS Role (Restart After):  <br/>
<img src="https://i.imgur.com/Tok2qqe.png" height="80%" width="80%" alt=
<br />
<br /> 
Promoting the server to a domain controller is a required step after this:  <br/>
<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>

