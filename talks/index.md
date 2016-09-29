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


Keynotes
========

Stressed out? Denial of service attacks from the providers’ perspective
-----------------------------------------------------------------------
by Alice Hutchings

The most frequent users of ‘booter’ or ‘stresser’ services are online gamers. These services are used to gain an advantage over an opponent by ‘booting’ them off the game with a denial of service attack. Booter services have customer-facing websites, whereby payments are taken for subscriptions, and attacks are requested. In order to understand this black market resource, we asked those providing the services to tell us about themselves and their activities. The operation of booter services requires not just technical expertise, but also information about the market for denial of service attacks, and how to monetise this. I will talk about how this knowledge is obtained, exposure to these services, and the escalation from using to operating booter services, and to other forms of cybercrime.

Bio: Alice Hutchings
--------------------

Dr Alice Hutchings is a Senior Research Associate at the Computer Laboratory, University of Cambridge. A criminologist, her research interests include understanding cybercrime offenders, and the prevention, intervention and disruption of online crime. She is a researcher in the Cambridge Cloud Cybercrime Centre, a multi-disciplinary initiative combining expertise from the University of Cambridge's Computer Laboratory, Institute of Criminology and Faculty of Law.


Keynote - TBA
-------------
by Quinn Norton

TBA

Bio: Quinn Norton
-----------------

Quinn Norton, internet journalist and essayist, previously of Wired and The Message. I read too much history, use too much technology, obsess too much about security, know too much nerdy stuff, and am way too interested in the Mongolians.
Nothing Ever Ends is a fast romp though the history of computer and internet culture, from over two thousand years ago to several years in the future. I’ll tell the stories of some of key players in the history of the net, including the 19th century robber barons in America, Han dynasty feng shui practitioners, God, the RIAA, 90s software pirates, a little-know greek goddess, the Seattle Police Department. Over enough time, all the consequences become unintended. But all those unintended consequences give us the internet we have now, and the future we will have.


Talks
=====

Exploiting and attacking seismological networks... remotely
-----------------------------------------------------------
by Bertin Bervis Bonilla and James Jara

In this presentation we are going to explain and demonstrate step by step in a real attack scenario how a remote attacker could elevate privileges in order to take control remotely in a production seismological network located at 183mts under the sea. We found several seismographs in production connected to the public internet providing graphs and data to anyone who connects to the embed web server running at port 80. The seismographs provide real time data based in the perturbations from earth and surroundings, we consider this as a critical infrastructure and is clear the lack of protection and implementation by the technicians in charge.

We are going to present 3 ways to exploit the seismograph which is segmented in 3 parts: Modem (GSM, Wi-Fi, Satellite, GPS,Com serial) {web server running at port 80 , ssh daemon} Sensor (Device collecting the data from ground or ocean bottom) Battery (1 year lifetime) Apollo server (MAIN acquisition core server) These vulnerabilities affect the Modem which is directly connected to the sensor , a remote connection to the modem it's all that you need to compromise the whole seismograph network. After got the root shell our goal is execute a post exploitation attack , This specific attack corrupts/modifies the whole seismological research data of a country/ area in real time. We are going to propose recommendations and best practices based on how to deploy a seismological network in order to avoid this nasty attacks.

Bio: Bertin Bervis Bonilla
--------------------------

Is a  researcher in offensive security reverse engineering and network attacks and defense, Bertin has been speaker in several security conferences like DEFCON ,BlackHat ARSENAL, OWASP Latin america Tour , DragonJAR conference ,EKOPARTY and all technical universities in his country .
He is the founder of NetDB - The Network Database project , a computer fingerprint/certificate driven search engine. Formerly is a network engineer working for a five letters us networking company in San Jose Costa Rica.

Bio: James Jara
---------------

Is the founder and CTO of NETDB.IO , a search engine of internet of things focused in info-security research. He likes Bitcoin Industry, Open Source and framework development and gave various presentations on security conferences like EkoParty. Interested machine learning for mobile, Internet of Things (IoT) devices and industrial systems used in critical infrastructure networks. Sport-coder!


Where should I host my malware?
-------------------------------
by Attila Marosi


The growth of IoT devices continues to raise questions about their role and impact in cybersecurity. Badly configured or poorly individual devices are often easy targets for malicious actors. Launching attacks at first seems more challenging due to the diversity of the ecosystem, but is actually doable and easy to execute. We explain how IoTs are a cybercriminal’s paradise:

In our SophosLabs research, we focused on a very generic attack scenario that will affect almost any device that has an FTP service. Your router or network-attached storage (NAS) are the most likely examples. These attacks typically exploit the level of trust people place on any content they see hosted on internal network shares. A successful attacker would abuse or compromise a default FTP account for guest access, place a “Trojan horse” on a visible file share and rely on human curiosity for the rest to happen. In many cases, root folders for FTP and WWW services are the same, making the attacker’s life even easier. Since many of the IoT devices publically expose FTP services world-wide, this fairly unsophisticated attack can result in a large number of infected “things” and provide great value to cybercriminals.

To assist our research, we developed an IoT scanning framework (“ScanR”) which is able to perform large scale network probes to assess the state of open FTP services and identify how many of them have been compromised . In our latest test, we utilized ScanR against 3 million open FTP servers determine the type of the device and the state of its security. The results were far worse than we expected.

Over 90% of the unprotected devices were found to be infected with at least one Malware threat or exhibiting the signs of an attack. In this talk, we’ll reveal the results of the research, exposing the number of vulnerable devices and the gigabytes of storage that is now freely available to attackers. We’ll also share the technical results of the malware analysis.

In summary, this talk will provide an insight into how the very old Internet protocols are being exploited on modern internet connected “things”, explain the risks it creates to home and corporate users and suggest recommendations on how businesses and users should be protecting themselves better against these unsophisticated, but dangerous and highly successful attack scenarios.

Bio: Attila Marosi
------------------

Attila Marosi has always worked in the information security field ever since he started in IT. As a lieutenant of active duty he worked for almost a decade on special information security tasks occurring within the Special Service for National Security. Later he was transferred to the newly established GovCERT-Hungary, which is an additional national level in the internationally known system of CERT offices. Now he works for the SophosLabs as a Senior Threat Researcher in the Emerging Threats Team to provide novel solutions for the newest threats.

