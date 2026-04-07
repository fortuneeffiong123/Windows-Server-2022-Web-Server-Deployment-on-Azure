# Windows-Server-2022-Web-Server-Deployment-on-Azure
Deploying and Hosting a Web Server Using Windows Server 2022 on Microsoft Azure
This project demonstrates a step-by-step deployment of a Windows Server 2022 virtual machine on Microsoft Azure, configuring remote access via RDP (Remote Desktop Protocol), installing Internet Information Services (IIS), and hosting a publicly accessible web page.

The purpose of this project is to showcase practical skills in cloud infrastructure, Windows Server administration, networking, and web server setup in a hands-on Azure environment.

**Objectives**
Deploy a Windows Server 2022 VM on Azure
Configure secure RDP access (port 3389)
Install and configure IIS web server
Host and verify a live web page accessible from the internet
**Tools & Technologies**
Cloud Platform: Microsoft Azure
Operating System: Windows Server 2022
Web Server: Internet Information Services (IIS)
Protocol: RDP (Remote Desktop Protocol)
Networking: Public IP, Network Security Group (NSG)
**Implementation Steps**
Create Resource Group in Azure for organization
Deploy Windows Server 2022 VM with public IP and allowed inbound ports
Connect via RDP from local computer
Install IIS using Server Manager
Verify web page locally with http://localhost
Test public access using the VM's public IP
**Screenshots**
 images of Virtual Machine creation and deployment, 
<img width="1177" height="936" alt="image" src="https://github.com/user-attachments/assets/b20dd07c-0cdc-4bec-8584-7559634365fb" />

 IIS default web page
![WINDOW2022 Image](https://github.com/user-attachments/assets/01ff9c52-4415-417d-8bd9-bbe15f66690c)

**Architecture Overview**
User (Browser)  → Internet → Azure Public IP → NSG → Windows Server 2022 VM → IIS → Web Page


**Key Outcomes**
Successfully deployed a cloud-based Windows Server VM
Configured secure remote administration using RDP
Installed and managed IIS web server
Hosted a publicly accessible webpage for verification


**Skills Demonstrated**
Azure Cloud Computing
Windows Server Administration
Remote Desktop & Networking Configuration
IIS Web Server Installation & Management
Cloud Infrastructure Deployment
