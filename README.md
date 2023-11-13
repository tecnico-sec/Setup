Instituto Superior Técnico, Universidade de Lisboa

**Network and Computer Security**

# Setup of Lab Environment

All labs should be executed in the virtual machine (VM) of the Kali Linux project: [Kali.org](https://www.kali.org).  
We strongly suggest running Kali Linux locally, as a _guest_, on your own machine working as _host_.

In this document we will describe the following ways to run the VM:

- Using VirtualBox (recommended for Windows and Linux running on x86 or x64 processors);
- Using VMWare Fusion (recommended for macOS running on Apple Silicon processors M1/M2/M3).

## 1. Virtual Box

1. Download VirtualBox at [Virtual Box](https://www.virtualbox.org) official website;
2. Install VirtualBox following [instructions from the manual](https://www.virtualbox.org/manual/ch02.html);
3. Create a new Virtual Machine following the [Kali inside VirtualBox tutorial](https://www.kali.org/docs/virtualization/install-virtualbox-guest-vm/);
4. Install Kali Linux inside the VM, following the [Kali Setup tutorial](KaliSetup.md).

### Troubleshooting

If you have problems with the Guest Additions (screen resolution, unable to copy host to guest, etc) you might want to have a look in [here](http://www.virtualbox.org/manual/ch04.html).

## 2. VMWare

1. Create an account (if you do not have one yet) at [VMware](https://customerconnect.vmware.com/evalcenter?p=fusion-player-personal-13);
2. Download VMware Fusion (the free version);
3. Install VMware;
4. Create a new Virtual Machine following the [Kali inside VMWare tutorial](VMwareFusion.md).

### Troubleshooting

If you have problems with the Guest Additions (screen resolution, unable to copy host to guest, etc) you might want to have a look in [here](https://kb.vmware.com/s/article/1018414).

## 3. RNL Virtualization

If you are unable to use VirtualBox or VMware fusion, then you still have the option of using an earlier version of the VM, at an RNL lab located in the Alameda campus.

For the first labs you just need to run the script `rnl-seed21`.
This script automates the process of creating a VM running on the lab machine, connected to the network through NAT.

If you require this option, please contact faculty for additional `rnl-virt` specific materials.

----

[SIRS Faculty](mailto:meic-sirs@disciplinas.tecnico.ulisboa.pt)
