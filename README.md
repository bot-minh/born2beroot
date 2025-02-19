# Born2beroot

## 1. How a Virtual Machine Works
A Virtual Machine (VM) is like a computer inside your computer. It runs its own operating system while being controlled by the host OS. The VM shares your hardware (CPU, RAM, storage) but remains separate from the main operating system.

## 2. Choice of OS
Debian is chosen over CentOS because it is lighter to install and configure.

## 3. Differences Between CentOS and Debian
- **CentOS**: Used in enterprise environments and corporate servers.
- **Debian**: Great for general use, developers, and personal projects.

## 4. Purpose of a Virtual Machine
- Run multiple OSes on one computer (e.g., Windows on Linux).
- Test software in a safe, isolated environment.

## 5. AppArmor
AppArmor is a security module for Debian that restricts what system resources an application can access.

## 6. SSH (Secure Shell)
SSH is a protocol that allows secure remote login to another machine over a network.

## 7. UFW (Uncomplicated Firewall)
UFW is a simple firewall tool for managing network security. When connecting to a remote system using SSH, your request must pass through the firewall, where UFW decides whether to allow or block it.

## 8. Aptitude vs apt
- **apt**: A lower-level package manager that installs only the requested packages.
- **aptitude**: A higher-level package manager that may install additional dependencies, sometimes including unnecessary ones.

## 9. LVM (Logical Volume Manager)
LVM is a storage management system for Linux that allows flexible disk management:
- **Physical Volume (PV)**: The actual physical storage device (e.g., a hard drive or partition).
- **Volume Group (VG)**: A pool of storage combining one or more Physical Volumes.
- **Logical Volume (LV)**: Virtual partitions created within a Volume Group for flexible storage management.

