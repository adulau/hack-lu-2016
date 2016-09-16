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
------------------
Clarence Chio graduated with a B.S. and M.S. in Computer Science from Stanford, specializing in data mining and artificial intelligence. He currently works as a Security Research Engineer at Shape Security, building a product that protects high valued web assets from automated attacks. At Shape, he works on the data analysis systems used to tackle this problem. Clarence spoke on Machine Learning and Security at DEFCON 24, PHDays, BSides Las Vegas and NYC, Code Blue, SecTor, and Hack in Paris (2015­2016). He had been a community speaker with Intel, and is also the founder and organizer of the ‘Data Mining for Cyber Security’ meetup group, the largest gathering of security data scientists in the San Francisco Bay Area.

Bootstrapping an Architectural Research Platform
------------------------------------------------
by Jacob Torrey

This talk aims to provide the fundamental architectural knowledge and resources for a security research interested in misuse of the x86 platform to conduct their own research with less “boiler-plate”. Covering the privileges and architectural events that different CPU rings can monitor, a few basic research hypervisors, and new technologies coming into the mainstream; this talk will aid researchers to rapidly focus on the research questions and not the setup.

Bio: Jacob Torrey 
-----------------
Jacob Torrey is an Advising Research Engineer at Assured Information Security, Inc. where he leads the Computer Architectures group and acts as the site lead for the Colorado branch. Jacob has worked extensively with low-level x86 and MCU architectures, having written a BIOS, OS, hypervisor and SMM handler. His major interest is how to (mis)use an existing architecture to implement a capability currently beyond the limitations of the architecture. In addition to his research, Jacob volunteers his time organizing conferences in Denver (RMISC & BSidesDenver) and regular meet-ups across the front range. Twitter: @JacobTorrey

badGPO - Using GPOs for Persistence and Lateral Movement
--------------------------------------------------------
by Yves Kraft, Immanuel Willi

Bio: Yves Kraft
---------------

Bio: Immanuel Willi
-------------------

[WORKSHOP] Introduction to Security Onion
-----------------------------------------
by David Szili

Security Onion is a Linux distribution based on Ubuntu, designed for security analysts. It contains many security tools such as Snort, Suricata, Bro, OSSEC, Sguil, Squert, ELSA, NetworkMiner, etc. to create a platform for network security monitoring. The unique combination of features and concepts like pivoting from one tool to another one, having different network security monitoring data types (like full packet capture) and the capability to form a distributed sensor architecture make Security Onion one of the most powerful solutions which often outperforms many of the commercial products.

The goal of this introductory workshop is to familiarize the participants with Security Onion, guide them through the first steps of setting it up and start analyzing traffic. The first part of the workshop will be about installing and configuring Security Onion in a Virtual Machine. The next section will be a quick walk-through to the primary interfaces (Squert, Sguil, ELSA), the different NSM data types and pivoting between interfaces and data types. At the end of the workshop, we will take a look at a few exercises and real life case studies, replay traffic and perform analysis using the tools and data types available in Security Onion.

Requirements for the workshop:
- A laptop with at least 8 GB of RAM and more than 20 GB of free disk space (VT-x support must be enabled on the host system).
- Application to run Virtual Images (type-2 hypervisor), such as VMWare Workstation (recommended), VMWare Player, VirtualBox or similar software.

Attendees should download the latest Security Onion image in advance from GitHub:
https://github.com/Security-Onion-Solutions/security-onion/blob/master/Verify_ISO.md

Bio: David Szili 
----------------
David Szili is a freelancer IT Security Consultant with penetration testing, security monitoring, incident response and forensics background, previously working for companies like POST Telecom PSF, Dimension Data and Deloitte.

David has two Master's degrees in Computer Engineering and in Networks and Telecommunication and a Bachelor's degree in Electrical Engineering. He also holds several IT security certifications such as GSEC, GCIA, GCIH, GMON, GMOB, OSCP, OSWP and CEH.

In his spare time, David likes working on hobby electronics projects, develop new IT security tools or sharpen his skills with CTFs and bug bounty programs.

Credential Assessment: Mapping Privilege Escalation at Scale
------------------------------------------------------------
by Matt Weeks

