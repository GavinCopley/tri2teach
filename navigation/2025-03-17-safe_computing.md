---
layout: post
title: Safe Computing
description: Safe computing from Collegeboard's AP CSP curriculum
type: issues 
courses: { csp: {week: 9} }
comments: true
permalink: /csp/teach/safe_computing/all
---

# Key Topic - IOC-2.C
Explain how unauthorized access to computing resources is gained.

## Phishing - IOC-2.C.1
Phishing is a technique that attempts to trick a user into providing personal information. That personal information can then be used to access sensitive online resources, such as bank accounts and emails.

- A lot of you have seen phishing before
- Common examples are email phishing or mobile phishing
- Below is a real example of mobile phishing that Jacob received
- Prevention: Don't click on links from people you don't know or don't trust

![mobile]({{site.baseurl}}/images/mobile_phishing.png)

## Keylogging - IOC-2.C.2
Keylogging is the use of a program to record every keystroke made by a computer user in order to gain fraudulent access to passwords and other confidential information.

- Keylogging does have a few benefits: parental controls or employee monitoring in a business setting
- Other than that, keylogging almost always happens when you install malware
- An application will record your keystrokes
- If you type in a password and username, it would be logged
- Prevention: Don't install untrusted software or apps

## Data Interception - IOC-2.C.3
Data sent over public networks can be intercepted, analyzed, and modified. One way that this can happen is through a rogue access point.

- Examples of this can be seen when people set-up fake wifi networks and capture all data being transferred to it or DNS spoofing, which is when an attacker sends you to a unintended IP address after they hijack a DNS server.
- Prevention: Connect to secure networks and verify the address of websites you connect to are legitimate.

## Rogue Access Point - IOC-2.C.4
A rogue access point is a wireless access point that gives unauthorized access to secure networks.

- This is part of data interception.
- It is when a access point is installed on a network without owner knowledge or permission.
- Passive interception: a rogue access point can read your data but not able to manipulate it
- Active interception: a rogue access point can read and manipulate your data.
- Prevention: Connect to trusted networks and only send information via websites with S (HypertHTTPext Transfer Protocol Secure), to ensure data is encrypted

## Malicious Links - IOC-2.C.5
A malicious link can be disguised on a web page or in an email message. 

- These are links that send you to illegitimate websites or links that send you to a malware download.
- Seen in many places; websites, ads, emails, texts, etc.
- Prevention: Don't click links that you don't know.

## Malicious Emails - IOC-2.C.6
Unsolicited emails, attachments, links, and forms in emails can be used to compromise the security of a computing system. These can come from unknown senders or from known senders whose security has been compromised. 

- These emails can contain scams or malicious downloads/attachments.
- After downloading an these attachments, most of them send malicious emails from your account to other people you know
   - Therefore, these emails can come from people you know
- Prevention: Don't download files or click random links from emails. If you have to, make sure its someone you know and can verify if it was actually them.

## Freeware - IOC-2.C.7
Untrustworthy (often free) downloads from freeware or shareware sites can contain malware.

- Freeware is software that is free to install. Shareware is software where you get a free trial and are asked to pay later.
- Freeware and shareware aren't always malware, but a lot is
- Prevention: Don't download software for free, especially if there is a popular paid version. If you have to, make sure it's from a trusted site that you know and can verify has no malware.

## Real Life Example
You connect to an unsecure free wifi at a coffee shop. You send private information on an unsecure http website (NOT https). What you don't know is that someone set up a rogue access point in the shop. They named their fake wifi "WiFi Coffee Shop Free" while the real WiFi was "Free Coffee Shop WiFi." They can read and even manipulate the packets you send via the network before they relay it to the real network. Or they can send you to a different website than the one you intended to go to, possibly injecting malware or stealing info.

## Popcorn Hack
Go to [this website](https://www.security.org/how-secure-is-my-password/) and make a secure password. <br>
Remember: secure passwords have capitalized letters, numbers, and special characters