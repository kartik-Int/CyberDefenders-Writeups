---
description: >-
  Investigate network traffic with Wireshark to identify attacker TTPs, extract
  XSS payloads and session tokens, and determine exploited web application
  vulnerabilities.
---

# RetailBreach Lab

**Scenario**

In recent days, ShopSphere, a prominent online retail platform, has experienced unusual administrative login activity during late-night hours. These logins coincide with an influx of customer complaints about unexplained account anomalies, raising concerns about a potential security breach. Initial observations suggest unauthorized access to administrative accounts, potentially indicating deeper system compromise.

Your mission is to investigate the captured network traffic to determine the nature and source of the breach. Identifying how the attackers infiltrated the system and pinpointing their methods will be critical to understanding the attack's scope and mitigating its impact.



Q1. Identifying an attacker's IP address is crucial for mapping the attack's extent and planning an effective response. What is the attacker's IP address?

<figure><img src=".gitbook/assets/image (11).png" alt=""><figcaption></figcaption></figure>



The attacker used a directory brute-forcing tool to discover hidden paths. Which tool did the attacker use to perform the brute-forcing?

<figure><img src=".gitbook/assets/image (12).png" alt=""><figcaption></figcaption></figure>

Solved : 1320

Cross-Site Scripting (XSS) allows attackers to inject malicious scripts into web pages viewed by users. Can you specify the XSS payload that the attacker used to compromise the integrity of the web application?

<figure><img src=".gitbook/assets/image (13).png" alt=""><figcaption></figcaption></figure>

Pinpointing the exact moment an admin user encounters the injected malicious script is crucial for understanding the timeline of a security breach. Can you provide the UTC timestamp when the admin user first visited the page containing the injected malicious script?

<figure><img src=".gitbook/assets/image (14).png" alt=""><figcaption></figcaption></figure>

The theft of a session token through XSS is a serious security breach that allows unauthorized access. Can you provide the session token that the attacker acquired and used for this unauthorized access?

<figure><img src=".gitbook/assets/image (15).png" alt=""><figcaption></figcaption></figure>

Identifying which scripts have been exploited is crucial for mitigating vulnerabilities in a web application. What is the name of the script that was exploited by the attacker?

<figure><img src=".gitbook/assets/image (16).png" alt=""><figcaption></figcaption></figure>



<figure><img src=".gitbook/assets/image (17).png" alt=""><figcaption></figcaption></figure>



Exploiting vulnerabilities to access sensitive system files is a common tactic used by attackers. Can you identify the specific payload the attacker used to access a sensitive system file?

<figure><img src=".gitbook/assets/image (18).png" alt=""><figcaption></figcaption></figure>
