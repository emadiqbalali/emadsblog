---
title: "How To Unbrick Asus FonePad 7 (k012) Using Temporary CWM Recovery?"
date: "2016-05-18"
categories: 
  - "asusindia"
---

Are you facing the issue after rooting your Asus FonePad 7 k012 or Is your device bricked and you cannot boot it again? No worries, I got a fix and it will unbrick Asus fonepad7 (k012) and boot it up instantly.

Keep reading until your device is ready to use once again.

**Update 1 (Feb 17, 2022): All Links in this post has been rectified.**

![Unbrick Fonepad 7](posts/2016/05/images/How-to-unbrick-fonepad-7-k012_-1.png)

## My Story, What Made My FonePad To Get Bricked?

I've a story to tell you what happened with my device so that you can get an idea. If you need to ignore my story then go below for a tutorial on how to fix it.

Hence, a couple days later I decided to format it and I came to know that there was no recovery installed and I was on the latest Asus Firmware which Android 5.0 LolliPop.

Therefore, I boot it in Fastboot mode and formatted it. **I erased Cache, Data, UserData, and System without actually realizing that you can't flash ROM again without recovery**.

Then I keep on searching how to flash it without recovery or just by using fastboot. I can't even flash it using Fastboot as it returned with some errors.

Fortunately, I got a solution which probably worked without a problem. I know there was no such good post about this issue.

XDA has many threads including this issue but XDA don't let me post a comment telling me some bullshit that account must be verified or old in order to comment.

I got a blog lying around and decided to post an article perfectly written solving this issue for you guys facing the same problem.

**_You can thank me by sharing article around_** so that all get to know and fix it or say let Google know and index it properly in their giant search engine.

## How to fix this issue? 

**Disclaimer: I'm not responsible for anything happening to your device. At best I can help you if you contact me. You should follow all the steps carefully and do it on your own risk.**

**Issue:** _You Bricked Your Asus FonePad 7 (k012) and In this case, you might be getting a USB logo flashing when you power on your device and then your device powers off immediately again. You can only access the Fastboot menu as of now._

## Things You need:

1. A Laptop or a PC  
2. [Asus USB Driver](https://gsmusbdriver.com/asus-fonepad-7-k012)  
3\. [Asus ADB and Fastboot](https://dl.google.com/android/repository/usb_driver_r13-windows.zip)  
4\. [Temporary CWM Recovery for Intel devices](https://www.androidfilehost.com/?fid=24052804347782876)  
5\. [Asus Firmware](https://firmwarefile.com/asus-fonepad-7-k012) depending on you. I prefer the latest version on their website.

## Steps to install Temporary CWM Recovery on your Asus FonePad 7:

1. Install the given Asus USB drivers in your PC/Laptop.
2. Download and extract the Temporary CWM Recovery for Intel devices.
3. After extracting, open the folder you in which you extracted and from that folder open Launcher.bat
4. A Command Prompt opens and you need to type in **ACCEPT** and then press **T2**
5. The CWM recovery is now installed on your Asus FonePad 7

## Steps to copy and flash the firmware on your Asus FonePad 7:

1. Download the firmware for your device. (Links are given above in **You Need** section)
2. On your Asus device, boot to CWM recovery and then go to "_Mount and Storage"_ and mount **Data** in order to copy firmware to the device.
3. Open ADB and run the command _adb devices_ to verify your device is being recognized
4. After verifying, copy the firmware using the command "_adb push_ /sdcard". Run this command without quotation.
5. After copying, back to your device check for **Install ZIP** in CWM Recovery and select it. After this, select **Install from SD Card** and choose ZIP file you copied to the device in step 4
6. Your FonePad 7 is successfully flashed and now working again. You've successfully unbrick Asus FonePad7 K012

I hope that it helped you. I value your feedback, therefore, please take your time to comment on how I can improve.If you have ideas, please share it with us. I am also willing to help you fix the above issue if you personally contact me.You can find my social media link on the homepage of my blog. **Sharing is Caring. Hope you care!** 

**You Might Also Like:**

https://sastaeinstein.com/2018/12/beginners-guide-to-start-a-blog.html
