# Global-RDP-Attack-Visualizer
This is a repository where we visualize the RDP attacks from all over the world over a vulnerable machine. 

We use MS Azure as our platform for this project.

We have to create an account in https://azure.microsoft.com/en-in/get-started/azure-portal/  It's free for students, otherwise you may have to pay to purchase the credits.

You can refer Images folder where all the screenshots of the Azure settings and the process is provided. 

### The main highlights of the procedure is - 
1. Create a VM in MS Azure with minimum specifications in any region(like Asia-Pacific).
2. You will get an IP address for the VM. you can access the VM using the Remote Desktop Connection in Windows. 
3. Make the VM vulnerable by removing any existing default inbound rule and switching off the firewalls. Establish the rule that any machine can iinteract with the VM.
4. Go to Microsoft Defender for Cloud and disable all the protection features.
5. We will create custom logs about the latitude,longitude,country,timestamp etc...
6. Go to Azure Sentinel(Microsoft SIEM) and it will show all the attacks being carried by various machines on our VM as Security events in a graphical manner. 
7. We take the real time data collected by Azure Sentinel and plot it in the world map using Microsoft Workbook.
8. This map shows the real time attacks carried out from various countries. 

### Thank you😊