Attila has several international certificates such as CEH, ECSA, OSCP, OSCE. During his free time he is reading lections and does some teaching on different levels; on the top of them for white hat hackers. He presented on many security conferences including hack.lu, DeepSEC, AusCERT, Hacktivity, Troopers, HackerHalted and NullCon.


Interesting Malware - No, I'm not kidding...
--------------------------------------------
by Marion Marschalek

There is malware, and then, there is m.a.l.w.a.r.e. Last year we got our fingers on a set of exquisite binaries which were definitely not the usual kind. No I'd never call malware sophisticated, after all that's not what it takes to be dangerous; or interesting. But those were a challenging beast, unusually intriguing.

For the lack of a better name, and given all the whacky traits the binaries come with, we dubbed the family CheshireCat. That's the pink cat in Alice's wonderland with the most stupid grin. The CheshireCat binaries have been around since 2002, some are built for workstations as old as Windows NT4, they support dial-up connections and executable header checks for the NewExecutable file format. Go figure. We came to the conclusion, someone very dedicated has built CheshireCat for very special networks and kept his operation under the radar for more than a decade.

This talk will introduce CheshireCat's implementation traits, stealth tactics and wonderous functionalities. Special attention will be paid to the retro coding style and the kind of functional obfuscation that make CheshireCat so special.

Bio: Marion Marschalek
----------------------

Marion Marschalek is Principal Malware Researcher at G DATA Advanced Analytics, focusing on the analysis of emerging threats. Marion started her career within the anti-virus industry, and then worked on advanced threat protection systems, where she built a thorough  understanding of how threats and protection systems work and at which points both have their caveats. Marschalek is a lecturer at University of Applied Sciences St. Pölten and frequently contributes to articles and papers. She is a regular speaker at international conferences and has  presented research at Black Hat, RSA, and SyScan. She also serves as a review board member for Black Hat Europe. Marschalek was listed as one of Forbe's "30 under 30" in the technology Europe division in 2016. In 2013 she was the winner of the Female Reverse Engineering Challenge, organized by RE professional Halvar Flake. She practices martial arts and finds vivid passion in taking things apart. Preferably other people's things.

House intercoms attacks: when frontdoors become backdoors
---------------------------------------------------------
by Sébastien Dudek

To break into a building, several methods have already been discussed, such as trying to find the code paths of a digicode, clone RFID cards, use some social engineering attacks, or the use of archaic methods like lockpicking a door lock or breaking a window.

New methods are now possible with recent intercoms. Indeed, these intercoms are used to call the tenants to access the building. But little study has been performed on how these boxes communicate to request and grant access to the building.

In the past, they were connected with wires directly to apartments. Now, these are more practical and allow residents to open doors not only from their classic door phone, but to forward calls to their home or mobile phone. Private houses are now equipped with these new devices and its common to find these "connected" intercoms on recent and renovated buildings.

In this presentation we will introduce the Intercoms and focus on one particular devices that is commonly installed in buildings today. Then we will present our analysis on an interesting attack vector, which already has its own history. After this analysis, we will present our environment to test the intercoms, and show some practical attacks and our results that could be performed on these devices. During this talks, the evolution of our mobile lab and some advances on the 3G intercoms attacks will be also presented.


Bio: Sébastien Dudek
--------------------

Sébastien Dudek is a security consultant at Synacktiv. His main fields of interest are radio communication technologies and network and software security. He has been a speaker at NoSuchCon and Hack.lu. He has also contributed for the French magazine MISC and blogged about various security mechanisms.


KillTheHashes 30 million Malware DNA profiling exercise
-------------------------------------------------------
by Luciano Martins, Rodrigo Cetera and Javier Bassi


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

Unveiling the attack chain of Russian-speaking cybercriminals
-------------------------------------------------------------
by Wayne Huang and Sun Huang

Existing research on the Asprox actor has focused primarily on the malware they spread, but little has been published on who they are, how they operate and spread malware, and what resources they own. In this rare talk, we will disclose our many years of deep research on this actor: for example, since their initial operation in 2007, the Asprox gang now owns 2+ billion compromised emails, 2+ million compromised web servers (backdoored with webshells), 0.9+ million compromised SMTP accounts (some of which belong to the US military), 0.4+ million compromised FTP accounts, and SSH access to 1200+ compromised servers.
We will detail how they’ve evolved into their currently sophisticated infection infrastructure, including their multiple layers of distribution and command-and-control servers, their anti-detection proxy servers, their malware obfuscation tool chain, their means of infecting endpoints, their large scale tool to auto-compromise websites and inject webshells, and their evolution in 2014 to Android malware and mobile botnets.
We will study statistics such as daily downloads and conversion rate, and will explain their monetization methods within multiple underground economies, and the economics. Finally, we’ll cover how we’ve managed to collect our data, how we analyzed the data, and the many techniques we used in tracking this actor.

Bio: Wayne Huang
----------------

Wayne Huang was Founder and CEO of Armorize Technologies, and is now VP Engineering at Proofpoint. Huang is a frequent speaker at security conferences, including BlackHat '10, DEFCON '10, RSA '07 '10 '15 ‘16, SteelCon '16, Troopers '16, AusCERT '16, SyScan '08, '09, OWASP '08, '09, Hacks in Taiwan '06 '07, WWW '03 '04, PHP '07 and DSN '04. Into security since 7th grade, he has led teams to develop security products ranging from source code analysis, web application firewall, vulnerability assessment, exploit & malware detection, anti-malvertising, email security, and APT defense. He received his Ph.D. in EE from National Taiwan University, and his B.S. and M.S. in CS from NCTU. He holds two US patents on source code analysis.

Bio: Sun Huang
--------------

Sun Huang is a Senior Threat Researcher at Proofpoint. He has more than 9 years of experience in information security.  Sun has discovered many Web application 0days, including those of CMS and C2 Panel. Sun has participated in many security contests, and was one of the top 10 researchers in Paypal's 2013 Bug Bounty Wall of Fame. He was also the third place AT&T bug reporter in 2013.  Sun currently holds CCNA, ECSS, CEH, and PMP certifications. Sun has presented at RSA '15 '16, SteelCon '16, Troopers '16, AusCERT '16.


