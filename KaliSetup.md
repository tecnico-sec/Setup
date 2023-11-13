# Kali Linux Installation

This tutorial assumes that you are able to boot the installation media inside a virtual machine (VM) to install Kali Linux.  
Despite it being easier to use the pre-built VMs, we recommend that you use the installation media, as it will allow you to learn more about the process of installing operating systems.
The following options can be adjusted as you see fit.

## Obtain installation media

If you do not have an installation media for Kali Linux, like a disc image, you can obtain one [here](https://cdimage.kali.org/).  
Make sure you download the desired version and the correct processor architecture (for Apple Silicon MacBooks, ARM64, for Intel-based MacBooks, AMD64).

## Installation steps inside VM

1. Your VM should now be loading.
Select the “Install” option using your keyboard.

![GRUB menu](images/kali-01.png)

2. After a while, you will be presented with a screen which allows you to select a language.
For the purpose of this guide, we will select “English”.

![Language menu](images/kali-02.png)

3. Select “Other” location, "Europe", "Portugal".

![Location menu Other](images/kali-03.png)

![Location menu Europe](images/kali-04.png)

![Location menu Portugal](images/kali-05.png)

4. Select “United States” locale.

![Locale menu](images/kali-06.png)

5. Select “Portuguese” keyboard layout.

![Keyboard configuration](images/kali-07.png)

6. Set hostname as “kali”, the default value.

![Hostname](images/kali-08.png)

7. You can skip the definition of domain name.

![Domain name](images/kali-09.png)

8. Username and password will be set to “kali” for this example.
This is an insecure practice, so make sure you select another password (that you do not forget).

![User full name](images/kali-10.png)

![User account name](images/kali-11.png)

9. Set your timezone as “Lisbon”

![Timezone](images/kali-12.png)

10. Select “Guided - use entire disk”, and for the following option, you should select the only existing disk, “VMWare Virtual NVMe Disk”

![Partition use disk](images/kali-13.png)

![Partition NVMe](images/kali-14.png)

11. Select “All files in one partition”

![All files in partition](images/kali-15.png)

12. Select “Finish partitioning” and confirm your changes by selecting “Yes”

![Finish partition](images/kali-16.png)

![Write changes](images/kali-17.png)

After a short while, the installer should ask you which software you want.

13. For desktop environment, you should choose Xfce, Kali’s default.

![Xfce](images/kali-18.png)

As the installer prepares your Kali Linux instance, you will have to wait for a short while, around 10 minutes.

14. Select “Continue” to finish the installation.

![Reboot](images/kali-19.png)

15. After a while, you should be presented with a login screen, in which you should use the username and password that you previously configured.

## Kali up and running

Kali Linux is installed and ready for use!

![Kali Desktop](images/kali-20.png)

<!--
If you wish to remove the graphical user interface, you can follow [these instructions](https://linuxconfig.org/kali-linux-without-gui).
-->

----

[SIRS Faculty](mailto:meic-sirs@disciplinas.tecnico.ulisboa.pt)
