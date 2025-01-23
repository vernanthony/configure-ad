<p align="center">
<img src="https://i.imgur.com/pU5A58S.png" alt="Microsoft Active Directory Logo"/>
</p>

<h1>On-premises Active Directory Deployed in the Cloud (Azure)</h1>




<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Active Directory Domain Services
- PowerShell

<h2>Operating Systems Used </h2>

- Windows Server 2022
- Windows 10 (21H2)

<h2>High-Level Deployment and Configuration Steps</h2>

- Deploy an Azure Virtual Machine (VM)
- Promote the VM to a Domain Controller
- Configure Networking and DNS
- Connect Resources to the Domain

<h2>Deployment and Configuration Steps</h2>

![Screenshot 2025-01-22 194152](https://github.com/user-attachments/assets/daccfd40-e499-43e3-be1e-72de2f8d5f78)


<p>
</p>
<p>
I deployed a virtual machine (VM) in Microsoft Azure, utilizing the Azure portal for configuration and deployment. The VM was set up with the desired specifications, including the operating system, CPU, memory, and storage options. After configuring networking settings, such as virtual networks and security groups, the VM was provisioned and made accessible for further configuration or application deployment.</p>
<br />

![Screenshot 2025-01-22 195322](https://github.com/user-attachments/assets/83914068-d54e-4580-a43e-e3ae17fc87d7)


<p>
</p>
<p>
I deployed a virtual machine (VM) in Microsoft Azure and installed Active Directory on a domain controller. The process involved configuring the VM's specifications, including the operating system, CPU, memory, and storage. Once the VM was provisioned, I set up Active Directory services, promoted the VM to a domain controller, and configured the necessary domain settings. </p>
<br />

![Screenshot 2025-01-22 195407](https://github.com/user-attachments/assets/21cfc0c5-053d-44b9-b528-be0d1ff62749)


![Screenshot 2025-01-22 195436](https://github.com/user-attachments/assets/fe2e1b20-ddad-40a8-ac76-b21ac8597b39)

<p>
</p>
<p>
 After configuring the VM's specifications, including the operating system, CPU, memory, and storage, I installed the Active Directory Domain Services (AD DS) role. Following this, I used the Active Directory Domain Services configuration wizard to promote the VM to a domain controller, creating a new domain in the process. Networking configurations, such as virtual networks and security groups, were also set up to ensure secure and reliable connectivity. The VM is now fully functional as a domain controller for managing users and resources.







</p>
<br />
