---
title: "How to sideload OTA update manually on your Google Nexus/Pixel?"
date: "2017-04-22"
categories: 
  - "sideload"
---

Hola everyone! How's it going. It's Emad here with another post on my blog. I recently got Nexus 6 (Shamu) in my hand and literally got a chance to test it. Due to my mistake, it was one of the stolen device and I was grounded in Police Station.  
  
**B****eware of craigslist in your countries. Never trade without getting the seller Identity or authorized device bill.**  
While testing Nexus 6, I came up with an issue that it wasn't receiving the **Nougat 7.1.1** update so far yet as Google even officially released the 7.1.1 update files online for Nexus 6. 
  

[![](/posts/2017/04/images/android-nougat-nexus-6p.jpg)](http://cdn.wccftech.com/wp-content/uploads/2016/08/android-nougat-nexus-6p.jpg)

  
  
**Note: This guide is for the one who still didn't received the 7.1.1 update for their Pixel/Nexus device. It applies almost the same way for all Nexus/Pixel devices. Anyhow, in my case I'm using Nexus 6.**  
Let's take a look to update your Nexus/Pixel device:  
  

1. Visit [here](https://developers.google.com/android/ota) and download the OTA file for your Nexus/Pixel device.
2. Match the checksum and verify it to be on the safer side.
3. Make sure you have **adb** installed on your PC/Mac. If not visit [here](http://riffhold.com/gWx) to download. It is a minimal adb and doesn't require you to install whole SDK.
4. Now connect your Nexus/Pixel to your PC/Mac
5. Launch ADB and type in this command "_adb reboot recovery"_ without quotes
6. Now, hold power button and press the volume up button once to see the menu
7. Choose _Apply update from ADB_ and press power button to select.
8. Go back to your PC, type in this command "_adb sideload <ota.zip>"_ without quotes. _ota.zip is the location of the file you downloaded in step 1._
9. It will start updating it. Once finished you'll be back to menu which appeared in step 6. Now choose _reboot system now_ to successfully reboot and enjoy the Nougat 7.1.1 update.

  

  
Thanks for reading up my post. I'm hopeful and make sure that you don't waste your precious time and gained atleast some information from my posts. If you really enjoy the stuff, head up sometime again to look up new stuff here.
