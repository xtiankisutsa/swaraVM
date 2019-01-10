# swaraVM
**SwaraVM** is a mobile security virtual machine that aggregates tools and resources that are commonly used for network traffic analysis, malware analysis, digital forensics, vulnerability research and exploitation, reverse engineering, mobile and web application assessment, alongside a variety of mobile application practice labs.

SwaraVM for Android is built on top of [Security Onion](https://securityonion.net) running on [lubuntu](https://lubuntu.net). which provides full packet capture, Snort or Suricata rule-driven intrusion detection, Bro event-driven intrusion detection and powerful analysis tools.

SwaraVM provides a near perfect combination of leveraging freely available and cutting-edge open-source tools on a light weight distro to facilitate end to end to end mobile application security assessments.  

SwaraVM is developed and maintained by [@xtian_kisutsa](https://twitter.com/xtian_kisutsa) and [@r_doobie_](https://twitter.com/r_doobie_). Any contributions and suggestions for swaraVM are highly appreciated and encouraged. Issues and bugs should be reported on the issues page.  

## Use cases
Our goal in developing this project, was to bridge the gap of network traffic analysis while either assessing mobile application or analyzing mobile malware. Here are few use cases for using swaraVM.
* Running malware on lab mobile device and capturing network packets, which are forwarded to swara VM for rule detection and alerts by snort/suricata and event intrusion detection by bro IDS. 
* Pentesting web applications while passively capturing your network traffic, to allow you to analyze the packets and write intrusion detection rules for snort/suricata and bro to detect your payloads or exploits. 
* You can also use the same setup above to determine which intrusion detection signatures could be used to flag your payloads and exploits. This is by utilizing either the emerging threat (open/pro) or snort(community/registered) rulesets. 
* Assess, reverse engineer, source/bytecode review, debug, instrument and exploit mobile applications on the same virtual machine. 
* Using the mobile application labs to test and grow your skills in mobile application assessment and exploitation. 
In the the end swaraVM can be used by both red teams and blue teams depending on your use case, all in one lightweight, standalone and portable virtual machine. 

## Suggested setup
The suggested setup for end to end mobile application security that facilitates the use cases mentioned above, is as illustrated by the diagram below. 

![Alt](https://github.com/xtiankisutsa/swaraVM/blob/master/sample_setup.png)

An overview and detailed guide for configuring swaraVM as shown on the diagram above is on [this](http://www.shadowinfosec.io/2018/04/portable-mobile-app-traffic-analysis.html) blog post. 

## Inspired by
This project is inspired by [Security Onion](https://securityonion.net), [Santoku](https://santoku-linux.com/), [Androlab](https://github.com/sh4hin/Androl4b), [REMnux](https://remnux.org), [Appie](https://manifestsecurity.com/appie/), [Vezir](https://github.com/oguzhantopgul/Vezir-Project), [SIFT workstation](https://digital-forensics.sans.org/community/downloads) and the [Ultimate-Forensics-VM](https://github.com/theflakes/Ultimate-Forensics-VM).

Please visit the [wiki](https://github.com/xtiankisutsa/swaraVM/wiki) for additional information on Swara VM, including the installation guide. **Happy hacking :D** 
