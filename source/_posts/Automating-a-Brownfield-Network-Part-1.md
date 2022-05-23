---
title: Automating a Brownfield Network - Part 1
date: 2022-05-22 20:44:05
tags:
  - automation
  - ansible
---
Welcome to the first of this mutliple part series which will cover different aspects of automating a brownfield network. Lets start by discussing the why and if this is a road you would like to go down.

### What is a brownfield network and why would I want to introduce automation?
Thats a great question.

### What this series will aim to acheive
As we go along in this series we will look at different aspects of automation and how it can be used in our network, regardless of network type and vendors.

We first need to ask what benefit will automation provide in our existing network? Will it make me fast at my job? Maybe get me the girls? Who knows.

### Benefits of automation in a network
* Configuration consistency
* Each change is tested and proven non-impacting
* Accurate source of truth
* Faster time to deployment
* Reduction of human error

### Devices we will use
The following devices are common in todays netorks and are easy to emulate in a virtual enviroment such as eve-ng:
* Cisco
    * NX-OS
    * vIOS
* Juniper
    * vSRX-NG
* Fortinet
    * Fortigate

{% asset_img 32766_1.jpg %}

### What this tutorial assumes
* You have used ansible, even if just to output a show command on a network device
* You have a lab or somewhere you can safely test your playbooks, never test on the live production network!
* You are familular with basic networking protocols

### Final thought
There are so many tools available when starting to automate that it can quickly become overwhelming, how do we know we are using the right tool the right way??
Do not worry, lets start small and simple and then keep building from that.

<div id="disqus_thread"></div>