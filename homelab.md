---
layout: default
---

# Homelab Server

My servers provide me a home lab to experiment and learn on, as well as provide me and my friends with multiple useful services. I have run servers at home for a long time now, most of them have been recycled hardware due to low performance requirements. My latest setup was built last year and has already had some small improvements done.

### Current setup:

Intel i3-10100 with 32GB of ram running Proxmox. Boot drive is two SSD’s in ZFS Mirror for redundancy. For mass storage I have 2x 8TB and 2x 12TB hard drives, shucked from external housings. Hard drives are connected to an LSI HBA.

### Networking:

My personal computers and the server are connected via 2.5 GBASE-T. This allows me to utilize full speed of the hard drives.

### Services:
* Proxmox as a hypervisor to run virtual machines
* Virtualized TrueNAS for handling mass storage in ZFS. Hard drives are assigned to the virtual machine via a PCI-E passthrough of the HBA
* In progress: Automatic nightly storage replication to a server at a friend for nightly offsite backups
* Two virtualized routers (pfSense) providing me with firewalls for two external IP addresses
* Virtualized Pi Hole for network wide ad blocking via DNS
* Virtualized Home Assistant for home automations
* Couple virtualized Ubuntu instances running Docker containers and other services for friends.

![Homelab](\assets\homelab_2.jpg)

![Homelab](\assets\homelab_1.jpg)

[back](./)