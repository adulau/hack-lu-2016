---
layout: page
title: Talks at Hack.lu 2016
excerpt: "Talks at Hack.lu 2016"
modified: 2016-03-14T19:44:38.564948-04:00
image:
  feature: talks-s.jpg
  credit: Alexandre Dulaunoy
  creditlink: https://www.flickr.com/photos/adulau/5129843510
---

Talks, workshops and presentations will be published after the [Call for Papers]({{ site.url }}/blog/Call-for-Papers/). Feel free to submit your presentations or researches to be part of the 2016 edition.

Talks
=====

Keynote - 
----------------------------------------------------------------
by Quinn Norton

Text.


Bio: Quinn Norton
-----------------

Text.


Cyber Grand Shellphish: Shellphish and the DARPA Cyber Grand Challenge
----------------------------------------------------------------------
by Kevin Borgolte

Autonomous hacking is becoming a reality. Over the last years, DARPA organized
the Cyber Grand Challenge (CGC), a security competition in which participants
had to develop a system able to automatically exploit and patch binaries
without any manual interaction.

We qualified for the final event and fielded our Cyber Reasoning System, the
Mechanical Phish, against six other competitors. Our system placed third
overall, was the first self-funded team, and the first academic-only team.

In this talk, we introduce Mechanical Phish. We present the challenges we faced
and tackled, and the solutions we implemented for them while developing one of
the first fully-autonomous hacking systems, which spans over 100,000 lines of
code (mostly in Python).

We have open-sourced Mechanical Phish and we demonstrate how it can be used to
automatically find bugs, create exploits, and patch vulnerable binaries.

Specifically, Mechanical Phish uses a combination of symbolic execution
(powered by angr, the binary analysis platform developed at UC Santa Barbara)
and fuzzing to find bugs. From exploitable bugs, it automatically generates
proofs of vulnerability to show code execution capabilities. In addition, our
system patches existing binaries to make them resilient against known and
unknown attacks with negligible performance impact. Finally, given the
hardware-setup and the no-human-intervention policy of the Cyber Grand
Challenge final event, we will touch on how we designed Mechanical Phish to be
extremely realiable, efficient in resource usage, and a fault-tolerant
distributed system.

Bio: Kevin Borgolte
-------------------
Kevin Borgolte is a PhD candidate in the Computer Science department at UC
Santa Barbara. He is an active member of the Shellphish Capture the Flag team,
played with them various DEFCON CTFs in the past years, and won third place
with some other selected members at the DARPA's Cyber Grand Challenge, which
came with a total of $1,500,000 of prize money including the qualification
prize. Kevin has also been an organizer of the International Capture the Flag
contest, which is being held annually since 2001. Kevin published at top-tier
academic security conferences like USENIX Security, ACM CCS, and WWW. In his
research, he focuses on data-driven security and spans from web-based malware
and threats to cybercrime, the underground economy, and large-scale abuse to
adversarial machine learning. He also dabbles in automatic vulnerability
discovery and exploitation.


WiFi Exploitation: How passive interception leads to active exploitation
------------------------------------------------------------------------
by Solomon Sonya

When was the last time you thought to yourself, hmm, I wonder if an attacker is exploiting my smart phone and laptop as a result of merely leaving my WiFi enabled? Or, when did you think: I wonder if a person can create a profile about me and possibly determine where I live, work, and places I have been simply via passive interception of the 802.11x frames beaconed from my devices? Ok, let's go a bit further: when was the last time you realized your smart phone is wirelessly leaking details regarding every network you have stored on your device for everyone to see and when did you ever consider that an attacker could intercept your beacons, establish a rogue AP mimicking exactly what you are looking for, and MiTM your system directly back to the attacker automatically? Do you even know the information your smart phone is constantly broadcasting out via that wireless NIC of yours? 

Welp, if any of these questions take you by surprise, then this talk may be of particular interest to you. I show you exactly how to engineer a distributed sensor network that captures, parses, interprets, and visualizes 802.11x frames/messages in order to build the picture of devices communicating within the sensor mesh. Next, I show how to build the connector agents to resolve GPS location of devices in the area and extracted from your device's broadcasted frames. After this, I'll show you how we interface with Google Map to interactively display the location profiles we create on users intercepted within the area. Finally, we go into carrying out MiTM attacks based on what your devices is requesting to automatically exploit the user without their knowledge. We conclude with enhancements required to better secure your devices from future exploitation.

