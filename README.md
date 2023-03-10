# osticket-prereqs
<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>




<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of Prerequisites</h2>



* Add Internet Information Services
* Add MySQL 5.5
* Add all simple versions of x86 PHP up to v7.3
* Install osTicket v1.15.8
* Reload IIS (open IIS, Stop and Start the server)
* Enable extensions in IIS
* Refresh the osTicket site in your browser and observe the changes
* Clean up files for optimal use

<h2>Installation Steps</h2>

<p>
<img src="https://i.imgur.com/x92zuuZ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Install and Enable IIS in Windows
</p>
<br />
<p>
<img src="https://i.imgur.com/lu1bA7K.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
 Navigate to 127.0.0.1 to check that web server is running
</p>
<br />

<p>
<img src="https://i.imgur.com/Hcc0dL9.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Step 3 Install MySQL
</p>
<br />

<p>
<img src="https://i.imgur.com/IGtnJsB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Step 4 Run IIS as Admin </p>
<br />

<p>

<p>
<img src="https://i.imgur.com/9RKO3oT.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Step 5 Register New PHP Version w fast CGI
</p>
<br />

<p>
<img src="https://i.imgur.com/bWhVqHr.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Step 6 Restart IIS</p>
<br />

<p>

<p>
<img src="https://i.imgur.com/OtMvxFz.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Step 7 Download OsTicket and Copy Upload Folder into Webserver's main folder
</p>
<br />

<p>
<img src="https://i.imgur.com/TXNWexd.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Step 8 rename upload folder to osTicket
</p>
<br />

<p>

<p>
<img src="https://i.imgur.com/BWQZYMX.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Step 9 Restart IIS. In IIS navigate to osticket folder click on 80* hyperlink
</p>
<br />

<p>
<img src="https://i.imgur.com/JPQExGD.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Step 10 Enable php extensions for osTicket functionality
( php_imap.dll, php_intl.dll , php_opcache.dll)

</p>
<br />

<p>

<p>
<img src="https://i.imgur.com/bRoRvVx.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Step 11 rename sample config to config
</p>
<br />

<p>
<img src="https://i.imgur.com/ZT5f8Nv.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Step 12 in the securities tab, Remove permissions. Then Grant Permissions to Everyone 
</p>
<br />

<p>

<p>
<img src="https://i.imgur.com/OEaCxKs.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Step 13 Continue Setting Up Os Ticket in Browser
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Step 14 Download HeidiSQL to access the mysql server
</p>
<br />

<p>

<p>
<img src="https://i.imgur.com/WqzGFhX.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Step 15 Connect to the Session
</p>
<br />

<p>
<img src="https://i.imgur.com/1sPFdok.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Step 16 Create a New Database Called OsTicket
</p>
<br />

<p>

 <p>
<img src="https://i.imgur.com/IdJJWjR.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<p>
Step 17 Cleanup Steps Delete Setup Folder in wwwroot folder
</p>
<br />

<p>
<img src="https://i.imgur.com/SiChEqz.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Step 18 in C navigate to wroot . osticket. include. ost-config and set permissions back to read only
</p>
<br />

<p>

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />





