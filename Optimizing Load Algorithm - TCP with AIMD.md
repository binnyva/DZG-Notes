---
title: "Optimizing Load Algorithm - TCP with AIMD"
tags: ["permanent-notes", "algorithm","problem-solving" ]
date: 2022-05-20 01:46:00
source: "https://www.youtube.com/watch?v=2VCPmabnBdo"
---

To find the ideal load for a system, double the load in each iteration. Once the system fails, half the last load and increase load by one for each iteration. The load before the next failure is the ideal load.

This is the method used by TCP(in computer networks) to decide how many packets to send. First the system sends 1 packet and wait for a response. If it gets an acknowledgment, it sends 2. If that's also acknowledged, it doubles it to 4. Then 8, 16, 32 - until there is no acknowledgment. Once failure happens, it sends the half of last transmission(in our example, that would be 16). Then increases the number by one for each iteration. 16, 17, 18 ... until another failure. Then the previous number is used - that's the ideal load.

You can use this for other areas where ideal load has to be found as well. Eg. how much workload can a new member of the team handle. 

