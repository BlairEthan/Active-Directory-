<h1>Active Directory 🔒🖥</h1>

<h2><i>Description</h2></i>
<h3>Active Directories are used to store data items on your local network. The service maintains a structured database of information on users, devices, applications, groups, and devices.The data's structure enables one place (home office or enterprise) to access information about all network-connected resources. In essence, Active Directory functions as a network phonebook that makes it simple to find and manage devices.</h3>

<h2>Environments & Utilites used:</h2>
<li><a href="https://www.virtualbox.org/wiki/Downloads"> Oracle Virtual Box</li></a>
<li><a href="https://www.microsoft.com/en-us/evalcenter/download-windows-server-2019"> Server 2019 ISO</li></a>
<li><a href="https://www.microsoft.com/en-us/software-download/windows10ISO"> Windows 10 ISO</li></a>
<li>Powershell</li>


<h2> Step 1 <h2>Choose a physical or virtual machine to install Windows Server on. Make sure it meets the system requirements for Windows Server.
<h2> Step 2 <h2>Install Windows Server on the machine.
<h2> Step 3 <h2>Configure a static IP address for the machine. You can do this by going to Control Panel > Network and Sharing Center > Change adapter settings > right-click on your network adapter > Properties > Internet Protocol Version 4 (TCP/IPv4) > Properties. Enter the IP address, subnet mask, default gateway, and DNS server addresses.
<h2> Step 4 <h2>Rename the machine to a unique name that you will use to identify it in your lab.
<h2> Step 5 <h2>Install Active Directory Domain Services (AD DS) on the machine. You can do this by opening Server Manager > Add Roles and Features > Role-based or feature-based installation > select the server > select Active Directory Domain Services.
<h2> Step 6 <h2>Once AD DS is installed, open the Active Directory Domain Services Configuration Wizard. You can do this by clicking on the yellow exclamation mark in the Server Manager dashboard, or by opening Server Manager > Tools > Active Directory Domain Services Configuration Wizard.
<h2> Step 7 <h2>Follow the prompts in the wizard to configure the domain name and NetBIOS name. You can use a domain name that you own, or a domain name that you create specifically for your lab. Make sure the domain name is unique and does not conflict with any existing domain names on the internet.
<h2> Step 8 <h2>Once the wizard is complete, you will have a new Active Directory domain running on your machine. You can use Active Directory Users and <h2> Step 9 <h2>Computers to create user accounts, group policies, and other Active Directory objects.
<h2> Step 10 <h2>Create a test user account and a test group, and assign the user account to the group.
<h2> Step 11 <h2>Join a client computer to the domain. You can do this by opening Control Panel > System > Change settings > Change > select "Domain" > enter the domain name you created in step 7 > enter the credentials of a domain administrator account.


