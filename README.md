<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Installation</h1>
This tutorial outlines the prerequisites and installation of the open-source help desk ticketing system osTicket.<br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of Prerequisites</h2>

- Install IIS with CGI
- Download and install installation files
- Create a "PHP" file in the C drive and unzip "PHP 7.3.8" in it.
- Setup MySQL
- Register PHP from within IIS
- Install osTicket
- Go to site

<h2>Installation Steps</h2>

<p>
<img src="https://i.imgur.com/uhCYxdl.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Open the control panel. Navigate to programs and features. Go to turn "Windows features on or off". Enable and drop down "Internet Information Services" (IIS), drop down "World Wide Web services" and "Application Development Features". Then enable "CGI".
</p>
<br />

<p>
<img src="https://i.imgur.com/kTqOdKo.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Download and install "PHP manager for IIS", "Rewrite Module","PHP 7.3.8","VC_redist.x86.exe","MySQL 5.5.62".
</p>
<br />

<p>
<img src="https://i.imgur.com/bVDEDQc.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Start MySQL setup. Do a typical setup. Launch config wizard. Standard configuration. Set Password
</p>
<br />

<p>
<img src="https://i.imgur.com/6aP5cER.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Luanch IIS as an admin. Register PHP from within IIS. Reload IIS.
</p>
<br />

<p>
<img src="https://i.imgur.com/MntfHMx.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Download osTicket. Extract and copy “upload” folder to c:\inetpub\wwwroot. Within c:\inetpub\wwwroot, Rename “upload” to “osTicket”. Reload IIS.
</p>
<br />

<p>
<img src="https://i.imgur.com/ZEos0p0.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
In IIS go to sites. drop down default web site. select osTicket. Click link under Browse folder.
</p>
<br />
