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
 Enable: php_imap.dll
Enable: php_intl.dll
Enable: php_opcache.dll

</p>
<br />

<p>


