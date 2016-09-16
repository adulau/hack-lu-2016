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
