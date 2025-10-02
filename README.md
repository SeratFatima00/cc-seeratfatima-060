# Cloud Computing LAB 01

## Student Information
- **Submitted By:** Seerat Fatima  
- **Registration No:** 2023-BSE-060  
- **Section:** 5B  

## Instructor
- **Submitted To:** Engr. Shoaib  

---

## Lab Task
### Installation of Linux Server

### Objective
To install and configure a Linux server environment required for cloud computing labs.

---

## Steps for Installation

### 1. Download Linux Distribution
- Go to the official website of your chosen Linux distribution (e.g., Ubuntu Server, CentOS, Debian).
- Download the latest ISO image (e.g., Ubuntu Server LTS).

### 2. Create Bootable Media
- Use tools such as **Rufus** (Windows) or **Startup Disk Creator** (Linux).
- Select the ISO file and create a bootable USB.

### 3. Boot from USB
- Insert the bootable USB into your computer.
- Restart the system and enter BIOS/UEFI settings.
- Change boot priority to USB drive.
- Save and exit → system will boot from the USB.

### 4. Start Installation
- Choose **Install Linux Server** option.
- Select language, keyboard layout, and region.
- Configure hostname (e.g., `cloud-server`).

### 5. Partition the Disk
- Choose automatic partitioning (recommended for beginners) or manual (advanced).
- Assign root (`/`) and swap partitions.

### 6. Create User Account
- Enter your **username** and **password** for administrative login.

### 7. Install Base System
- Wait for packages to install.
- Configure package manager (enable updates & security repositories).

### 8. Install Additional Software
- Select necessary server components:
  - **OpenSSH Server** (for remote login).
  - **Web server, database, etc.** if required.

### 9. Finish Installation
- Once installation is complete, remove the USB and reboot.
- Login using your credentials.

### 10. Verify Installation
Run the following commands after login:

```bash
lsb_release -a    # Check Linux version
uname -r          # Check kernel version
ip a              # Verify network configuration
