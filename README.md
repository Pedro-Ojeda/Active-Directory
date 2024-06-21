# Active Directory Lab Setup

This project demonstrates the setup and configuration of a comprehensive Active Directory environment using Oracle VirtualBox. It includes the installation of Windows Server 2019 as a domain controller and a Windows 10 client, along with network configuration, DHCP, and NAT setup.

## Key Steps and Configurations

1. **Oracle VirtualBox Installation:**
   - Installed VirtualBox and Extension Pack for VM management.

2. **ISO File Acquisition:**
   - Downloaded Windows 10 and Windows Server 2019 ISO files.

3. **Virtual Machine Creation:**
   - Created VMs for the domain controller and Windows 10 client.
   - Configured network adapters for internal and external communication.
<p align="center">
Configure network adapters for internal and external networking: <br/>
<img src="https://i.imgur.com/mUfUAOE.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<p align="center">
Creating admin user account: <br/>
<img src="https://i.imgur.com/akwmEEX.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />

4. **Windows Server 2019 Setup:**
   - Installed and configured AD DS, promoted the server to a domain controller.
   - Set static IP addressing for internal network communication.
   - Configured RRAS for NAT to provide internet access to internal network clients.
   - Installed and configured DHCP for IP address assignment.
<p align="center">
Installed and configured AD DS, Routing and Remote Access (RRAS) and DHCP: <br/>
<img src="https://i.imgur.com/JIt7XFF.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<p align="center">
Configuring DHCP Scope: <br/>
<img src="https://i.imgur.com/ey0rUjk.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />

5. **Active Directory User Management:**
   - Created organizational units and user accounts using a PowerShell script.
<p align="center">
PowerShell scripts to create a large number of user accounts in Active Directory: <br/>
<img src="https://i.imgur.com/Kz3zbRh.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />

6. **Windows 10 Client Setup:**
   - Installed Windows 10 on the client VM.
   - Joined the client to the Active Directory domain.
   - Verified network connectivity and domain login.
<p align="center">
Join the Windows 10 VM to the Active Directory domain: <br/>
<img src="https://i.imgur.com/7y2YG9D.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<p align="center">
Verify the client can obtain an IP address from the DHCP server: <br/>
<img src="https://i.imgur.com/2iMatKg.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />


## Skills Demonstrated

- Network configuration and management
- Active Directory setup and administration
- Automation with PowerShell
- DHCP and NAT configuration
- Client-server interaction and domain joining

This lab setup is ideal for understanding the core concepts of Active Directory and Windows networking in a virtualized environment. It provides a solid foundation for managing and troubleshooting a corporate network infrastructure.