Cyber Grand Shellphish: Shellphish and the DARPA Cyber Grand Challenge
----------------------------------------------------------------------
by Kevin Borgolte

Autonomous hacking is becoming a reality. Over the last years, DARPA organized the Cyber Grand Challenge (CGC), a security competition in which participants had to develop a system able to automatically exploit and patch binaries without any manual interaction.

We qualified for the final event and fielded our Cyber Reasoning System, the Mechanical Phish, against six other competitors. Our system placed third overall, was the first self-funded team, and the first academic-only team.

In this talk, we introduce Mechanical Phish. We present the challenges we faced and tackled, and the solutions we implemented for them while developing one of the first fully-autonomous hacking systems, which spans over 100,000 lines of code (mostly in Python).

We have open-sourced Mechanical Phish and we demonstrate how it can be used to automatically find bugs, create exploits, and patch vulnerable binaries.

Specifically, Mechanical Phish uses a combination of symbolic execution (powered by angr, the binary analysis platform developed at UC Santa Barbara) and fuzzing to find bugs. From exploitable bugs, it automatically generates proofs of vulnerability to show code execution capabilities. In addition, our system patches existing binaries to make them resilient against known and unknown attacks with negligible performance impact. Finally, given the hardware-setup and the no-human-intervention policy of the Cyber Grand Challenge final event, we will touch on how we designed Mechanical Phish to be extremely realiable, efficient in resource usage, and a fault-tolerant distributed system.

Resources:
- https://github.com/mechaphish
- https://github.com/shellphish
- https://github.com/angr


Bio: Kevin Borgolte
-------------------
Kevin Borgolte is a PhD candidate in the Computer Science department at UC Santa Barbara. He is an active member of the Shellphish Capture the Flag team, played with them various DEFCON CTFs in the past years, and won third place with some other selected members at the DARPA's Cyber Grand Challenge, which came with a total of $1,500,000 of prize money including the qualification prize. Kevin has also been an organizer of the International Capture the Flag contest, which is being held annually since 2001. Kevin published at top-tier academic security conferences like USENIX Security, ACM CCS, and WWW. In his research, he focuses on data-driven security and spans from web-based malware and threats to cybercrime, the underground economy, and large-scale abuse to adversarial machine learning. He also dabbles in automatic vulnerability discovery and exploitation.


Spy Hard with a Vengeance: How one city stood up to the Department of Homeland Security
---------------------------------------------------------------------------------------
by aestetix and Brian Hofer

This talk will cover the reign of surveillance that has secretly taken over the United States at the local level through use of Federal grant money, and offer suggestions on how we can fight back. It’s the story of how the Department of Homeland Security (DHS) tried to create a fusion center in Oakland, California. In particular, we'll be sharing details of the Oakland privacy policy we helped create in response to this intrusive spy system, and the advocacy that led to its creation. Our hope is to teach the framework we created, shed light on how these issues affect both Americans and Europeans, and how businesses and governments can find a balance between security and privacy.

Bio: aestetix
-------------
aestetix served on the DAC ad hoc privacy committee as a technical expert. In addition, he has been involved in many privacy−aware projects, including Noisetor, the first nonprofit sponsored Tor Exit Node in the United States, and the HOPE 2008 and 2010 badges, which involved RFID location aware social networking. He also refuses to eat hot dog buns on Sundays, in accordance with the wishes of Our Goddess.

Bio: Brian Hofer
----------------
Brian Hofer is a member of the Oakland Privacy Working Group, which formed to oppose the DAC. He chaired the DAC ad hoc privacy committee, which has since introduced two City Council adopted privacy and data retention policies, along with an ordinance making the privacy committee permanent.


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

Bridging political gaps with code
---------------------------------
by Okhin


One of the main mission of La Qaudrature du Net, as a NGO fighting for human right sin the digital spheres, is to develop engagement of people to pressure political bodies such as national or european parliaments.

To achieve this goal, LQDN has developped over the year a toolbox to help document the political process, to help keeping tabs on representatives through their all career, and to mobilize citizens to take actions and to reestablish dialog with these representatives.

I will discuss how this process has been going into LQDN actions and how the dynamics between code, developers and users (both internal and external) are at the core of this process.

From paying technical debt, to volunteer management, from ideological to technical points of view, let's talk about how code can be political.

Bio: Okhin
----------

Okhin is the La Quadrature du Net Tools Manager. His missions goes from maintainning infrastructure, to manage a communty of volunteer, to organising security training.

Before LQDN, he worked for the International Federation of Human Roghts (FIDH) as a member of the IT Team, and used to volunteer with the group known as Telecomix, where his interests in technics merged with politics.

WiFi Exploitation: How passive interception leads to active exploitation
------------------------------------------------------------------------
by Solomon Sonya

When was the last time you thought to yourself, hmm, I wonder if an attacker is exploiting my smart phone and laptop as a result of merely leaving my WiFi enabled? Or, when did you think: I wonder if a person can create a profile about me and possibly determine where I live, work, and places I have been simply via passive interception of the 802.11x frames beaconed from my devices? Ok, let's go a bit further: when was the last time you realized your smart phone is wirelessly leaking details regarding every network you have stored on your device for everyone to see and when did you ever consider that an attacker could intercept your beacons, establish a rogue AP mimicking exactly what you are looking for, and MiTM your system directly back to the attacker automatically? Do you even know the information your smart phone is constantly broadcasting out via that wireless NIC of yours?

Welp, if any of these questions take you by surprise, then this talk may be of particular interest to you. I show you exactly how to engineer a distributed sensor network that captures, parses, interprets, and visualizes 802.11x frames/messages in order to build the picture of devices communicating within the sensor mesh. Next, I show how to build the connector agents to resolve GPS location of devices in the area and extracted from your device's broadcasted frames. After this, I'll show you how we interface with Google Map to interactively display the location profiles we create on users intercepted within the area. Finally, we go into carrying out MiTM attacks based on what your devices is requesting to automatically exploit the user without their knowledge. We conclude with enhancements required to better secure your devices from future exploitation.

