<h1>Active Directory 🔒🖥</h1>

<h2><i>Description</h2></i>
<h3>Active Directories are used to store data items on your local network. The service maintains a structured database of information on users, devices, applications, groups, and devices.The data's structure enables one place (home office or enterprise) to access information about all network-connected resources. In essence, Active Directory functions as a network phonebook that makes it simple to find and manage devices.</h3>

<h2>Environments & Utilites used:</h2>
<li><a href="https://www.virtualbox.org/wiki/Downloads"> Oracle Virtual Box</li></a>
<li><a href="https://www.microsoft.com/en-us/evalcenter/download-windows-server-2019"> Server 2019 ISO</li></a>
<li><a href="https://www.microsoft.com/en-us/software-download/windows10ISO"> Windows 10 ISO</li></a>
<li>Powershell</li>

<h2>Step 1: Installation</h2>
Install Windows 10 ISO, Server 2019 and Oracle Virtual Box. Make sure to pick the appropriate version for your device!
Windows 10 ISO and Server 2019 both come with extensions you have to download as well for them to operate.

<h2>Step 2: Create the Server 2019 Computer First:</h2>
Open Virtual Box and name it something simple such as "dc" for domain controller and choose the windows 64-bit option and continue. Decide on the proper amount of RAM you want to dedicate to the server (depending on your device specs). Once done, go ahead and create the disk with the default settings. You must also change Network settings so that this VM is able to connect to you home/work internet. To do that head to 'Network'->'Adapter 1' ->'Attached to:' & select <b>Internal Network</b>. Now that your RVM is configured you can go boot it up and you can set it up as you would a regular Windows Desktop. Since its our default administrator account we can give it a simple password (ex. 'Password1').
<p align = left><img src = "Create Server 2019.png" height="50%" width="50%"></p>

<h2> Side Notes </h2>
To make navigating the virtual machine a bit easier you can adjust "Advanced Settings" such as:
<li><i> Share Clipboard & Drag'nDrop</li></i>
<h6><i> **Switching these to 'bidirectional' will help your VM run smoother**</i></h6>

