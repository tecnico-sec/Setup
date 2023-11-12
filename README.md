Instituto Superior Técnico, Universidade de Lisboa

**Network and Computer Security**

# Setup of Lab Environment

All labs should be executed in the virtual machine (VM) of the Kali Linux project: [Kali](https://www.kali.org). 

In this document we will provide three ways of running this VM:  
* (a) Locally on your machine using VirtualBox (Recommended for x86 machines)
* (b) Locally on your machine using VMWare Fusion (Recommended for Apple Silicon machines (M1/M2/M3))
* (c) using the virtualization system provided by RNL (labs in Alameda).  

We strongly suggest running Kali linux locally.

## 1. Install Kali Linux Virtual Machine Locally on your machine with Virtual Box
1. Download Virtual Box (if you don't have it installed) at [Virtual Box](https://www.virtualbox.org) official website;
2. Install VirtualBox
3. Install Kali Linux in a new Virtual Machine following the [Virtual Box tutorial](instructions/virtualbox.pdf).

## 2. Install Kali Linux Virtual Machine Locally on your machine with VMWare

1. Create an account (if you don't have one yet) at [VMWare](https://customerconnect.vmware.com/evalcenter?p=fusion-player-personal-13);
2. Download VMWare Fusion (the free version);
3. Install VMWare;
4. Install Kali Linux in a new Virtual Machine following the [VMWare tutorial](instructions/vmware.md).

## Troubleshooting

If you have problems with the Guest Additions (screen resolution, unable to copy host to guest, etc) you might want to have a look in [here](http://www.virtualbox.org/manual/ch04.html#idp11569008).

## 2. Using `rnl-virt` in RNL (labs in Alameda)

For the first labs you just need to run the script `rnl-seed21`.
This scripts automates the process of creation of a machine connected through NAT.
For some labs this has to be done manually.
Information about the process will be posted before those labs.

----

[SIRS Faculty](mailto:meic-sirs@disciplinas.tecnico.ulisboa.pt)
