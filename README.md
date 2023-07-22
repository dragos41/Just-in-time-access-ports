# Just-in-time-access-ports
## Secure ports with JIT
Just-in-time access (JIT) can help reduce this exposure and in this exercise you will implement JIT so that SSH and RDP sessions can be used to manage a virtual machine.

### Step 1 : Enable Azure Defender for Cloud

* From the Azure home page, search for and select  Virtual machines.

* Select the SamScoopsWeb virtual machine.

* Select Configuration from the left-hand side menu.

* Select Upgrade your Microsoft Defender for Cloud subscription to enable a just-in-time access.

* Select Upgrade on the Microsoft Defender for Cloud page.

* Select continue without installing agents on the right-hand side.

### Step 2 : Enable JIT access
* From the Azure home page, search for and select Virtual machines.

* Select the SamScoopsWeb virtual machine 

* In the left-hand menu, select Configuration.

* Select Enable just-in-time.

### Step 3 : Configure JIT policies for SSH and RDP from Microsoft Defender for Cloud
* From the SamScoopsWeb Configuration page select Open Microsoft Defender for Cloud.

* From the  Configured  tab, right-click on the VM to which you want to add a port, and select edit.

* To add SSH select Add and add the port number for SSH which is 22.

* Select TCP and leave the defaults.

* Select OK.

### Step 4 : Test remote access
* Select Microsoft Azure at the top of the page to take you back to the portal home page.

* Search for and select  Virtual machines.

* Select the SamScoopsWeb virtual machine.

* Select Start to power on the virtual machine from the top of the page.

* Select Connect on the left-hand menu.

* Select Request access.

* Select Download RDP file.

* Select the downloaded RDP file from your downloads folder.

* Select Connect.

* Enter the username AzAdmin and password P@$$@1234567 and select OK.

You have now connected to the webserver using JIT access.
