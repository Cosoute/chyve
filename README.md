# chyve

Section 1: Overview
Chyve is a type 1 hypervisor to run multiple VMs on a local workstation

The Chyve system runs on a custom (Client Hypervisor Environment) and is based on a secure implementation of Xen open source project. It is a powerful type-1 hypervisor, which also has a modern User Interface to manage the VM’s from within a single standalone workstation, pc or laptop.  The entire system is self contained – with all VM’s local to the machine’s hard-drive.

CHyvE can be used for many purposes – however for this particular instance - it has been customized for the Banker System to fulfill the specific needs required.  The banker user will need many VM’s in order to communicate with the remote offices.  The following feature is included:
-	5+ VMs for Operations
o	1 dedicated VM for each remote office (Copper, Gold, Platinum, Silver and Titanium)
o	All running Windows 7 32 bit Home version

-	2 VMs for Support
o	IT-Support Win7 VM 
o	Hidden Spector Storage Service VM (known as domS)

-	Each VM is restricted to authorized users only
-	VM’s are Daily Persistent (at midnight, a clean VM overwrites the current VM)

