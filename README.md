## 🎓 Academic Information

Project Title: Hardening and Securing an Operating System

Project Type: Cybersecurity Minor Project

Department: Computer Engineering

Institute: Sardar Vallabhbhai Patel Institute of Technology (SVIT), Vasad

## 👨‍💻 Author

### Aaditya Mistry

GitHub: https://github.com/AadityaMistry
LinkedIn: https://www.linkedin.com/in/aaditya-mistry

## 📜 License

This project is shared for educational purposes only. Feel free to use it as a learning resource with appropriate attribution.


---


# 🛡️ Hardening and Securing an Operating System (Windows 11)

A practical cybersecurity project demonstrating the implementation of **Windows 11 Operating System Hardening** using built-in Windows security features and PowerShell. The project focuses on improving system security by applying industry-recommended hardening techniques and verifying each security configuration through practical implementation.

---

## 📖 Project Overview

Operating systems are frequent targets of cyber threats such as malware, ransomware, unauthorized access, and network attacks. This project demonstrates how native Windows security features can be used to strengthen the security posture of a Windows 11 system without relying on third-party software.

The project includes practical implementation, PowerShell verification, observations, and documentation for each security control.

---

## 🎯 Objectives

- Understand the concept of Operating System Hardening.
- Secure a Windows 11 system using native security features.
- Reduce system vulnerabilities through security best practices.
- Verify security configurations using PowerShell.
- Document the implementation process with screenshots and observations.

---

## 🛠️ Tools & Technologies

- Windows 11 Home (Version 25H2)
- Windows PowerShell
- Microsoft Defender Antivirus
- Windows Defender Firewall
- Windows Update
- Event Viewer
- NTFS File System
- Controlled Folder Access
- System Protection (Restore Point)

---

## 📂 Project Implementation

The following security measures were implemented:

### ✅ System Information Collection
- Verified Windows version and build.
- Collected hardware and system details using PowerShell.

### ✅ Windows Update & Patch Management
- Installed the latest Windows security updates.
- Verified installed updates.

### ✅ Microsoft Defender Antivirus
- Updated virus definitions.
- Performed a Quick Scan.
- Verified Real-Time Protection.

### ✅ Windows Defender Firewall
- Verified Domain, Private, and Public firewall profiles.
- Confirmed firewall protection was enabled.

### ✅ User Account Security
- Reviewed local user accounts.
- Verified administrator privileges.
- Confirmed disabled built-in accounts.

### ✅ NTFS File Security
- Verified NTFS file system.
- Reviewed folder permissions.

### ✅ Controlled Folder Access
- Enabled ransomware protection.
- Verified protected folders.

### ✅ Network Security Assessment
- Examined network configuration.
- Reviewed active TCP connections.
- Verified DNS configuration.

### ✅ Event Monitoring
- Reviewed Security logs.
- Reviewed System logs.

### ✅ Backup & Recovery
- Enabled System Protection.
- Created a System Restore Point.

---

## 📷 Project Screenshots

The repository contains screenshots demonstrating:

- Windows Update
- Microsoft Defender
- Firewall Configuration
- User Accounts
- NTFS Permissions
- Controlled Folder Access
- Network Assessment
- Event Viewer
- System Restore
- PowerShell Outputs

---

## 📊 Results

The implementation successfully strengthened the security posture of the Windows 11 operating system through:

- Updated operating system
- Active malware protection
- Enabled firewall
- Secure user account configuration
- Protected file system
- Ransomware protection
- Verified network configuration
- Event monitoring
- Recovery capability

---


---

## 💻 PowerShell Commands Used

```powershell
systeminfo
Get-ComputerInfo
Get-HotFix
Update-MpSignature
Start-MpScan -ScanType QuickScan
Get-MpComputerStatus
Get-NetFirewallProfile
Get-LocalUser
Get-LocalGroupMember Administrators
Get-Volume
ipconfig /all
Get-NetAdapter
netstat -ano
Get-NetTCPConnection
Get-DnsClientServerAddress
Get-EventLog -LogName Security -Newest 20
Get-EventLog -LogName System -Newest 20
Get-ComputerRestorePoint
## 📁 Repository Structure

