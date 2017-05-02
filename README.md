# veeam-ciscohx-vib
Veeam Backup & Replication integrates with Cisco HyperFlex and allows you to improve performance of 
backup and replication of VMware vSphere VMs hosted on Cisco HyperFlex. 

VIB file for opening ESXi firewall ports required for Cisco HyperFlex integration
The VeeamCiscoHXFirewall.vib opens the required firewall ports on vSphere to get Veeam Backup & Replication access to the IOVisor of Cisco HyperFlex. 
We recommend to assign the Veeam Proxy Server IPs to the rule after installing the VIB to make sure only these IPs a allowed to access.
The Firewall rule is persistent after a ESXi reboot and is enabled by default after installation. 
The VIB does not require a reboot for installation.