This talk wouldn't be complete without a brand new tool release! Developing a framework like this is not as difficult or costly as you might think. I'll show you exactly how to do it. And if the coding and parsing of raw 802.11 frames is not your cup of tea, no worries at all. This talk talk releases and demo's a new framework I've built called Theia Sensor Suite that automatically analyzes all of this data and visualizes it for you in a robust GUI and framework. 802.11 exploitation will never go away, so let’s get started!

Bio: Solomon Sonya
------------------

2016: The Infosec Crossroads
----------------------------
by Saumil Shah

"Today's attacks succeed because the defense is reactive". I have been researching attacks and offensive techniques since the past 16 years. As the defenses kept catching up and closing open doors, we attackers looked for new avenues and vectors. This talk looks back on the state of defenses during my days of One-Way Web Hacking in 2001 to Stegosploit in 2016, and a common pattern emerges. Defense boils down to reacting to new attacks and then playing catch-up. It is time to take another look at defense strategy. In this talk I present the basics of what should be the next evolution of pro-active defense architecture.

Bio: Saumil Shah
----------------
@therealsaumil

Saumil Shah, is the founder and CEO of Net-Square, providing cutting edge information security services to clients worldwide. Saumil is an internationally recognized conference speaker and instructor for over 15 years. He is also the co-developer of the wildly successful "Exploit Laboratory" courses and authored two books titled "Web Hacking: Attacks and Defense" and "The Anti-Virus Book".

Saumil holds an M.S. in Computer Science from Purdue University, USA and a B.E. in Computer Engineering from Gujarat University. He spends his leisure time playing Pacman, flying kites, traveling around the world and taking pictures.


Exploit generation and JavaScript analysis automation with WinDBG
-----------------------------------------------------------------
by Fitzl Csaba and Miklos Desbordes-Korcsev

Our presentation will cover two different topics, which will show how easy and powerful is to automate various tasks with WinDBG.

1.  Exploit generation Many people are familiar with scripts which can help during an exploit development. But what if we automate the entire process once we have the bug? In the presentation we will show a tool that can take a POC BoF exploit (which generates a crash / EIP overwrite) and from that it can automatically generate a fully working exploit.

2. JavaScript analysis automation Javascript code deobfuscation always presents a challenge for malware analysts, analysis being time consuming, sometime even anti-debugging techniques make it more difficult. What if we had a mechanism to see into the very core of the JavaScript engine and the DOM and be able to track down what the malware was up do without having to make any changes to the code and without giving the malware a chance to sense a debugger being present? Eval? Document.write? Lambdas? No problem!


Bio: Fitzl Csaba
----------------

Csaba graduated in 2006, at the Budapest University of Technology and Economics as a computer engineer. He worked at Getronics as a Cisco support engineer for two years, and in 2008 he joined ExxonMobil, where he spent his time with designing and supporting global networks for 4 years. In the past four years, he is looking for information security breaches in the company's network, and his area of focus is network forensics and malware analysis. He currently holds several security certifications (OSWP, OSCP, OSCE, OSEE, CEH, ECSA, CHFI, GREM, GMOB, SISE).

Bio: Miklos Desbordes-Korcsev
----------------------------

Miklos graduated in 1998 from Technical University of Budapest as Electrical Engineer in the field of Robotics. He has 20 years IT experience in application development, application support, system administration, electronic data interchange and cyber security. In the last 9 years he's been working for ExxonMobil in several roles, in the past 2.5 years he's been doing offensive PoC development, malware analysis and breach investigation.


Bootstrapping an Architectural Research Platform
------------------------------------------------
by Jacob I. Torrey

This talk aims to provide the fundamental architectural knowledge and resources for a security research interested in misuse of the x86 platform to conduct their own research with less “boiler-plate”. Covering the privileges and architectural events that different CPU rings can monitor, a few basic research hypervisors, and new technologies coming into the mainstream; this talk will aid researchers to rapidly focus on the research questions and not the setup.

Bio: Jacob I. Torrey
--------------------

Jacob Torrey is an Advising Research Engineer at Assured Information Security, Inc. where he leads the Computer Architectures group and acts as the site lead for the Colorado branch. Jacob has worked extensively with low-level x86 and MCU architectures, having written a BIOS, OS, hypervisor and SMM handler. His major interest is how to (mis)use an existing architecture to implement a capability currently beyond the limitations of the architecture. In addition to his research, Jacob volunteers his time organizing conferences in Denver (RMISC & BSidesDenver) and regular meet-ups across the front range. Twitter: @JacobTorrey

Exploiting new default accounts in SAP systems
----------------------------------------------
by Joris van de Vis


TODO


Bio: Joris van de Vis
---------------------

Joris has got extensive experience in the technical and security field of SAP.  Next to his interest in SAP Coding and SAP Technology, his main interest lies in the field of SAP platform security. He loves Helping business secure their SAP systems and perform SAP security research in his spare time. He reported over 50 vulnerabilities in SAP applications. Joris has got 15+ years of experience working for large SAP running companies and government departments. Joris is co-founder of ERP-SEC, a SAP security focused company based in the Netherlands.



badGPO - Using GPOs for Persistence and Lateral Movement
--------------------------------------------------------
by Yves Kraft and Immanuel Willi

Group Policy is a feature which provides centralized management and configuration functions for the Microsoft operating system, application and user settings. Group Policy is simply the easiest way to reach out and configure computer and user settings on networks based on Active Directory Domain Services (AD DS). Such policies are widely used in enterprise environments to control settings of clients and servers: registry settings, security options, scripts, folders, and software installation and maintenance, just to name a few. Settings are contained in so-called Group Policy Objects (GPOs) and can be misused in a sneaky way to distribute malware and gain persistence in an automated manner in a post exploitation scenario of an already compromised domain. In a proof of concept, inspired by Phineas Fishers' article about pwning HackingTeam, we will show how persistence and lateral movement in a compromised company network can be achieved, and demonstrate some PowershellEmpire Framework modules which we created. PowershellEmpire is basically a post-exploitation framework that utilises the widely-deployed PowerShell tool for all your system-smashing needs. There are already functionalities built-in regarding GPOs. We tried to further evolve the miss-use of GPOs in additional scenarios. Furthermore, we will discuss some countermeasures including detection and prevention mechanisms

Bio: Yves Kraft and Immanuel Willi
----------------------------------

