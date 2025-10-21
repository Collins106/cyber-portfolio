---
layout: default
modal-id: 2
title: Incident Report
img: incident.png
alt: image-alt

# Reminder: Update this link with your own project link
project-url: https://drive.google.com/drive/u/0/folders/1COo427HaoECWvMyGBqyN680av-apMz0j

description: Identified DDoS attack, scope of incident, potential network vulnerabilities and protection measures, and properly documented analysis and recovery plans in order to restore normal operations and maintain alignment with NIST CSF best practices.
---

🧩 Cybersecurity Projects Overview

These projects represent my journey as a cybersecurity analyst — applying everything I’ve learned about network security, incident response, and system hardening.
Each one gave me hands-on experience in analyzing real-world attacks, capturing live traffic with tools like **Wireshark** and **tcpdump**, and documenting security incidents using frameworks like **NIST CSF**.
Together, they show how I approach a problem: **analyze, respond, secure, and prevent.**

---

🔐 Brute Force Attack and Website Compromise

This project was about investigating how a former employee carried out a brute force attack on a company website.
They guessed the admin’s default password and added malicious JavaScript that redirected visitors to a fake site with malware.
I analyzed the **network traffic**, identified the **DNS and HTTP behavior**, and documented the attack chain.
To prevent future incidents, I recommended **two-factor authentication (2FA)**, stronger password policies, and a **web application firewall (WAF)**.
It taught me how dangerous weak credentials can be — and how to document, fix, and secure web infrastructures properly.

---

💻 SYN Flood Denial of Service (DoS) Attack

Here I analyzed a **SYN Flood** attack that took down a company’s website by overwhelming it with TCP handshake requests.
Using **packet analysis**, I was able to explain exactly how the attack worked and what caused the system to crash.
My solution included enabling **SYN cookies**, **rate limiting**, and deploying an **IDS/IPS system** to detect suspicious traffic before it becomes a problem.
This project helped me understand how important it is to balance detection and prevention when dealing with denial-of-service attacks.

---

🌐 Network Protocol Analysis – DNS Port Unreachable

This one was more on the troubleshooting side. The company website kept returning a “destination port unreachable” error, so I used **tcpdump** to trace the issue.
I discovered that the problem was with **UDP port 53**, meaning DNS traffic was being blocked at the firewall.
After digging into the packets, I proposed firewall rule changes and tested DNS resolution again to confirm the fix.
It reinforced how understanding network protocols — especially **UDP, ICMP, and DNS** — is key to finding and fixing connection issues quickly.

---

🧱 Network Hardening Risk Assessment

This project focused on assessing a **data breach** at a social media company that exposed user information.
After reviewing their setup, I found the biggest issues were password sharing, a default admin password, and lack of firewall rules or MFA.
I built a **risk assessment plan** and suggested network hardening strategies — things like **firewall rule enforcement**, **strong password policies**, and **multifactor authentication**.
This one showed me how much difference small, consistent security habits can make in preventing future breaches.

---

🛡️ NIST CSF Incident Report – DDoS Attack

In this one, I applied the **NIST Cybersecurity Framework** to analyze a **DDoS attack** on a multimedia company’s internal network.
The attack used ICMP floods that took systems offline for two hours.
I documented how the attack happened, mapped it across the NIST CSF functions (**Identify, Protect, Detect, Respond, Recover**), and recommended improvements like **firewall ICMP rate-limiting**, **IP verification**, and **IDS/IPS deployment**.
This project helped me build a structured approach to incident response — not just reacting, but creating a clear, repeatable plan.

---

📄Final Report – Web Application Data Breach

This report covered an e-commerce data breach that exposed customer records because of a **forced browsing vulnerability**.
I analyzed the cause, assessed the impact, and recommended fixes like **URL allowlisting**, stronger access control, and regular **penetration testing**.
It helped me practice forensic thinking — connecting how a small misconfiguration can lead to a major data exposure.

---

🧠 What These Projects Show**

All together, these projects highlight my ability to:

* Analyze and interpret **network traffic** using **Wireshark** and **tcpdump**
* Document and respond to incidents using frameworks like **NIST CSF**
* Identify vulnerabilities and recommend **real-world mitigation steps**
* Communicate technical findings clearly through professional security reports
