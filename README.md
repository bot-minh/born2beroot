# born2beroot
1,How a Virtual Machine Works?
A virtual machine (VM) is like a computer inside your computer.
It runs its own operating system while being controlled by the host OS.
 The VM shares your hardware (CPU, RAM, storage) but separate with the main operating system.
2,Choice of OS
It's lighter to install and configure than CentOS. 
3, Differences 
centos :  
Used in enterprise environments, and corporate servers
debian:
Great for general use, developers, and personal 
4, Purpose of a Virtual Machine
Run multiple OSes on one computer (e.g., Windows on Linux).
Test software in a safe, isolated environment.
5,AppAmor
security module for Debian,restrict what system resources an application can access
6,SSH (Secure Shell)
SSH is a protocol that allows secure remote login to another machine over a network.
7,UFW
A simple firewall tool for managing network security.
When you try to connect to a remote system using SSH, your request must pass through the firewall, where UFW decides whether to allow or block it.
8,Aptitude vs apt
Aptitude is a higher-level package manager while APT is lower-level package manager. If you use apt, it will install the packages you ask for without adding extra unnecessary ones.
aptitude is another tool, but it’s a bit more advanced.  and sometimes it might install extra packages that you don't need and it depend on
9, LVM (Logical Volume Manager) is a storage management system for Linux. It allows you to manage disk storage
Physical Volume (PV): This is the actual physical storage device, such as a hard drive or a partition, that you use. 
Volume Group (VG): A Volume Group is a pool of storage made up of one or more Physical Volumes. 
Logical Volume (LV): Logical Volumes are the virtual partitions or volumes that you create within a Volume Group. 
