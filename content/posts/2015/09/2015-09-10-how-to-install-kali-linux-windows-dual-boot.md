---
title: "How to Install Kali Linux + Windows (Dual Boot)"
date: "2015-09-10"
categories: 
  - "computers"
  - "hacker"
---

## Kali Linux Installation Requirement:

1\. Blank DVD or USB 

2\. 4GB + RAM

3\. 10GB minimum space in HardDisk Drive

4\. CD-DVD Drive support or USB boot support

  

## Preparing for installation:

1\. Download [Kali Linux](https://www.kali.org/downloads/)

2\. Burn the Kali Linux to DVD or USB

3\. Ensure that your BIOS is set to boot the DVD drive or USB first

 (Some computer allow F12 key to choose boot options)

  

### Installing Kali Linux:

1\. Just after booting in the Kali linux options appear on the screen as listed in the picture below. Choose Graphical Install.

[![](images/01-install-select.png)](http://docs.kali.org/wp-content/uploads/2015/02/01-install-select.png)

  

2\. Choose your preferred language to proceed the installation.

[![](images/02-language-select.png)](http://docs.kali.org/wp-content/uploads/2015/02/02-language-select.png)

  

3\. Choose the current location from the list that appears.

[![](images/03-location.png)](http://docs.kali.org/wp-content/uploads/2015/02/03-location.png)

  

4\. Now the installer will copy the system files to your hard disk drive. Be patience for the next step.

  

5\. Type in the hostname if you want to change default is kali

[![](images/05-hostname.png)](http://docs.kali.org/wp-content/uploads/2015/02/05-hostname.png)

  

6\. Type in the domain if you have one or else you can skip the step

[![](images/06-domain.png)](http://docs.kali.org/wp-content/uploads/2015/02/06-domain.png)

  

7\. Now specify your full name in the blank given.

  

[![](images/07-user.png)](http://docs.kali.org/wp-content/uploads/2015/02/07-user.png)

  

8\. A default ID will be created using your full name. If you wish to change you can change it!

  

[![](images/08-username.png)](http://docs.kali.org/wp-content/uploads/2015/02/08-username.png)

  

9\. Set up your timezone. Time zone appears only according to the country you selected in step 2. In my case it's United States so the following timezone appears.

  

[![](images/09-timezone.png)](http://docs.kali.org/wp-content/uploads/2015/02/09-timezone.png)

  

  

10\. Now the installer will scan your disk and provides you with four options. Hence we use the entire disk and not going to configure the LVM (Logical volume Disk). We gonna choose the \[Guided - Use Entire Disk\]. Experienced users can have manual partitioning method.

  

[![](images/10-partitionmethod.png)](http://docs.kali.org/wp-content/uploads/2015/02/10-partitionmethod.png)

  

11\. Next step promotes you to choose the disk you want to be partitioned.

  

[![](images/11-selectdisk.png)](http://docs.kali.org/wp-content/uploads/2015/02/11-selectdisk.png)

  

12\. Now, you can keep all the file in single partition the default one or can use the other option provided below it. However, If you don't know you can choose the default one.

  

[![](images/12-partitioningscheme.png)](http://docs.kali.org/wp-content/uploads/2015/02/12-partitioningscheme.png)

  

13\. Now you will get the last chance to reveal all the changes made to your disk before it makes the changes to disk.

  

[![](images/13-finish-partitioning.png)](http://docs.kali.org/wp-content/uploads/2015/02/13-finish-partitioning.png)

  

14\. Configure the network mirrors here. Note that if you choose 'NO' you can't install packages from Kali repository later.

  

[![](images/14-networkmirror.png)](http://docs.kali.org/wp-content/uploads/2015/02/14-networkmirror.png)

  

15\. Now this step is important as it install GRUB loader. Somehow you must not listen this word before if you're not much familiar with installing and dual booting windows or linux.

GRUB Loader will list all the operating systems in your computer to select the one you wished to open!

  

[![](images/15-install-grub.png)](http://docs.kali.org/wp-content/uploads/2015/02/15-install-grub.png)

  

16\. Finally, it's over. Installation has completed! Reboot to enjoy the Kali!

  

[![](images/16-install-complete.png)](http://docs.kali.org/wp-content/uploads/2015/02/16-install-complete.png)

  

Thank You. Keep visiting TheVirtualImagination For more toturials!
