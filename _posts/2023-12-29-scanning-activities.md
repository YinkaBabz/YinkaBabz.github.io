---
layout: post
title: Scanning Activities
subtitle: Perform a scan and vulnerability assesments.
categories: Cyber Security
tags: [Cyber Security, practicals, ethical hacking]
---

## Learning Outcomes
- Identify and analyse security threats and vulnerabilities in network systems and
determine appropriate methodologies, tools and techniques to manage and/or solve
them.
- Design and critically appraise computer programs and systems to produce solutions
that help manage and audit risk and security issues.
- Gather and synthesise information from multiple sources (including internet security
alerts and warning sites) to aid in the systematic analysis of security breaches and
issues.

## osattack2 program
  The whois program is used to grab information from the regional internet registry(RIR). It is used to find out who owns the IP address

  ![whois](/assets/images/banners/whois.jpeg)

  Note that when the wrong IP address is entered we don't get any results.

## ping

  ![ping](/assets/images/banners/ping.jpeg)

## Vulnerability scanning using Nessus

  Nessus is a vulnerability scanning tool widely used for its graphical user interface mode.

  ![Nessus](/assets/images/banners/Nessus.jpeg)

  After scanning the host we can observe the vulnerabilities and also their risk levels.

## Vulnerability sanning using OpenVAS

  OpenVAS is a software framework of several services and tools offering vulnerability scanning and management. The *gvm-start* command is used to perform an automated scan.
  This method of scanning has more steps than the previous and is more comprehensive.

  ![5.3.2](/assets/images/banners/5.3.2.jpeg)
  ![5.3.22](/assets/images/banners/5.3.22.jpeg)

## How to crack windows password

  *Ophcrack* is a free windows password cracker based on rainbow tables.
  *Rainbow tables* are the stored pre-computed hashes.

  ![7.4.2](/assets/images/banners/7.4.2.jpeg)

  With this hack we are able to successfully see the usernames and passwords that have been stored on the system.

## Scan malware using antivirus

  An antivirus is a computer program that is used to prevent, detect and remove any malware.

  ![8.5.1](/assets/images/banners/8.5.1.jpeg)
  ![8.5.11](/assets/images/banners/8.5.11.jpeg)

## Capture packets using Wireshark

  *Wireshark* is a free and open-source packet analyzer. It can be used to identify unwanted traffic or detect malicious activities. It is also used for network troubleshooting, analysis, software and communications protocol development.

  ![wireshark](/assets/images/banners/wireshark.jpeg)

## ARP spoofing

  *Address Resolution Protcol(ARP)* is a stateless protocol for resolving IP addresses to machine MAC addresses. In ARP spoofing, ARP packets are can be forged to send data to the system also known as ARP poisoning. The hacker places themselves between the client and the server and thereby has access to all the traffic betwwen the two.

  ![9.4.1](/assets/images/banners/9.4.1.jpeg)
  ![9.4.11](/assets/images/banners/9.4.11.jpeg)

## Detecting a phising site using Netcraft

  *Phising* is a technique used to acquire information through deception using electronic communications.
  *Netcraft* provides internet security services for a large number of cases including cybercrime detection and disruption, application testing and PCI scanning.

  ![netcraft1](/assets/images/banners/netcraft1.jpeg)
  ![netcraft2](/assets/images/banners/netcraft2.jpeg)

## How to secure a Wi-Fi hotspot

  ![11.1.2](/assets/images/banners/11.1.2.jpeg)

## SQL injection

  SQL injection can exploit the backend database of the website, which mostly occurs due to web developer's mistakes.

  ![12.1.1](/assets/images/banners/12.1.1.jpeg)

  DVWA is the application used. This application practices some of the most common web vulnerabilities with various level of difficulty and a simple straight-forward interface.

## XSS injection

  XSS injection is a malicious content sent to the web browser. These contents are often a segment of Javascript, HTML, Flash or any other code that the browser may execute.

  ![12.1.2](/assets/images/banners/12.1.2.jpeg)

  Also uses the DVWA aapplication.

## DoS attack

  A DoS(Denial-of-Service) attack is a cyber-attack in which the perpetrator seeks to make a machine or network resource unavailable to its intended users by temporarily or indefinitely disrupting the services of a host connected to the internet.

  ![DoSattack](/assets/images/banners/DoSattack1.jpeg)
  ![Dosattack2](/assets/images/banners/Dosattack2.jpeg)

  Wireshark is used.

## Buffer overflow attack

  Buffer overflow attacks make use of various vulnerabilities in the stack. These attacks take malicious user input, put it onto the stack and affect the local variables that are stored on the stack.

  ![12.3.1](/assets/images/banners/12.3.1.jpeg)

  *PuTTY* is a SSH and Telnet client and a free implementation of SSH and Telnet for windows and unix platforms, along with an xterm terminal emulator. PuTTY is used to defend against a buffer overflow attack.

## Honeypot

  A honeypot is a computer system that is set up to trap cyber attackers who try to gain unauthorized access to information systems.

  ![honeypot1](/assets/images/banners/honeypot1.jpeg)
  ![honeypot2](/assets/images/banners/honeypot2.jpeg)
  ![honeypot3](/assets/images/banners/honeypot3.jpeg)

## Burp Suite

  Burp Suite is an integrated platform and graphical tool for performing security testing of web applications, it supports the entire testing process from initial mapping and analysis of an application's attack surface to finding and exploting security vulnerabilities.

  ![BurpSuite](/assets/images/banners/BurpSuite.jpeg)

  *Session hijacking* is the exploitation of the various web session control mechanism, which is normally used to manage a session's token. We can perform a session hijacking using Burp Suite.
  
