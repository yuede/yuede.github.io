---
layout: archive
title: "Projects"
permalink: /projects/
author_profile: true
---

Program Vulnerability Detection
===============================
The computing devices, e.g., IoT devices and smartphones, are growing rapidly to reach tens of billions in scale. As the running operating systems and software are far from flawless, the vulnerabilities existent in them inevitably enable unknown attack vectors. More seriously, as libraries and code segments are often heavily reused in the software development phase, a vulnerability found in one commonly used code repository could be harnessed to compromise a large number of computing devices that are dependent on it. Therefore, identifying the vulnerabilities hidden in the devices becomes a top priority task.

This project aims to greatly improve the security of the computing devices by
(1) investigating the potential attack surfaces that can cause serious damage;
(2) enhancing the fundamental techniques used in existing vulnerability detection methods.
So far, we have identified over 200 vulnerabilities from both mobile and IoT firmware. Several vendors have confirmed our findings.

<span style="color:blue">Publications</span>: DEFInit [under submission], [[BugGraph [AsiaCCS'21]]](../files/21_AsiaCCS_BugGraph.pdf), [[Vestige [ACNS'21]]](../files/21_ACNS_Vestige.pdf)

Cyber Threat Detection
========================
What makes cyber attack a relentless challenging problem is its continuing and evolving nature. Whenever a type of cyber attack is taken down, the attackers would evolve it by either designing new techniques or devising a completely new attack type. For example, a major component of botnet is building the hidden command and control channel. Traditionally, they were using telnet, Internet relay chat, peer-to-peer, and domains. Now they have evolved to use social network and Tor hidden services. Thus, it is critical to design defense techniques that can keep pace with the evolution of attack vectors.

This project aims to detect various types of cyber threats, including APT, botnet, malicious URL, and malware in general.

<span style="color:blue">Publications</span>: [[APT detection [RAID'20]]](../files/20_RAID_lateral_movement.pdf); [[Malware Detection [ICCC'19]]](../files/19_ICCC_malware_adversary.pdf); Botnet Detection [[[ICPADS'14]]](../files/14_ICPADS_social_botnet.pdf), [[[ISPEC'14]]](../files/14_ISPEC_multiprocess_botnet.pdf); [[Malicious URL Detection [NPC'14]]](../files/14_NPC_malicious_url.pdf)


High-Performance Computing for Graph analytics
==============================================

Graph is an important data representation used in many applications, such as control and data flow graph in program analysis, friendship graph in the social network, and authentication graph in APT campaigns. There are two major challenges for computing on graphs. First, Graph, in reality, is big data in terms of both graph size and count. The graph size in many real applications, e.g., social network, has reached billion scale. Second, many interesting graph algorithms have high time complexity, e.g., subgraph isomorphism is NP-complete. As real applications usually require real-time computation, it is critical to improve the scalability of graph analytics.

This project aims to design scalable graph analytics techniques and systems to both speed up the computation and scale up the accommodated graph size and count. A recent focus is on <strong> graph neural network (GNN)</strong> as it is being widely applied and requires more computation resources.

---------------------------------
<span style="color:blue">Publications</span>: [[Aquila [HPDC'20]]](../files/20_HPDC_Aquila.pdf), [[SwarmGraph [HPCC'20]]](../files/20_HPCC_SwarmGraph.pdf), [[iSpan [SC'18]]](../files/18_SC_iSpan.pdf)
