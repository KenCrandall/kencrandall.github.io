---
title: Virtualization on Linux
date: 2013-06-18 12:12
categories:
- linux
- virtualization

---
It is interesting that so many virtualization solutions either *use* or *start-out using* Linux as their base.  

Xen uses Linux for Dom0 and VMware's original ESX used Linux as the Service Console...

Oracle VDI uses VirtualBox on Linux as a Type-2 hypervisor, and ***way*** back in the day, VMWare GSX/Server used Linux as it's base (also a Type-2 hypervisor.)

Now we have KVM where Linux _**is**_ the hypervisor...