Yves and Immanuel are both penetration testers at Oneconsult AG. Their daily business is to build and deconstruct things.
Yves works as a security consultant at Oneconsult, focusing on penetration tests, security consulting and training. He was promoted to team leader and branch manager Bern a year ago. As a former system and network engineer he managed several servers, applications and networks including systems at a large Swiss university, financial services and public administration among other industries.
Immanuel worked several years as a system administrator at a university. When moving to another higher education institution he was appointed head of the internal IT services department. His work at Oneconsult is focused on penetration tests and security consulting.


Machine Duping: Pwning Deep Learning Systems
--------------------------------------------
by Clarence Chio

Deep learning and neural networks have gained incredible popularity in recent years, but most deep learning systems are not designed with security and resiliency in mind, and can be duped by any attacker with a good understanding of the system. In this talk, we will dive into popular deep learning software and show how it can be tampered with to do what you want it do, while avoiding detection by system administrators. Besides giving a high level overview of deep learning and its inherent shortcomings in an adversarial setting, we will focus on tampering real systems to show real weaknesses in critical systems built with it. In particular, this demo­driven session will be focused on manipulating an image recognition, speech recognition, and phishing detection system built with deep learning at the core.

Bio: Clarence Chio
------------------
Clarence Chio graduated with a B.S. and M.S. in Computer Science from Stanford, specializing in data mining and artificial intelligence. He currently works as a Security Research Engineer at Shape Security, building a product that protects high valued web assets from automated attacks. At Shape, he works on the data analysis systems used to tackle this problem. Clarence spoke on Machine Learning and Security at DEFCON 24, PHDays, BSides Las Vegas and NYC, Code Blue, SecTor, and Hack in Paris (2015­2016). He had been a community speaker with Intel, and is also the founder and organizer of the ‘Data Mining for Cyber Security’ meetup group, the largest gathering of security data scientists in the San Francisco Bay Area.

Credential Assessment: Mapping Privilege Escalation at Scale
------------------------------------------------------------
by Matt Weeks

In countless intrusions from large retail giants to oil companies, attackers have progressed from initial access to complete network compromise. In the aftermath, much ink is spilt and products are sold on how the attackers first obtained access and how the malware they used could or could not have been detected, while little attention is given to the credentials they found that turned their access on a single-system into thousands more. This process, while critical for offensive operations, is often complex, involving many links in the escalation chain composed of obtaining credentials on system A that grant access to system B and credentials later used on system B that grant further access, etc. We’ll show how to identify and combat such credential exposure at scale with the framework we developed. We comprehensively identify exposed credentials and automatically construct the compromise chains to identify maximal access and privileges gained, useful for either offensive or defensive purposes.

Bio: Matt Weeks
---------------

Matt Weeks currently leads root9B's research and development arm. As a researcher, he has uncovered a number of major vulnerabilities in various products. He also developed for the Metasploit framework, runs the site http://www.scriptjunkie.us/ and the southwest CCDC regional red team. Previously, he led the USAF's intrusion forensics and reverse engineering lab and the creation of their enterprise hunt teams.

BtleJuice: the Bluetooth Smart Man In The Middle Framework
----------------------------------------------------------
by Damien Cauquil


A lot of Bluetooth Low Energy capable devices are spread since the last few years, offering a brand new way to compromise many "smart" objects: fitness wristbands, smart locks and padlocks and even healthcare devices. But this protocol poses some new challenges: how may one easily intercept every communication between a device and an application ? How to easily spoof the behavior of a device to assess authentication ?

During months (years ?) we've been using Bluetooth Low Energy sniffers (like Ubertooth or even Adafruit's Bluefruit sniffer) to perform security assessments on many connected devices, with not so much success because of the erratic way BLE sniffers work. There were no easy way to perform a decent man-in-the-middle attack on BLE enabled devices. This is why we developed 'BtleJuice', a framework to fill in the gap and allow spying on communications between two BLE devices without SDR. We designed it to be modular and to allow MAC spoofing using a compatible Bluetooth LE adapter as data is relayed through network, that means both devices (the cloned and the real one) may be at different locations (or isolated) thus avoiding interference.

The ability to intercept every bit of data between two BLE enabled devices is an efficient way to passively determine a device's behavior and its attack surface and of course to find vulnerabilities. Reverse-engineering mobile applications is no more mandatory to retrieve samples of data to perform fuzzing or even understand how the device and its related components work. Furthermore, the ability to perform on-the-fly data modification gives an opportunity to create improved fuzzers and to detect more vulnerabilities.

We will demonstrate the efficiency of this framework on real devices, intercepting every piece of information and patching data on-the-fly, but also the impact in term of security.

Bio: Damien Cauquil
-------------------

Damien Cauquil is a senior security researcher at Digital Security (CERT-UBIK), a French security company focused on IoT and related ground breaking technologies. He spoke at various international security conferences including Chaos Communication Camp, Hack.lu, Hack In Paris and a dozen of times at the Nuit du Hack (one of the oldest French security conferences).

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

When Practice Informs Technology
--------------------------------
by Mahsa Alimardani

Digital rights activists and social change actors often operate in singular movements that seldom overlap, creating a disconnect between technology and practical needs. Non governmental organizations (NGOs) with insufficient knowledge of technology, or technological infrastructure may try to fill this void by allocating funding to attain the most up to date technologies or best practices, which may not be of relevance to local needs and contexts, ultimately proving ineffective. The latest technologies, best tech practices or rapid response expertise are often not only ineffective, but find themselves repeated within the same networks rather than expanding beyond immediate existing trust relationships between at risk Internet users and technologists. There is a need to bridge the relationship between the practices of change actors and the decisions of technologists to ensure that they inform the technologies and digital security guidelines given to them -not the other way. Deliberate efforts to connect technologist with civil society actors beyond their existing networks and foster new trust networks are therefore necessary. Emphasis will be given to three areas of focus: inclusion of marginalized groups such as women, youth and LGBT; privacy vs. publicity concerns; and UX/usability concerns to facilitate the building of networks, bring women and those marginalized into the technology discourse through an environment that fosters trust, and exchange tools, technologies and best practices.

Bio: Mahsa Alimardani
---------------------

