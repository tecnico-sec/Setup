Instituto Superior Técnico, Universidade de Lisboa

**Network and Computer Security**

# Setup of Lab Environment

Most of the material available for our Network and Computer Security labs is part of the [SEED Labs Project](https://seedsecuritylabs.org/). Have a look at their project as you have many more labs proposed beyond the ones we'll follow here.

All labs should be executed in the virtual machine (VM) provided by the SEED Labs project: [SEEDUbuntu16.04](https://seedsecuritylabs.org/lab_env.html).

In this document we will provide two ways of running this VM:  
(a) Locally on your machine, or  
(b) using the virtualization system provided by RNL (labs in Alameda).  

We strongly suggest the former.

## 1. Install SEED Locally on your machine

1. Download the Pre-built Virtual Machine Images (Ubuntu) from [SEED Labs Project](https://seedsecuritylabs.org/lab_env.html). Wesuggest the one built in June 2019.
2. Unzip the file.
    + Files will be included in folder `SEEDUbuntu-16.04-32bit`.
3. Follow the [instructions](https://seedsecuritylabs.org/Labs_16.04/Documents/SEEDVM_VirtualBoxManual.pdf).
    + _Step2_: You can give whatever name you want to your machine (and a folder with that name will be created)
    + _Step4_: To keep your disk organized, you may move the files from the folder created in 2.1 to the folder that was just created prior to performing Step4.
    + _Step5_: It is important that you select `Graphics Controller: VBoxVGA` otherwise you might have a small resolution.
4. Start the VM. `user:pass/seed:dees`
5. Optional: Change keymap to PT. `setxkbmap pt`
6. Recommended: Update the system. `sudo apt update; sudo apt upgrade`

## Troubleshooting

If you have problems with the Guest Additions (screen resolution, unable to copy host to guest, etc) you might want to have a look in [here](http://www.virtualbox.org/manual/ch04.html#idp11569008).

## 2. Using `rnl-virt` in RNL (labs in Alameda)

**Acknowledgments**

Original version: Pedro Adão

----

[SIRS Faculty](mailto:meic-sirs@disciplinas.tecnico.ulisboa.pt)
