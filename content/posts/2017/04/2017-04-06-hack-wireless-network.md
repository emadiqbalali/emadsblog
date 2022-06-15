---
title: "How To Hack WiFi WPA/WPA 2 Network With Kali Linux?"
date: "2017-04-06"
categories: 
  - "hacker"
---

> **Disclaimer:** Hacking into some else network is illegal. This guide is for educational purposes only. I don't take responsibilities of  how you use this information.

In this article, you are going to learn to hack WPA/WPA2 with reaver in Kali Linux or other Linux Operating System. If you're totally new to Linux then you can download [Kali Linux](https://kali.org) on your PC or alongside Windows using Dual Boot. If you want to do that, check out recommended reading at the end of the article.

We will first take a look into some abbreviations used in this articles.

- **WPS:** _Wi-Fi Protected Setup_  
    This is a type of setup in which 8 digit PIN is involved in helping you to connect to the Router. This method consumed less time and is reliable. However, this PIN consists of only digits, therefore, it is vulnerable to brute-force attacks. This **PIN also reveals** the WPA/WPA2 password of the wireless network.
- **WPA/WPA2:** _Wi-Fi Protected Access_  
    Both are the forms of Wireless Security Protocols. It helps in securing Wireless Computer Networks.

## You Need:

1. [Kali Linux](http://kali.org/) (Pre-Installed With Reaver) / Any Linux OS such as **Ubuntu**
2. Compatible Wireless Adapter \[[Alfa AWUS036H](https://amzn.to/2CVcpAi)\]
3. Little Patience
4. The Wireless Network Signal should be strong to avoid packet losses.

## Installing Reaver (Other Linux Users)

If you're using Kali Linux then you can skip this step. Kali Linux have all pentesting tools pre-installed including Reaver.

- Boot into Linux.
- Connect to LAN or Wireless network for Internet access in order to download Reaver Package
- Open the fresh terminal after connecting to the internet.
- Type the following command **_"apt-get update"_** without double quotations to fetch the updates first.
- Now, type in **_"apt-get install reaver"_** to install the reaver package.
- You have successfully installed Reaver on your Linux OS.

## Steps To Hack WPA/WPA2 With Kali Linux Using Reaver

- Open a new terminal.
- Type the command **_"airmon-ng start wlan0"_** to enable Wireless Monitor Mode for monitoring Wireless Network you're going to target.
- Open up another terminal now, type in command **_"wash -i mon0"_** to check if your target Wireless Network have WPS enabled so that it can be hacked with Reaver. If not, then you have to go with [Standard Bruteforce Attack on Handshake](https://medium.com/@brannondorsey/crack-wpa-wpa2-wi-fi-routers-with-aircrack-ng-and-hashcat-a5a5d3ffea46) to obtain password with dictionary. You may get **fcs error**, if you do so then your wireless network adapter cannot inject packets but still hack into network. Simply press **"CTRL+C"** to stop the running command and then type **_"wash -i mon0 --ignore-fcs"_** and now you should see the network listed showing you if they have WPS enabled or not.
- You can stop the running command using **CTRL+C**
- Now, it's time to attack the target network to bruteforce the 8 Digit WPS PIN for obtaining WPA/WPA2 Shared Password.
- Keep the scanned result aside.
- Open a fresh terminal and type in **_"reaver -i mon0 -b \[BSSID\] -c (channel) -vv"_**
- Breaking down above command for you, **BSSID** of target network which is found in scanned result terminal, **mon0** is a monitor mode of Wireless Adapter created in 2nd step while **\-c** is channel of target network also found in the scanned results.
- The Reaver will now starting bruteforcing the WPS PIN. It may take 10 minutes to 10 hours depending on PIN.
- **In modern routers,** the security is tight and this attack is patched by limiting the number of attempts made to enter the PIN and if exceeded the WPS is locked and reaver is halted.
- If such thing happens, then it is not possible to crack the WPA/WPA2 password using Reaver. You can still put your dictionary on work by bruteforcing the handshake of target network.
- If you happen to be lucky enough, the PIN will be cracked within a matter of minutes or hours. The end results of successful attack is given below.

[![](images/Screenshot%2Bfrom%2B2013-06-04%2B20-48-55.png)](http://3.bp.blogspot.com/-lVrf4583FcE/VesBl57-xvI/AAAAAAAAARc/BDhoOEPFdAI/s1600/Screenshot%2Bfrom%2B2013-06-04%2B20-48-55.png)

If you want to learning hacking then checkout [amazing source to hacking guides](https://allabouthacking.com). They have amazing content to protect yourself from hackers and also learn their techniques to become a hacker yourself. They explain hackers and get you the truth.

**Recommended Reading:**

[Installing Kali Linux As A Dual Boot](https://sastaeinstein.com/2015/09/how-to-install-kali-linux-windows-dual-boot.html)
