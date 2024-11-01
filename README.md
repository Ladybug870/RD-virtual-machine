<p align="center">
<img src="https://i.imgur.com/9Q5uoKu.png" alt="Microsoft Active Directory Logo"/>
</p>

<h1>Remote Desktop Connection on a VM (Azure)</h1>
This tutorial outlines using the remote desktop application on a windows PC to connect to a virtual machine.<br />



<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop


<h2>Operating Systems Used </h2>


- Windows 10 (21H2)



<h2>Deployment and Configuration Steps</h2>

<p>
<img src="https://i.imgur.com/2nKPLD7.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
If not opened already, go to your broswer and login to your Azure account. Select your virtual machine that you created. 
</p>
<br />

<p>
<img src="https://i.imgur.com/UUvYS37.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Now you are viewing the overview of your VM that you created. Find it's public IP address and copy it. 
</p>


<br />

<p>
<img src="https://i.imgur.com/Ee7hpO1.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Minimize your browser and select the search bar at the bottom left hand corner of your screen. 

Type in RDC or Remote Desktop Connection, click application. Paste in the IP address you copied from your VM then click connect. 

<img src="https://i.imgur.com/i8WzFB9.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
Enter in the username and password combo that you created and wrote down while making your virtual machine, then click ok. Tada! Now you have remote access to the virtual machine you made!!!

<img src="https://i.imgur.com/mNjJtDU.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
