---
title: "How To Fix Windows 10 AudioVideo Lag?"
date: "2019-06-12"
categories: 
  - "computers"
  - "laptop"
tags: 
  - "audiovideo-lag"
  - "disable-hpet"
  - "windows-10"
coverImage: "home-office-1867761_1920.jpg"
---

Lately, after Windows 10 update several people complained about the Windows 10 AudioVideo lag and it might not only happening on Windows 10 but can be on any windows version.

For me, it the audio and video lag started just after updating Windows 10 major update and since then none of the updates was able to fix it. Even I tried several solutions available online including Hard Reset as well as installing and reinstalling audio drivers.

**The problem was that the audio doesn't match the video. It is delayed and happens with every video streaming platforms and even while playing downloaded movies using Video Player.** It made me something like this every time I watch something on my PC.

<iframe src="https://giphy.com/embed/lJnAXeJO8tE7E37mxq" width="480" height="276" frameborder="0" class="giphy-embed" allowfullscreen></iframe>

[](https://giphy.com/gifs/reaction-lJnAXeJO8tE7E37mxq)

Nothing seems to work. I decided to dig around more to get help. I noticed that people were complaining about it on several forums and no one was able to fix it.

However, for some people the little workaround given below fixed the issue and for some it doesn't. Therefore, you should first try the following to check if it fixes the problem.

## Simple Way To Fix The AudioVideo Sync Lag:

1. Uninstall and reinstall the [Realtek audio drivers](https://www.realtek.com/en/component/zoo/category/pc-audio-codecs-high-definition-audio-codecs-software). In most cases, it should fix the problem.
2. Update the Windows. Go to updates and check if any Cumulative update is pending. If yes, update it and check if the problem is fixed.

If all above fixes failed, then this fix should be able to sort out the problem.

## Fix Windows 10 AudioVideo Lag \[Hard Way\]

For me disabling **HPET** (High Precision Event Timer) fixed all the issues therefore, we will look how to disable it in the steps below.

### Disabling HPET (1st Way)

1. Press **CTRL + Q** or simply open search and then search for **Device Manager**.
2. Click on **Device Manager**
3. Scroll down below to **System Devices** and open the sub-menu.
4. Search for **High Precision Event Timer** and disable it.

## Disabling HPET (2nd Way)

1. In the taskbar, right click on **Windows Button** and open **Command Prompt** as an administrator
2. Now, to disable HPET type the following command **"bcdedit /deletevalue useplatformclock"** without quotations.
3. Press enter and you're good to go.

## Disabling HPET (3rd Way)

In this way, HPET is disabled from the **BIOS**. As BIOS settings are different for different laptops and PC therefore I could not give you exact steps on disabling HPET from BIOS.

You can enter into BIOS by pressing either **F12 or DEL** key from keyboard. You can then go through the settings to find HPET and disable it. I don't recommend this way unless above two methods fail to fix your problem.

**I listed 3 ways to disable HPET for a reason.**

When I used either 1st and a 2nd way to disable HPET, it only fixed the Windows 10 AudioVideo Lag for streaming platforms like Amazon Prime Video, & Netflix. While for YouTube it remained the same. Hence, I disabled it completely from BIOS to fix the problem for YouTube as well.

* * *

**You Might Also Like:**

[Build A PC From Scratch Under Rs 30,000](https://sastaeinstein.com/2019/06/build-gaming-pc.html)

[TV Shows On Amazon Prime You Should Watch](https://sastaeinstein.com/2018/12/3-tv-shows-amazon-prime.html)
