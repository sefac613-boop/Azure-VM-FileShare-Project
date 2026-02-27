

# 🚀 Azure Virtual Machine & Azure File Share Assignment



---


<img width="1536" height="1024" alt="azure_structure" src="https://github.com/user-attachments/assets/ea320a18-04f1-4119-8ee3-0478e93f6e06" />



## 📋 Project Overview
This project demonstrates a cloud-based infrastructure setup using Microsoft Azure. The primary focus was creating a seamless link between an Ubuntu Virtual Machine and a local macOS environment using Azure File Share for real-time synchronization.

### 🛠 Tech Stack & Tools
- **Cloud Platform:** Microsoft Azure
- **Operating System:** Ubuntu Linux
- **Web Server:** Apache2
- **Database:** MySQL
- **File Sharing:** Azure File Share (SMB/CIFS Protocol)

🧹 Clean Up
  ---The following resources were deleted after project completion:

  ---Virtual Machine

  ---Storage Account

  ---Resource Group

  ---Public IP

  ---Network Interface

🚀 Technologies Used
  ---Microsoft Azure

  ---Ubuntu Linux

  ---Apache

  ---MySQL

  ---Azure File Share (SMB / CIFS)

  ---Network Security Group (NSG)



## ⚙️ Implementation Process

### 1. Azure Virtual Machine Setup
- Deployed a Linux VM (Ubuntu) on the Azure portal.
- Configured Network Security Groups (NSG) to allow traffic on Port 22 (SSH) and Port 80 (HTTP).

### 2. Azure File Share Configuration
- Created a persistent storage share named `sharemee`.
- Mounted the share to the Linux VM at the `/media/sharemee` directory.
- Connected the local macOS environment to the same Azure share for cross-platform data flow.

### 3. Server Management & Database
- Installed **Apache Web Server** to host web services.
- Installed **MySQL Server** for database management.
- Verified all services are "Active and Running".

---

## 🔍 Verified Terminal Operations (CRUD)

I have successfully performed Create, Read, and Delete operations on the mounted share. Below is the directory listing evidence:


# Output from: ls -la /media/sharemee

drwxr-xr-x 2 root root 4096 Feb 26 12:15 .

-rw-r--r-- 1 root root   27 Feb 26 12:15 islem_tamam.txt

-rw-r--r-- 1 root root   60 Feb 26 12:13 odev_raporu.txt

-rw-r--r-- 1 root root    0 Feb 26 12:06 terminal_den_selam.txt



### 4. Links Resource


* **GitHub Repository:** [https://github.com/sefac613-boop/Azure-VM-FileShare-Project](https://github.com/sefac613-boop/Azure-VM-FileShare-Project)

  LinkedIn Post: [LinkedIn Profile](https://www.linkedin.com/in/sefa-ceylan-aa8731249/)