Mahsa is the Iran editor for Global Voices as well as an Iranian-Canadian Internet researcher. Her focus is on the intersection of technology and human rights, especially as it pertains to freedom of expression and access to information with a focus on Iran. She holds a Honours Bachelor of Arts and Science in Political Science from the University of Toronto, and a Research Masters degree at the University of Amsterdam, finishing a her thesis on the technologies of social movements in Iran. She is also a researcher for the University of Amsterdam's DATACTIVE Research Collective.


An in-dept view into the iOS Kernel Vulnerabilities abused by PEGASUS
---------------------------------------------------------------------
by Stefan Esser

On 24th of August Citizenlab announced that they have caught an iOS surveillance malware called PEGASUS in the wild after it had been used against dissidents in the UAE. This was a very different form of iOS malware from everything previously caught in the wild, because it made use of 3 previously unknwon iOS  vulnerabilities. This exploit chain has been named TRIDENT. Unfortunately up to this day none of the involved parties has provided any technical details about the vulnerabilities involved or shared the caught malware samples with independent researchers that could provide an analysis to the public.

In this session we will take a look into how it was possible to close this information gap by analysing the iOS update provided by Apple and what previously hidden details about the vulnerabilities were discovered. We will detail how these vulnerabilities can be exploited to achieve arbitrary kernel code execution. However we will only look at the kernel side of things and leave the MobileSafari vulnerability to another team of researchers.


Bio: Stefan Esser
-----------------

Stefan Esser is best known in the security community as the PHP security guy. Since he became a PHP core developer in 2002 he devoted a lot of time to PHP and PHP application vulnerability research. However in his early days he released lots of advisories about vulnerabilities in software like CVS, Samba, OpenBSD or Internet Explorer. In 2003 he was the first to boot Linux directly from the hard disk of an unmodified XBOX through a buffer overflow in the XBOX font loader. In 2004 he founded the Hardened-PHP Project to develop a more secure version of PHP, known as Hardened-PHP, which evolved into the Suhosin PHP Security System in 2006. Since 2007 he works as head of research and development for the German web application company SektionEins GmbH that he co-founded. In 2010 he did his own ASLR implementation for Apple's iOS and shifted his focus to the security of the iOS kernel and iPhones in general. Since then he has spoken about the topic of iOS security at various information security conferences around the globe. In 2012 he co-authored the book the iOS Hackers Handbook.

Fraud detection and forensics on telco networks
-----------------------------------------------
by Vladimir Kropotov and Dmitry Kurbatov

Telecom networks have always been targets for those looking to obtain services for free or at the expense of other subscribers. In this presentation, we will describe new fraud techniques and attacks that use SS7 vulnerabilities affecting Telecom networks and related services. We will demonstrate how integration of payment systems with communication services can jeopardize the bank accounts of ordinary subscribers and make it easier for criminals to monetize attacks. Our demo will include transfer of money from electronic accounts.

Bio: Vladimir Kropotov
----------------------

Head of CSIRT, Positive Technologies
Vladimir was born in 1980. He holds a university degree in applied mathematics and information security.
Active for over 15 years in information security projects and research, he previously built and led incident response teams at some of Fortune 500 companies. Vladimir joined Positive Technologies in 2014 and currently performs research for automating detection and prevention of infrastructure attacks as well as heads the Computer Security Incident Response Team (CSIRT). He participates in various projects for leading financial, industrial, and telecom companies.
Vladimir regularly appears at high-profile international conferences such as FIRST, CARO, HITB, Hack.lu, PHDays, ZeroNights, POC, Hitcon, and many others.


Bio: Dmitry Kurbatov
--------------------

Head of telecom security department, Positive Technologies
Dmitry Kurbatov was born in Moscow in 1986. He holds a university degree in information security of telecommunications systems.
Dmitry joined Positive Technologies in 2010 as an information security expert and now he specializes on telecom and mobile networks security. He is responsible for the product development (SS7 Attack Discovery and SS7 Security Scanner) as well as for services in audit of telecom and mobile networks security systems. His team revealed vulnerable points in popular two factor authentication schemes using texts and demonstrated how easy it is to compomise Facebook, WhatsApp and Telegram accounts.

The Legend of Windows: A Link to the Hash
-----------------------------------------
by m4xk and sıx

During one of our IT security investigation we have observed an undocumented Windows feature which leaks much valued hashes from the system. No complicated exploitation is needed to play the trick we will present and it can drastically speed up owning all the users in the systems and reaching to domain administration privileges.

Bio: m4xk
---------

m4xk is working in the field of IT Security for several years and always curious about how IT systems work underneath. He grew a passion for reverse engineering software and hardware. He is deeply interested in breaking and exploiting computers after learning how they work. m4xk holds several international certifications like OSCP.

Bio: sıx
--------

sıx is passionate about bad software and exploiting it's flaws. He is working as an IT Security Specialist for years now and previously as an administrator for Windows, Linux and Unix systems in order to learn how they work in practice. sıx holds several international certifications like OSCP.


Of Mice and Keyboards: On the Security of Modern Wireless Desktop Sets
----------------------------------------------------------------------

Wireless desktop sets consisting of a wireless mouse, a wireless keyboard, and a USB dongle have become more popular and more widespread in the last couple of years. Seen as potential target, those radio-based devices are of more interest to people with malicious intentions than their wired counterparts, due to the fact that they can also be attacked remotely from a safe distance via radio signals.

As wireless desktop sets represent an attractive target both allowing to take control of a computer system and to gain knowledge of sensitive data like passwords, they have been frequently analyzed for security vulnerabilities and were successfully attacked in the past.

SySS GmbH started a research project about the security of modern wireless desktop sets using AES encryption in 2015, as there was no publicly available data concerning security issues in current wireless mice and keyboards. Up to now, several security vulnerabilities in modern wireless desktop sets of different manufacturers like Microsoft, Cherry, Logitech, Fujitsu and Perixx have been found and reported in the course of our responsible disclosure program.

In our talk, we will present the results of this research and will demonstrate ways in which modern wireless desktop sets of several manufacturers can be attacked by practically exploiting different security vulnerabilities.


Bio: Matthias Deeg
------------------

Matthias Deeg is interested in information technology - especially IT security - since his early days and has a great interest in seeing whether security assumptions in soft-, firm- or hardware hold true when taking a closer look. Matthias successfully studied computer science at the university of Ulm and holds the following IT security certifications: CISSP, CISA, OSCP, OSCE.

