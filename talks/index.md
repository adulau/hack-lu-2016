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
