# Microsoft Sentinel Honeypot Project #
Overview:

This project leverages a Windows based virtual machine created in Azure with open ports to allow inbound traffic from anywhere on the internet. This creates a 'honeypot' to draw in traffic purposefully to the computer, inviting would be attackers. The purpose of this project is to familiarise myself with the inner workings of Microsoft Sentinel and to make use of the SIEM in order to monitor any connection attempts by threat actors.

I utilised a custom PowerShell script which exports the event logs from the VM and works in conjunction with the 'extract' feature in the Log Analytics Workspace, in order to enumerate the data and display the geographic location for incoming attacks and display them in a readable format via Workbooks with Sentinel.

## **Tools:** ##
- **Microsoft Sentinel (SIEM)**
  - Workbooks
- **Virtual Machines**
  - Microsoft Windows 11
  - 'HoneyPotLab' Resource Group
  - Log Analytics Workspace (LAW)
  - Network Security Group
- **Microsoft Defender for Cloud**
  - Defender Plans/Data Collection

![image](https://github.com/user-attachments/assets/83634ffd-0fa0-4da3-8dc2-183afaff26cd)

<!-- 

Project created following this video by Josh Madakor on YouTube:

"SIEM Tutorial for Beginners | Azure Sentinel Tutorial MAP with LIVE CYBER ATTACKS!"
https://www.youtube.com/watch?v=RoZeVbbZ0o0 

-->