In countless intrusions from large retail giants to oil companies, attackers have progressed from initial access to complete network compromise. In the aftermath, much ink is spilt and products are sold on how the attackers first obtained access and how the malware they used could or could not have been detected, while little attention is given to the credentials they found that turned their access on a single-system into thousands more. This process, while critical for offensive operations, is often complex, involving many links in the escalation chain composed of obtaining credentials on system A that grant access to system B and credentials later used on system B that grant further access, etc. We’ll show how to identify and combat such credential exposure at scale with the framework we developed. We comprehensively identify exposed credentials and automatically construct the compromise chains to identify maximal access and privileges gained, useful for either offensive or defensive purposes.

Bio: Matt Weeks
---------------
Matt Weeks currently leads root9B's research and development arm. As a researcher, he has uncovered a number of major vulnerabilities in various products. He also developed for the Metasploit framework, runs the site http://www.scriptjunkie.us/ and the southwest CCDC regional red team. Previously, he led the USAF's intrusion forensics and reverse engineering lab and the creation of their enterprise hunt teams.

#KillTheHashes 30 million Malware DNA profiling exercise
--------------------------------------------------------
by Luciano Martins, Rodrigo Cetera

Similar to human fingerprints, every malware has its own unique digital fingerprint that differentiates it from others.  As a result, malware will always attempt to hide its true self by deleting or changing this information to avoid detection by antivirus companies and malware researchers.

Doing malware profiling allows malware hunters and analysts to really interrogate the internals of malware and perform searches over a large number of file characteristics. For instance, instead of relying on file-level hashes, we can compute other features such as imported functions, strings, constants, file segments, code regions, or anything that is defined in the file type specification, we had built a software to perform those tasks CodexGigas that provides us with more than 142 possible searchable patterns, that can be combined.

Since malware developers go to great lengths to obfuscate their characteristics, it is often difficult for by researchers and malware analysts to identify multiple characteristics and correlation points.

By analyzing malware internals, the algorithm is able to build characteristic families to which a new sample can be categorized and therefore identified for specific behavior, enabling early detection of new malware by comparing against existing malware.

We will demonstrate the results of our work and the techniques and tool used to derive these results.

Bio: Luciano Martins
--------------------
Luciano Martins is a Director in Threat Intel & Analytics at Deloitte. who works in the area of vulnerability assessment, black box testing, personnel training, hacking skills, malware, and strong reverse engineering skills. Luciano has nearly 20 years of experience in security atmosphere. Prior to Deloitte, he founded the USSR LABS research group in Argentina and led it for five years.

Bio: Rodrigo Cetera
-------------------
Rodrigo Cetera is a security researcher in the Deloitte Argentina team, student of Software and Electronic Engineering at UBA (University of Buenos Aires). C++/Python developer and Electronic Technician. Former science teacher, always fascinated by know how the world works. Rugby fan and amateur guitar player.

Bio: Javier Bassi
-----------------
Javier Bassi is a security researcher in the Deloitte Argentina team, student of computer engineering at UCA (Universidad Católica Argentina). Angular.js / Python / Ruby on Rails/ Laravel developer and Data visualization with Splunk/D3. Enthusiast of web security and cryptography, evangelizer of Docker.

When Crypto Fails
-----------------
by Yaniv Balmas, Ben Herzog

"There is a theory which states that if ever anyone discovers exactly how to properly use cryptography, it will instantly disappear and be replaced by something even more bizarre and inexplicable.
There is another theory which states that this has already happened."

Cryptography is no longer a niche malware feature. It has become the weapon of choice to subject victims to extortion, preform covert communications, achieve stealth and much more. 
Almost no crimeware bag of tricks is complete without a nasty ransomware binary somewhere in it.

Like any other dangerous weapon, cryptography should be handled with care; in the wrong hands, it can easily become a double-edged sword - and, in fact, it does. There appears to be no upper bound for how ill-designed cryptography can be. Whenever you think you have seen the worst of it... Well, you better think again.

Our talk will showcase several real-world cryptographic disasters encountered by our researchers. Some are more well-known than others, but all have had consequences - for the attacker as well as their victims. 

Trying to extract value from these failures is often a crapshoot. In some cases, there is not much to do but to watch cryptography fail and laugh\cry. However, in other cases - especially if you know what to look for - you may be able to use cryptographic failures to your advantage and subvert the original intent of the malware to your benefit.

This presentation will try to educate the audience on the common methods that can be employed to identify those failures, and perhaps save yourself or others from a very sticky situation.
Once our presentation is over we will also release a tool we designed that can be used for triage of encrypted files, aimed to help you do just that.

Bio: Yaniv Balmas
-----------------

Bio: Ben Herzog
---------------


