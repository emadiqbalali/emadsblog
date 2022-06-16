---
title: "How To Create A Safer Internet Ecosystem For Children?"
date: "2019-12-06"
categories: 
  - "browser"
  - "network"
  - "website"
coverImage: "child-safety-dns-scaled.jpg"
---

As with many good things, one of the bad sides of the Internet is the wide availability of adult websites. More often than not, this NSFW (not suitable for work) sites can easily distort a kid’s minds and have some grave implications in the long term. 

Not to mention, the Trojan, Virus and other Malware threats from these dubious sites that can compromise your financial and personal identity.

Make sure to read this article on [How to Create a Ghost/Hidden Folder in Windows](https://www.techvile.in/how-to-create-a-ghost-hidden-folder-in-windows/)

## How To Block Adult Websites On Windows?

While you can always using a browser extension to block adult content on a specific browser, but they can be easily bypassed with a proxy or using another web browser. 

To help you with that, here are some of the best ways to block adult sites on Windows, with and without the use of any software. Let’s begin.

### Windows Parental Control

The easiest way to block adult sites or even any time-wasting sites (like Instagram and Reddit) is to use the native Parental control in Windows 10. 

**Although do keep in mind, for this to work, you need to have a Microsoft account (not a local account) and create different users for yourself or your children**.

First, create a local user say for your child.

To do so, navigate to Settings > Accounts > Family & other people. Select Add a family member, and create a new user for your child. Remember, you need to add an email address for your kid here, so make sure you have one handy.

![block adult sites windows parental control](/posts/2019/12/images/image8.png)

Once done, go to the Windows 10 family settings and login, to directly manage your children’s accounts.

Once you login in you’ll see a dashboard that lets you set screen time limits, block sites, filter content, etc. Here we are interested in blocking websites, so click on Web browsing, choose Block inappropriate websites. 

This will block adult content on Edge and Internet Explorer and you can further customize it to stop your kid from launching Chrome or Firefox browser. 

However, it’s far from perfect,  your kids can always, use proxy sites or install a new browser to bypass this.

![microsoft parental control](/posts/2019/12/images/image9.png)

### Block Adult Content Using OpenDNS

The fast, effective, and easiest way to properly block and filter content is to use the OpenDNS service. OpenDNS is a public DNS service that can intercept and filter or block the content according to your settings. 

> _In case you don’t know, a DNS service translates the human-readable web address like google.com to machine-understandable IP address like 192.168.0.125._ 

For this instance, we’ll use OpenDNS for block NSFW content, however, there are other DNS providers like Clean Browsing that does a similar job.  The steps are going to be the same.

So, to start off with OpenDNS, head over to the official site and sign up for a free account.

Once you are done signing up, OpenDNS will give you the IP addresses of its DNS service. We need to use these IP addresses in our system or router to start using the OpenDNS.

![](/posts/2019/12/images/image5.png)

OpenDNS Name Servers

Thankfully, OpenDNS has specific instructions on how to change the DNS address on a computer or on a router. Just click on the appropriate option displayed just below the IP addresses.

**Home Routers: If you have a router in your house then select this option. It will take you to a page where you can find instructions for your specific router. (Recommended)**

Computer Workstations and Laptops: This option gives instructions on how to change the DNS address on your Windows, Mac, or Linux computer. I will show you how to easily change the DNS address in Windows, just follow the steps below.

Smart Devices: **This option shows you the instructions for other smart devices like smartphones, PlayStation, Xbox, Apple TV, etc.**

### Configuring OpenDNS

To set up the filtering, click on the link “**Dashboard**” on the top navigation bar. On the next page, navigate to the “**Settings**” tab. Generally, your current IP address is already added in the blanks. Simply click on the button “**Add Network**.”

![](/posts/2019/12/images/image1.jpg)

You will be asked to enter a friendly name to easily recognize the network. So, enter the name and click on the button “**Done**.” If you are using Dynamic IP address, then select the checkbox “**Yes, it is dynamic**” and then click on the link “**OpenDNS Updated for Windows**” to download the OpenDNS software.

![opendns family shield](/posts/2019/12/images/image3.jpg)

That’s it, you’ve added the network. Do install OpenDNS Updater and log into your account so that it can automatically update the IP address with OpenDNS if you have a Dynamic IP address (IP address that changes every time you turn on your internet).

After creating the network, click on the IP address to configure it.

![](/posts/2019/12/images/image4.jpg)

Now, select the radio button “**Custom**,” select the checkbox “**Pornography**” and then click on the button “**Apply**” to save the changes. That’s all there is to do.

![](/posts/2019/12/images/image7.jpg)

### Add OpenDNS In Windows

Configuring DNS is pretty easy with DNS Jumper, free and portable software to quickly change DNS settings in Windows. To start off, [download DNS Jumper](http://www.sordum.org/7952/dns-jumper-v2-1/), extract the folder and execute the EXE file.

![](/posts/2019/12/images/image2.jpg)

Now, select “**US – OpenDNS**” from the drop-down menu under and then click on the button “**Apply DNS**.”

![](/posts/2019/12/images/image6.jpg)

From this point forward, all the adult websites will be blocked as per your settings. If need be, you can also block other content categories like adult themes, nudity, etc., using OpenDNS

## Best Routers Supporting DNS Nameservers

\[amalinkspro type="showcase" asin="" apilink="https://amzn.to/38eBbIQ" new-window="true" addtocart="true" nofollow="true" sc-id="4" imgs="%3Ca%20href%3D%22https%3A%2F%2Fwww.amazon.com%2FTP-Link-AC1200-Smart-WiFi-Router%2Fdp%2FB07N1L5HX1%2Fref%3Das\_li\_ss\_il%3Fkeywords%3Drouters%26qid%3D1575628558%26sr%3D8-6%26linkCode%3Dli2%26tag%3Dnerdmoney-20%26linkId%3D786e3a8b92ceb4e7919a843bdfe9768f%26language%3Den\_US%22%20target%3D%22\_blank%22%3E%3Cimg%20border%3D%220%22%20src%3D%22%2F%2Fws-na.amazon-adsystem.com%2Fwidgets%2Fq%3F\_encoding%3DUTF8%26ASIN%3DB07N1L5HX1%26Format%3D\_SL160\_%26ID%3DAsinImage%26MarketPlace%3DUS%26ServiceVersion%3D20070822%26WS%3D1%26tag%3Dnerdmoney-20%26language%3Den\_US%22%20%3E%3C%2Fa%3E%3Cimg%20src%3D%22https%3A%2F%2Fir-na.amazon-adsystem.com%2Fe%2Fir%3Ft%3Dnerdmoney-20%26language%3Den\_US%26l%3Dli2%26o%3D1%26a%3DB07N1L5HX1%22%20width%3D%221%22%20height%3D%221%22%20border%3D%220%22%20alt%3D%22%22%20style%3D%22border%3Anone%20!important%3B%20margin%3A0px%20!important%3B%22%20%2F%3E" link-imgs="false" specs="MU MIMO technology (5GHz band) ~~~1200 MBPS High Speed~~~TP Link Tether app easily set up and manage your home network at home or remotely" btn-color="#ff9900" btn-text="Buy From Amazon" alignment="aligncenter" hide-prime="0" hide-image="0" hide-reviews="0" hide-price="0" hide-button="0" width="750"\]\[/amalinkspro\]

## Wrapping It Up

These are the things that you can do to block adult content on the internet and thereby create a safer environment for your children. I hope you find this article useful and thanks for spending time here.

**Also Read:**

- [Stop Being Indexed from Truecaller (Simple Steps)](https://www.techvile.in/stop-being-indexed-from-truecaller-simple-steps/)
- [Free & Fast DNS Servers For Home Routers](https://sastaeinstein.com/free-fast-and-reliable-dns-servers-for-home-router/)

If you are someone who wants to break your addiction, then stop using the internet when you are alone or whenever you are in your bedroom. Hope this helps!

Share your views in the comments section.

Cheers!

[Facebook](www.facebook.com/vibin.kishore) [Twitter](www.twitter.com/_mrSpectre) [Instagram](www.instagram.com/_.vibin._)
