Installation Steps

1. Open VirtualBox 
Launch VirtualBox on your host machine.

2. Create a New Virtual Machine ( you can use any software for virtual machine, in this workshop we are using oracle vm box) 
Click on "New" to create a new virtual machine.
Enter a name for your virtual machine (e.g., "pfSense").
Choose "BSD" as the type and "FreeBSD (64-bit)" as the version.

3. Assign Memory (RAM) 
Choose the amount of RAM to allocate to the virtual machine. Recommended: 2048 MB or more.

4. Create a Virtual Hard Disk
Select "Create a virtual hard disk now" and click "Create."
Choose "VDI (VirtualBox Disk Image)" as the hard disk file type.
Choose "Dynamically allocated" for storage on physical hard disk.

5. Set Virtual Disk Size
Choose the size of the virtual hard disk. Recommended: 10 GB or more.
Click "Create" to finish creating the virtual machine.

6. Attach pfSense ISO ( you can download the latest version of pfsense iso file from the link : "https://www.pfsense.org/download/")
With the new virtual machine selected, click on "Settings."
Under the "System" tab, move "Optical" to the top in the "Boot Order" section.
Under the "Storage" tab, click on the empty disk icon next to "Controller: IDE" and choose the pfSense ISO file you downloaded.

7. Start the Virtual Machine
Click "Start" to launch the virtual machine.
The pfSense installation menu will appear.

8. Install pfSense (if you are facing any difficulties during installation, feel free to reach us.)
Select "Install" from the menu.
Follow the on-screen instructions to complete the installation.
Set up network interfaces, IP addresses, and other configurations as needed.

9. Complete Installation
Once the installation is complete, the virtual machine will prompt you to remove the installation medium (ISO).
Remove the ISO and press "Enter" to reboot.

10. Log in to pfSense
Access pfSense through the web interface using a web browser. 
Default login credentials: Username - "admin," Password - "pfsense."

Additional Configuration (Optional)
Update pfSense: Navigate to "System" > "Update" to apply the latest updates.
Configure firewall rules, NAT, VPN, and other settings as per your network requirements