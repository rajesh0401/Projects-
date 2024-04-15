Installation Steps

1. Open VirtualBox ( you can use any software for virtual machine, in this workshop we are using oracle vm box) 
Launch VirtualBox on your host machine.

2. Create a New Virtual Machine
Click on "New" to create a new virtual machine.
Enter a name for your virtual machine (e.g., "Kali Linux").
Choose "Linux" as the type and "Debian" as the version.

3. Assign Memory (RAM)
Choose the amount of RAM to allocate to the virtual machine. Recommended: 2048 MB or more.

4. Create a Virtual Hard Disk
Select "Create a virtual hard disk now" and click "Create."
Choose "VDI (VirtualBox Disk Image)" as the hard disk file type.
Choose "Dynamically allocated" for storage on physical hard disk.

5. Set Virtual Disk Size
Choose the size of the virtual hard disk. Recommended: 20 GB or more.
Click "Create" to finish creating the virtual machine.

6. Attach Kali Linux ISO - install the kalilinux software from the link: "https://www.kali.org/get-kali/#kali-installer-images"
With the new virtual machine selected, click on "Settings."
Under the "System" tab, move "Optical" to the top in the "Boot Order" section.
Under the "Storage" tab, click on the empty disk icon next to "Controller: IDE" and choose the Kali Linux ISO file you downloaded.

7. Start the Virtual Machine
Click "Start" to launch the virtual machine.
Kali Linux installation menu will appear.

8. Install Kali Linux - if you are facing any difficulties during installation, feel free to reach us. 
Select "Install" from the menu.
Follow the on-screen instructions to complete the installation.
Set up your user account and password when prompted.

9. Complete Installation
Once the installation is complete, the virtual machine will prompt you to remove the installation medium (ISO).
Remove the ISO and press "Enter" to reboot.

10. Log in to Kali Linux
Log in with the credentials you set during the installation.

Additional Configuration (Optional)
Update Kali Linux: Open a terminal and run sudo apt update && sudo apt upgrade.
Install VirtualBox Guest Additions for improved integration.