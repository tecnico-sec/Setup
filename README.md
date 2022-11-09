Instituto Superior Técnico, Universidade de Lisboa

**Network and Computer Security**

# Setup of Lab Environment

Most of the material available for our Network and Computer Security labs is part of the [SEED Labs Project](https://seedsecuritylabs.org/).
Have a look at their project as you have many more labs proposed beyond the ones we will follow here.

All labs should be executed in the virtual machine (VM) provided by the SEED Labs project: [SEEDUbuntu 20.04](https://seedsecuritylabs.org/labsetup.html).

In this document we will provide two ways of running this VM:  
(a) Locally on your machine using VirtualBox, or  
(b) using the virtualization system provided by RNL (labs in Alameda).  

We strongly suggest the former.

## 1. Install SEED Locally on your machine

1. Download the Pre-built Virtual Machine Images (Ubuntu) from [SEED Labs Project](https://seedsecuritylabs.org/labsetup.html).  
We suggest the one built in 2021 with the SHA1 hash value of `79d8af332b7bfaa46541644d34bab0b1a4f4239e`.
2. Unzip the file.
    + Files will be included in folder `SEED-Ubuntu20.04`.    
3. Follow the [instructions](https://github.com/seed-labs/seed-labs/blob/master/manuals/vm/seedvm-manual.md).
    + _Step 2_: You can give whatever name you want to your machine (and a folder with that name will be created)
4. Start the VM. `user:pass/seed:dees`,
5. Recommended: Change the user password.
6. Recommended: Update the system. `sudo apt update; sudo apt upgrade`
7. Optional: Change keymap to PT. `setxkbmap pt`

## Troubleshooting

If you have problems with the Guest Additions (screen resolution, unable to copy host to guest, etc) you might want to have a look in [here](http://www.virtualbox.org/manual/ch04.html#idp11569008).

## 2. Using `rnl-virt` in RNL (labs in Alameda)

For the first labs you just need to run the script `rnl-seed21`.
This scripts automates the process of creation of a machine connected through NAT.
For some labs this has to be done manually.
Information about the process will be posted before those labs.

----

[SIRS Faculty](mailto:meic-sirs@disciplinas.tecnico.ulisboa.pt)