Since 2007 he works as IT security consultant for the IT security company SySS GmbH and is also head of R&D.

Matthias was speaker at the Chaos Communication Congress in 2009 and 2010 (lightning talks and a workshop), at the BSidesVienna security conference in 2014 and 2015 (talks) and at the DeepSec security conference in 2015 (talk). In the last years, he also published several IT security papers and security advisories.


Bio: Gerhard Klostermeier
-------------------------

Gerhard Klostermeier is interested in all things concerning IT security - especially when it comes to hardware or radio protocols. He successfully studied IT security at Aalen University and is working at SySS GmbH since 2014 as IT security consultant and penetration tester.

Gerhard was speaker at GPN 2013 - a conference organized by the Chaos Computer Club (CCC) in Karlsruhe - where he talked about hacking RFID-based student cards. He is also author of the Mifare Classic Tool Android app.


Workshops
=========

Android malware reverse engineering
-----------------------------------
by Axelle Apvrille

This workshop explains how to reverse engineer Android malware.
After some brief explanation, attendees will be provided with a few recent samples such as Android/SpyBanker (May 2016), Android/Xiny (May 2016) or Riskware/InnerSnail (June 2016). They will learn how to reverse those, step by step.

The course will be split in two parts. The first part covers the "basics" - which are sufficient to handle most samples. The second part dives into more advanced consideration such as dealing with obfuscated or packed samples.

Attendees bring their own laptop + install VirtualBox, or docker.


Bio: Axelle Apvrille
--------------------

Axelle Apvrille (@cryptax) is a happy senior researcher at Fortinet. Her research focuses on any strange virus on so-called 'smart' devices, ranging from smartphones to IoT.

