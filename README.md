 # Windows-11-Virtualbox-Deployment-Troubleshooting-Lab
 ## Overview
 This project documents the deployment of a Windows 11 Virtual machine using Oracle VirtualBox. The purpose of this lab was to build a control Windows 11 Environment that could be used for cybersecurity training, testing, and experimentation.
 Rather than only documenting the successful installation, I recorded the troubleshooting process used to diagnose and resolve issues  encountered during the deployment. 

 ## Objectives 
 - Deploy Windows 11 inside Oracle VirtualBox.
 - Configure a virtual machine for Windows 11.
 - Configure UEFI and TPM 2.0 requirements.
 - Configure Hardware virtualization
 - Troubleshoot VM Boot failures.
 - Verify and attach a Windows ISO.
 - Configure the virtual optical Drive.
 - Diagnose EUFI boot issues.
 - Complete a clean Windows 11 installation.
 - Configure the VM as an isolated cybersecurity lab environment
 - Minimize unnecessary personal data synchronization.

## Environment
### Host System
- CPU: AMD Ryzen 5 5600X
- Ram: 16 GB
- Operating System: Windows
- Virtualization platform: Oracle Virtual Box

### Virtual Machine
- Operating System: Windows 11
- Architecture: x64
- Virtual CPU: 4
- Ram: 8 GB recommended configuration
- Virtual Disk: 61 GB
- Firmware: EUFI
- TPM: TPM 2.0
- Installation media: Windows 11 ISO

# 1. Obtaining the Windows 11 ISO
I downloaded the official windows 11 x64 ISO from Microsoft's Windows 11 download page.
the ISO used during the installation was:
'Win11_25H2_English_x64_v2.iso'
The ISO was stored locally in the Windows downloads directory.

# 2. Creating the Virtual Machine
A new windows 11 virtual machine was created in Oracle VirtualBox.
The VM was configured with:
- 4 virtual CPUs
- 8 GB of RAM
- Approximately 61 GB virtual hard disk
- UEFI Software
- TPM 2.0
- Virtual optical Drive containing the Windows 11 ISO

The virtual hard disk was initially empty because Windows had not yet been installed.






