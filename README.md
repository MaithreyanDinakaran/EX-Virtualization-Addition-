## Virtualization with Linux Commands
## Objective:

Install and configure Kali Linux in Oracle VM VirtualBox.
## Pre-requisites:

A system with Oracle VM VirtualBox installed.
    
At least 4 GB RAM and 20 GB free disk space.

Kali Linux ISO image, which can be downloaded from the official website.
    

## Step-by-Step Installation Guide:
## Step 1: Download Kali Linux ISO
1.Go to the Kali Linux download page.

2.Download the Kali Linux ISO file.

Choose between 32-bit or 64-bit depending on your system (most systems are 64-bit).

Download the Installer version for a full installation.

## Step 2: Open Oracle VM VirtualBox
Launch VirtualBox on your computer.

![376927707-de807551-50dd-4024-8746-9dda684bc697](https://github.com/user-attachments/assets/51c0bf2d-4936-4239-93ab-c15bc3a5cb59)

## Step 3: Create a New Virtual Machine
1.In VirtualBox, click on the New button to create a new virtual machine.

2. Name and Type Settings:

   Name: Give a name like "Kali Linux".
   Type: Select Linux.
   Version: Select Debian (64-bit) or Debian (32-bit) depending on the ISO version you downloaded.
   
3.Click Next to proceed.


## Step 4: Allocate Memory (RAM)
1.Choose how much RAM to allocate to your virtual machine.
 Recommended: At least 2 GB (2048 MB) for Kali Linux, or 4 GB if possible.
        
2.Click Next.

## Step 5: Create a Virtual Hard Disk
1.Select Create a virtual hard disk now.

2.Click Create.

## Step 6: Select Hard Disk File Type
1.Choose VDI (VirtualBox Disk Image).

2.Click Next.

## Step 7: Storage on Physical Hard Disk
1.Select Dynamically allocated (so the disk will grow as needed).
2.Click Next.

## Step 8: Allocate Storage Space
1.Set the hard disk size. Kali Linux requires at least 20 GB of storage.
 You can increase this if you plan to install many additional tools later.
        
2.Click Create.

## Step 9: Configure Kali Linux ISO

1.Select the VM from the list in VirtualBox and click Settings.

2.Navigate to Storage from the side menu.

3.Under Controller: IDE, click the Empty CD icon.

4.On the right, click the CD icon next to Optical Drive and choose Choose a disk file....

5.Locate and select the Kali Linux ISO you downloaded.

6.Click OK.


## Step 10: Start the Virtual Machine
 In VirtualBox, click Start to boot up your Kali Linux virtual machine.

![376919257-78e3d1cd-0555-433c-be26-008f79b590a0](https://github.com/user-attachments/assets/664d4cec-70a4-40f5-b052-da3b1a1606e6)



## Step 11: Begin Kali Linux Installation

1.The VM will now boot from the ISO. You’ll see a boot menu.
Select Graphical Install and press Enter.


![Screenshot (39)](https://github.com/user-attachments/assets/d599ebdb-6a8a-4751-8589-947a25a50de7)
        

## Step 12: Select Language and Region
Choose your language, location, and keyboard layout.

These can be configured to your preference.

Click Continue after each selection.

## Step 13: Configure the Network


You’ll be prompted to configure the network.

Enter a hostname for your system (e.g., kali).

You can leave the domain name empty if you don’t need to set up a domain.

## Step 14: Set Up Users and Passwords
Create a root password for the administrator account.

Choose a strong password and re-enter it for confirmation.

## Step 15: Partition Disks
Choose Guided - use entire disk for simplicity (recommended for beginners).

Select the virtual disk you created earlier.

Choose All files in one partition.

Finish partitioning and confirm to write the changes to disk.

## Step 16: Install the System
The installer will now copy files and install Kali Linux. This may take several minutes.

## Step 17: Install GRUB Bootloader
When prompted to install the GRUB bootloader, choose Yes.

Select the virtual hard disk as the location to install GRUB.

## Step 18: Complete Installation
After the installation is complete, click Continue to reboot the virtual machine.

## Step 19: Login to Kali Linux
Once the machine reboots, you’ll be presented with a login screen.

Log in using the root account and the password you set earlier.


## OUTPUT
# Arithmetic operations on 2 numbers METHOD
# PROGRAM
```
read -p "Enter first number: " num1
read -p "Enter second number: " num2
sum=$((num1 + num2))
diff=$((num1 - num2))
prod=$((num1 * num2))
quot=$((num1 / num2))
rem=$((num1 % num2))
echo "Sum: $sum"
echo "Difference: $diff"
echo "Product: $prod"
echo "Quotient: $quot"
echo "Remainder: $rem"
```
# OUTPUT

![Screenshot (40)](https://github.com/user-attachments/assets/e61fe3ca-68a2-4499-a5a3-596185a55ac2)



## TERMINAL METHOD
# OUTPUT

![Screenshot (42)](https://github.com/user-attachments/assets/7f22bfa6-d65e-4926-b4b6-027cd70b3d43)

## CHMOD METHOD

![421385981-915d0ee0-755f-4dbc-ac0e-cbdea76ecafe](https://github.com/user-attachments/assets/77150fbe-7858-4bbe-8d4b-4fb0c402762d)



## LINUX COMMANDS
![421384516-52253944-6c87-4440-a2a6-4e2c6fad618f](https://github.com/user-attachments/assets/d6e6d2a6-4109-477f-811c-01cd5b34ee85)

## RESULT
Thus, this experiment helped in understanding the fundamentals of Linux commands and Bash scripting for automation and system management.