She enjoys CTFs, especially at Hack.Lu, among the pic0wn team, though her best achievements are at drawing comic strips about it (http://picolecroco.free.fr/sstic/index.html).


Malware Triage IOCs - Using Open Data to Help Develop Robust Indicators
-----------------------------------------------------------------------
by Sergei Frankoff and Sean Wilson

Whether you are in the enterprise using malware triage as a gate to your incident response process, or a researcher using triage as a way to identify interesting malware samples, Indicators of Compromise (IOCs) will serve as the feedback loop in your triage process.

As a malware sample makes its way through your triage process the output should be an IOC. Not only will the IOC be used as part of your malware hunting process but it can also be used in future triage to avoid re-analyzing similar samples. The key to an efficient triage process is robust IOCs, the more robust your IOC the more variations of malware it will cover and the less time you will have to spend on re-analyzing similar samples.

We present an iterative approach to building robust malware indicators; first developing primary indicators, then mining open data for related malware samples, using the collection of similar samples to build robust IOCs, and finally testing the IOCs for effectiveness. We will cover multiple free tools that can assist with the use of primary indicators as pivots to mine open data repositories, as well as test the effectiveness of your IOCs. During the presentation we will use real malware samples with demonstrations to walk through each step in the process.

This is not a workshop about IOC formats, it is about the process used to build an IOC. We briefly cover the basics for Yara and OpenIOC but any format can be used with the process we teach.

Key takeaways include;

- familiarization with the use of IOCs in the malware triage process
- a standardized process for developing robust IOCs
- exposure to a quiver of free tools useful for indicator pivot searching
- how to test IOC effectiveness with unknown samples

Equipment you need;

- You must have a computer (preferably a VM) that you are comfortable analyzing malware with, if it is a work computer please check with your IT staff.
- You must have Administrator/Root privileges and the ability to install software on your computer.
- You must have the ability to disable any anti-virus software on your computer.

This workshop is aimed at incident responders and malware analysts who have a basic understanding of malware and the malware triage process. However this is not an advanced course and deep knowledge of reverse engineering and malware analysis is NOT required.

Bio: Sergei Frankoff
--------------------
Twitter: @herrcore

Sergei Frankoff is a malware researcher and Director of Threat Intelligence at Sentrant. Prior to joining Sentrant Sergei worked as an incident responder and a security analyst. Sergei is a strong believer in taking an open, community approach to combating cyber crime. He actively contributes to open source tools and tries to publish as much as possible. Sergei is also a co-founder of Open Analysis, a collective of malware researchers and incident responders who produce open tools and services to assist with malware analysis.


Bio: Sean Wilson
----------------
Twitter: @seanmw

Sean is a researcher at PhishMe with experience in malware analysis, incident response and reverse engineering. He is an active contributor to open source security tools focused on incident response and analysis. Prior to PhishMe, Sean worked in a number of incident response and application security roles with a focus on security testing and threat modelling. Sean is also a co-founder of Open Analysis, a collective of malware researchers and incident responders who produce open tools and services to assist with malware analysis. In his free time Sean loves fly fishing.


Introduction to Security Onion
------------------------------
by David Szili

Security Onion is a Linux distribution based on Ubuntu, designed for security analysts. It contains many security tools such as Snort, Suricata, Bro, OSSEC, Sguil, Squert, ELSA, NetworkMiner, etc. to create a platform for network security monitoring. The unique combination of features and concepts like pivoting from one tool to another one, having different network security monitoring data types (like full packet capture) and the capability to form a distributed sensor architecture make Security Onion one of the most powerful solutions which often outperforms many of the commercial products.

The goal of this introductory workshop is to familiarize the participants with Security Onion, guide them through the first steps of setting it up and start analyzing traffic. The first part of the workshop will be about installing and configuring Security Onion in a Virtual Machine. The next section will be a quick walk-through to the primary interfaces (Squert, Sguil, ELSA), the different NSM data types and pivoting between interfaces and data types. At the end of the workshop, we will take a look at a few exercises and real life case studies, replay traffic and perform analysis using the tools and data types available in Security Onion.

Requirements for the workshop:
- A laptop with at least 8 GB of RAM and more than 20 GB of free disk space (VT-x support must be enabled on the host system).
- Application to run Virtual Images (type-2 hypervisor), such as VMWare Workstation (recommended), VMWare Player, VirtualBox or similar software.

Attendees should download the latest Security Onion image in advance from [GitHub](https://github.com/Security-Onion-Solutions/security-onion/blob/master/Verify_ISO.md).

Bio: David Szili
----------------

David Szili is a freelancer IT Security Consultant with penetration testing, security monitoring, incident response and forensics background, previously working for companies like POST Telecom PSF, Dimension Data and Deloitte.

David has two Master's degrees in Computer Engineering and in Networks and Telecommunication and a Bachelor's degree in Electrical Engineering. He also holds several IT security certifications such as GSEC, GCIA, GCIH, GMON, GMOB, OSCP, OSWP and CEH.

In his spare time, David likes working on hobby electronics projects, develop new IT security tools or sharpen his skills with CTFs and bug bounty programs.

ARM Shellcode Basics
--------------------
by Saumil Shah

A 2 hour workshop on writing ARM Shellcode from scratch. I will cover some simple ARM assembly, and then we will work on two shellcode examples. A simple execve() shell and a fully working Reverse Shell. We will then test this with two ARM exploits. Attendees are required to bring in their laptops with a working copy of VMWare (Player/Workstation/Fusion). ARM images running on QEMU will be distributed to the participants.

Bio: Saumil Shah
----------------

Saumil Shah is the founder and CEO of Net-Square, providing cutting edge information security services to clients worldwide. Saumil is an internationally recognized conference speaker and instructor for over 15 years. He is also the co-developer of the wildly successful "Exploit Laboratory" courses and authored two books titled "Web Hacking: Attacks and Defense" and "The Anti-Virus Book".

Saumil holds an M.S. in Computer Science from Purdue University, USA and a B.E. in Computer Engineering from Gujarat University. He spends his leisure time playing Pacman, flying kites, traveling around the world and taking pictures.


FastIR Collector
----------------
by Sébastien Larinier

The goal of the wokshop is to present and use the open source [live forensic collector FastIR](https://github.com/SekoiaLab/Fastir_Collector) on differents cases investigations on Windows: RAT with tricks anti forensics, rootkits, Trojan with dll injections… And we’ll present new features we have developped this year with agent and server.

Bio: Sébastien Larinier
-----------------------

Sébastien Larinier (@sebdraven) currently is Senior Researcher and Incident Handler at the CERT Sekoia located in Paris, member of the honeyproject chapter France and co organizer of botconf. Sébastien focused his work  on botnet hunting, malware analysis, network forensics, early compromission detection, forensic and incident response. Python addict he supports different opensource projects like FastIR, Oletools, pymisp, malcom...,

Advanced Exploitation: ROP and protections bypass under Linux
-------------------------------------------------------------
by Julien Bachmann

This workshop’s goal is to give trainees an understanding of the exploitation technique known as Return Oriented Programming, or ROP, through both explanations and gradually complex exercises. The labs will be performed on Linux and binaries will be 32 bits.
After a brief recap on buffer overflows the workshop goes on to explain protection built-into the compiler and the OS (canaries, NX, ...). Introduction to ROP is done by starting with ret2libc exploitation which is a specialization of the ROP technique.
ROP concepts such as gadgets, ROP chains, primitives are detailed. Tools such as ropgadget and rp++ are presented and a detailed ROP chain is then studied.
The workshop then continues with a live example before entering the lab part. Example of lab manual (this one was given in a university) can be found in annex but subject to change in order to match timeframe.

Bio: Julien Bachmann
--------------------

After several years performing penetration tests, to break into information systems and assess the security of web and mobile applications, Julien joined the defence side for an MSSP. This background allows him to have a different view on how to protect enterprises and their critical assets. His current role could be could be resumed as a "full stack security architect: from assembly to Gartner reports and beyond”.
Julien is also a guest lecturer at Swiss engineering schools on software exploitation techniques, as well as on incident response and malware analysis.

HIDden secrets in Soft Token: A security study of HID Global Soft Token
-----------------------------------------------------------------------
by Mouad Abouhali (@_m00dy_)

Nowadays, many companies tend to deploy two factors authentication means to remotely access their infrastructure. Lately, the use of Soft Token
applications instead of Hardware tokens seduces more and more, especially in regards to financial aspects (deployment and maintenance costs).
In This current talk I will present a security study of the Android version of HID Soft Token application (HID Global). This study covers the
mechanisms that are used by the application to protect the main functional processing as generating encryptions keys, OTP keys, etc. Besides, the study
lays the groundwork for shedding light on two vulnerabilities that affect the application.

Indeed, the cryptographic operations that are implemented by the application suffer from a certain weaknesses that allow an attacker (under certain circumstances) to retrieve the main resources of an enrolled HID Soft Token application that belongs to a legitimate user, clone its configuration and particularly discover the victim’s PIN by the means of a brute force attack.

Bio: Mouad Abouhali
-------------------

Mouad Abouhali is a security researcher currently working in Airbus Group Innovations.


The Fantastic 4 ... forensic domains: net, disk, mem, mal
---------------------------------------------------------
by David Durvaux, Christophe Vandeplas

Forensic analysis (network, disk, memory, malware) is one of the core tasks of the incident handling activity. Where many analysts stop the investigation once they have identified the malware sample and write a report saying 'the attacker had full control...'; for us the fun only starts and we go further to find the juicy stuff that really matters.

With our favorite open source tools (plaso, volatility, rekall, cuckoo, …) we will perform network, disk, memory and malware analysis of the forensic evidence (Windows 10) created for the Locked Shields Cyber Exercise by the CCDCOE. The goal is to introduce you to some nice features of our modern toolset, while also taking a moment of silence in respect of old deprecated tools like log2timeline.pl that are still actively used today. 

Even more importantly we will not look into those 4 domains (network, disk, memory, malware) separately, as is done way too often, but will show you the immense value of putting all this information together allowing us to find the really juicy traces that were left on the system and would never be found.  


Bio: David Durvaux 
------------------

David Durvaux learned to do forensic when he was at CERT.be.  Since then he continues to break things for the European Commission and other customers when the opportunity is given.


Bio: Christophe Vandeplas 
-------------------------

Christophe Vandeplas enjoys forensic and malware analysis in NCIRC, the NATO Incident Response Center. Before he had fun at the Belgian Defence CERT where he helped built the CERT capability. His main contributions to the community were the creation of MISP, pystemon and the organisation of the FOSDEM conference for many years.
