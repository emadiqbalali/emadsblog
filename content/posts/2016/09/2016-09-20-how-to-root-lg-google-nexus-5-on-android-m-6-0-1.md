---
title: "How to root LG Google Nexus 5 on Android M 6.0.1?"
date: "2016-09-20"
categories: 
  - "smartphones-2"
---

Yo! Hi there!  
Today, I'm going to show you how to root Nexus 5 the easiest way!  

[![](images/nexus-5-crop.jpg)](https://4.bp.blogspot.com/-RuK3oJHT22k/V-Ft8cKEl5I/AAAAAAAABuI/dWZGjEXy5XcmpCo6nLO0A1ZuCvrCNSLwQCLcB/s1600/nexus-5-crop.jpg)

  

Disclaimer: Please backup your phone before proceeding. Unlocking your bootloader wipes your phone completely!

  
  
**You need:**  
  
**1\. LG Google Nexus 5 running on Android Marshmallow 6.0.1**  
**2\. [CF Auto Root by ChainFire](https://download.chainfire.eu/363/CF-Root1/CF-Auto-Root-hammerhead-hammerhead-nexus5.zip?retrieve_file=1)**  
**3\. [TWRP recovery](https://dl.twrp.me/hammerhead) (Only in case you need to play with ROMS) \[_Recommended\]_**  
**4\. [Nexus 5 USB Drivers](https://developer.android.com/studio/run/win-usb.html#)**  
**5\. [Fastboot and ADB](https://androiddatahost.com/265a2) (Portable: Doesn't include whole Android SDK)**  
**6\. Of Course some [brain](http://images.memes.com/meme/976.jpg)! xD :)**  
**Procedure:**  
1\. First of all, make sure your Nexus battery is charged more than 60%. Then install Nexus 5 USB drivers and Fastboot in your Laptop or PC.  
  
2\. Switch off your phone.  
  
3\. Put your phone in the bootloader or fastboot mode. This can be done by holding the pressing the Powerbutton + Volume Up + Volume Down. Now at the bottom of the screen look for \[**Lock State: Locked/Unlocked\]** if locked then visit here to [unlock your bootloader.](https://www.google.co.in/url?sa=t&rct=j&q=&esrc=s&source=web&cd=3&cad=rja&uact=8&ved=0ahUKEwiM57aNxJ7PAhWBrZQKHfviAZsQFggjMAI&url=http%3A%2F%2Fwww.iroot.com%2Fknowledge-tips%2Fhow-to-unlock-bootloader-on-nexus-5.html&usg=AFQjCNFFDU88pyq6Bd_NNJXQsQyA3RJekg&sig2=Kzz2w4MWxofdA773wKfMQg&bvm=bv.133387755,bs.2,d.dGo)  
  
4\. Open and extract the CF AutoRoot files and you would see a file called root-Windows.bat open it up and follow onscreen instruction to root your device. However, you will also be asked to unlock your boot loader and unlocking it wipes all your data completely.   
  
5\. A red Android logo appears on your phone and some rooting process goes on and after completing the phone restarts several time and then you're rooted!  
  
6\. Now open the Fastboot, it can be done by going into the folder where you extracted the fastboot and then by right clicking anywhere while holding shift key. Then select 'Open Command Window'.  
  
7\. A Command Prompt will appear, type in following command to flash recovery  
  

- _fastboot devices (_To check the connected device)
- _fastboot flash recovery_ \[Location of recovery Image on your PC, look at point 3 in you need to download\]

  
  
8\. Recovery will be flashed within 10 seconds and you're good to go. Enjoy playing with ROMS!