This talk wouldn't be complete without a brand new tool release! Developing a framework like this is not as difficult or costly as you might think. I'll show you exactly how to do it. And if the coding and parsing of raw 802.11 frames is not your cup of tea, no worries at all. This talk talk releases and demo's a new framework I've built called Theia Sensor Suite that automatically analyzes all of this data and visualizes it for you in a robust GUI and framework. 802.11 exploitation will never go away, so let’s get started!

Bio: Solomon Sonya
------------------
missing

[WORKSHOP] Android malware reverse engineering
----------------------------------------------
by Axelle Apvrille

This workshop explains how to reverse engineer Android malware. 
After some brief explanation, attendees will be provided with a few recent samples such as Android/SpyBanker (May 2016), Android/Xiny (May 2016) or Riskware/InnerSnail (June 2016). They will learn how to reverse those, step by step.

The course will be split in two parts. The first part covers the "basics" - which are sufficient to handle most samples. The second part dives into more advanced consideration such as dealing with obfuscated or packed samples.

Attendees bring their own laptop + install VirtualBox, or docker. 

Bio: Axelle Apvrille
--------------------
Axelle Apvrille (@cryptax) is a happy senior researcher at Fortinet. Her research focuses on any strange virus on so-called 'smart' devices, ranging from smartphones to IoT.
She enjoys CTFs, especially at Hack.Lu, among the pic0wn team, though her best achievements are at drawing comic strips about it (http://picolecroco.free.fr/sstic/index.html).

Exploiting and attacking seismological networks.. remotely
----------------------------------------------------------
by James Jara

In this presentation we are going to explain and demonstrate step by step in a real attack scenario how a remote attacker could elevate privileges in order to take control remotely in a production seismological network located at 183mts under the sea. We found several seismographs in production connected to the public internet providing graphs and data to anyone who connects to the embed web server running at port 80. The seismographs provide real time data based in the perturbations from earth and surroundings, we consider this as a critical infrastructure and is clear the lack of protection and implementation by the technicians in charge.

We are going to present 3 ways to exploit the seismograph which is segmented in 3 parts: 
Modem (GSM, Wi-Fi, Satellite, GPS,Com serial) {web server running at port 80 , ssh daemon} 
Sensor (Trillium in this case) Battery (1 year lifetime) These vulnerabilities affect the Modem (Taurus) which is directly connected to the sensor (Trillium) , a remote connection to Taurus modem it’s all that you need to compromise the whole seismograph network. 

After take control we are be able to mofify the packet seismic data in order to inject false information to the main acquisition server now as apollo (nanometrics) or his open source equivalent seiscomp3 . 
We discovered this equipment using a IoT search engine developed in costa rica by bertin bervis and james jara. we call it NetDB - The Network Database Project
We collect 24/7 the digital fingerprint ssl certificate metadata and geospatial information of all servers around the world.

Bio: James Jara
---------------
James Jara is the co-founder of Spartug and   co-founder/CTO of NETDB.IO , a search engine of internet of things focused in info-security research. He likes Bitcoin Industry, Delphi, Open Source and framework development and gave various presentations on security conferences like EkoParty,DragonJar,Defcon,BlackHat. Interested machine learning for mobile, Internet of Things (IoT) devices and industrial systems used in critical infrastructure networks. Sport-coder! 
twitter.com/jamesjara

Exploit generation and JavaScript analysis automation with WinDBG
-----------------------------------------------------------------
by Fitzl Csaba

Our presentation will cover two different topics, which will show how easy and powerful is to automate various tasks with WinDBG.
Part 1: Exploit generation
Many people are familiar with scripts which can help during an exploit development. But what if we automate the entire process once we have the bug? In the presentation we will show a tool that can take a POC BoF exploit (which generates a crash / EIP overwrite) and from that it can automatically generate a fully working exploit.
Part 2: JavaScript analysis automation
Javascript code deobfuscation always presents a challenge for malware analysts, analysis being time consuming, sometime even anti-debugging techniques make it more difficult.
What if we had a mechanism to see into the very core of the JavaScript engine and the DOM and be able to track down what the malware was up do without having to make any changes to the code and without giving the malware a chance to sense a debugger being present? Eval? Document.write? Lambdas? No problem!

Bio: Fitzl Csaba
----------------
Csaba graduated in 2006, at the Budapest University of Technology and Economics as a computer engineer. He worked at Getronics as a Cisco support engineer for two years, and in 2008 he joined ExxonMobil, where he spent his time with designing and supporting global networks for 4 years. In the past four years, he is looking for information security breaches in the company's network, and his area of focus is network forensics and malware analysis. He currently holds several security certifications (OSWP, OSCP, OSCE, OSEE, CEH, ECSA, CHFI, GREM, GMOB, SISE).
Desbordes-Korcsev Miklos:
Miklos graduated in 1998 from Technical University of Budapest as Electrical Engineer in the field of Robotics. He has 20 years IT experience in application development, application support, system administration, electronic data interchange and cyber security. In the last 9 years he's been working for ExxonMobil in several roles, in the past 2.5 years he's been doing offensive PoC development, malware analysis and breach investigation.

Spy Hard with a Vengeance: How one city stood up to the Department of Homeland Security
---------------------------------------------------------------------------------------
by aestetix, Brian Hofer

This talk will cover the reign of surveillance that has secretly taken over the United States at the local level through use of Federal grant money, and offer suggestions on how we can fight back. It’s the story of how the Department of Homeland Security (DHS) tried to create a fusion center in Oakland, California. In particular, we'll be sharing details of the Oakland privacy policy we helped create in response to this intrusive spy system, and the advocacy that led to its creation. Our hope is to teach the framework we created, shed light on how these issues affect both Americans and Europeans, and how businesses and governments can find a balance between security and privacy.

Bio: aestetix 
-------------
aestetix served on the DAC ad hoc privacy committee as a technical
expert. In addition, he has been involved in many privacy−aware projects,
including Noisetor, the first nonprofit sponsored Tor Exit Node in the United
States, and the HOPE 2008 and 2010 badges, which involved RFID location aware
social networking. He also refuses to eat hot dog buns on Sundays, in accordance
with the wishes of Our Goddess.

Bio: Brian Hofer
----------------
Brian Hofer is a member of the Oakland Privacy Working Group, which formed to
oppose the DAC. He chaired the DAC ad hoc privacy committee, which has since
introduced two City Council adopted privacy and data retention policies, along
with an ordinance making the privacy committee permanent.


The Metabrik Platform: Rapid Development of Reusable Security Tools
-------------------------------------------------------------------
by Patrice Auffret

During the course of a penetration test, a malware analysis, a forensic analysis or a Capture The Flag contest, who has never been in the situation of having to develop
The Metabrik Platform [1] goal is to normalize how we use tools and how they interoperate together by providing a Platform as a UNIX shell, merged with a Perl REPL interpreter and a virtually infinite number of Briks: small reusable components that just do one task. Learning it is as simple as knowing the five Commands.

You glue Briks together through the Shell. Idea is to have a set of common bricks having their own purpose and connect them to create a new tool or Brik. The more you write Briks, the more complex tasks you will be able to achieve. Many Briks were written from already existing ones and Metabrik itself is written using Briks. In the end, Metabrik is a development platform which brings normalization and weaponization for everyday tools, being new or existing ones.

We will cover forensic::scalpel Brik as an example of improving existing tools by glueing with new Briks. We will then show how we solved a root-me challenge by using just a few Briks. As another example, we will show VM instrumentation for extracting IOCs from malwares. More examples are available on the Web site [1] and newest ones will be presented during the conference thanks to the now more than 200 Briks.

Bio: Patrice Auffret
--------------------
Patrice Auffret (AKA GomoR) is a senior security expert specialized in network protocols hacking, network discovery and big data analytics.

He is author of multiple Perl modules to craft network packets and analyze responses (Net::Frame framework, SinFP3 OS fingerprinting suite or the OSPF Attack Shell).

He writes articles in French security magazine MISC and speaks at various security conferences including IT Underground 2007, SSTIC 2008, hack.lu 2012, EuSecWest 2012, ekoparty 2012 and SSTIC 2016.

2016: The Infosec Crossroads
----------------------------
by Saumil Shah

"Today's attacks succeed because the defense is reactive". I have been researching attacks and offensive techniques since the past 16 years. As the defenses kept catching up and closing open doors, we attackers looked for new avenues and vectors. This talk looks back on the state of defenses during my days of One-Way Web Hacking in 2001 to Stegosploit in 2016, and a common pattern emerges. Defense boils down to reacting to new attacks and then playing catch-up. It is time to take another look at defense strategy. In this talk I present the basics of what should be the next evolution of pro-active defense architecture.

Bio: Saumil Shah
----------------
Saumil Shah, is the founder and CEO of Net-Square, providing cutting edge information security services to clients worldwide. Saumil is an internationally recognized conference speaker and instructor for over 15 years. He is also the co-developer of the wildly successful "Exploit Laboratory" courses and authored two books titled "Web Hacking: Attacks and Defense" and "The Anti-Virus Book".

Saumil holds an M.S. in Computer Science from Purdue University, USA and a B.E. in Computer Engineering from Gujarat University. He spends his leisure time playing Pacman, flying kites, traveling around the world and taking pictures.

Saumil Udayan Shah - CEO, Net-Square - @therealsaumil

Unveiling the attack chain of Russian-speaking cybercriminals
-------------------------------------------------------------
by Wayne Huang, Sun Huang

Existing research on the Asprox actor has focused primarily on the malware they spread, but little has been published on who they are, how they operate and spread malware, and what resources they own. In this rare talk, we will disclose our many years of deep research on this actor: for example, since their initial operation in 2007, the Asprox gang now owns 2+ billion compromised emails, 2+ million compromised web servers (backdoored with webshells), 0.9+ million compromised SMTP accounts (some of which belong to the US military), 0.4+ million compromised FTP accounts, and SSH access to 1200+ compromised servers.
We will detail how they’ve evolved into their currently sophisticated infection infrastructure, including their multiple layers of distribution and command-and-control servers, their anti-detection proxy servers, their malware obfuscation tool chain, their means of infecting endpoints, their large scale tool to auto-compromise websites and inject webshells, and their evolution in 2014 to Android malware and mobile botnets.
We will study statistics such as daily downloads and conversion rate, and will explain their monetization methods within multiple underground economies, and the economics. Finally, we’ll cover how we’ve managed to collect our data, how we analyzed the data, and the many techniques we used in tracking this actor.

Bio: Wayne Huang
----------------
Wayne Huang was Founder and CEO of Armorize Technologies, and is now VP Engineering at Proofpoint. Huang is a frequent speaker at security conferences, including BlackHat '10, DEFCON '10, RSA '07 '10 '15 ‘16, SteelCon '16, Troopers '16, AusCERT '16, SyScan '08, '09, OWASP '08, '09, Hacks in Taiwan '06 '07, WWW '03 '04, PHP '07 and DSN '04. Into security since 7th grade, he has led teams to develop security products ranging from source code analysis, web application firewall, vulnerability assessment, exploit & malware detection, anti-malvertising, email security, and APT defense. He received his Ph.D. in EE from National Taiwan University, and his B.S. and M.S. in CS from NCTU. He holds two US patents on source code analysis.

Bio: Sun Huang
--------------
Sun Huang is a Senior Threat Researcher at Proofpoint. He has more than 9 years of experience in information security.  Sun has discovered many Web application 0days, including those of CMS and C2 Panel. Sun has participated in many security contests, and was one of the top 10 researchers in Paypal's 2013 Bug Bounty Wall of Fame. He was also the third place AT&T bug reporter in 2013.  Sun currently holds CCNA, ECSS, CEH, and PMP certifications. Sun has presented at RSA '15 '16, SteelCon '16, Troopers '16, AusCERT '16.

Machine Duping: Pwning Deep Learning Systems
--------------------------------------------
by Clarence Chio

Deep learning and neural networks have gained incredible popularity in recent years, but most deep learning systems are not designed with security and resiliency in mind, and can be duped by any attacker with a good understanding of the system. In this talk, we will dive into popular deep learning software and show how it can be tampered with to do what you want it do, while avoiding detection by system administrators. Besides giving a high level overview of deep learning and its inherent shortcomings in an adversarial setting, we will focus on tampering real systems to show real weaknesses in critical systems built with it. In particular, this demo­driven session will be focused on manipulating an image recognition, speech recognition, and phishing detection system built with deep learning at the core.

Bio: Clarence Chio
Clarence Chio graduated with a B.S. and M.S. in Computer Science from Stanford, specializing in data mining and artificial intelligence. He currently works as a Security Research Engineer at Shape Security, building a product that protects high valued web assets from automated attacks. At Shape, he works on the data analysis systems used to tackle this problem. Clarence spoke on Machine Learning and Security at DEFCON 24, PHDays, BSides Las Vegas and NYC, Code Blue, SecTor, and Hack in Paris (2015­2016). He had been a community speaker with Intel, and is also the founder and organizer of the ‘Data Mining for Cyber Security’ meetup group, the largest gathering of security data scientists in the San Francisco Bay Area.
