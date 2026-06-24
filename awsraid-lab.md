---
description: >-
  Investigate AWS CloudTrail logs using Splunk to identify unauthorized access,
  analyze configuration changes, and detect persistence mechanisms.
---

# AWSRaid Lab

Category: [Cloud Forensics](https://cyberdefenders.org/blueteam-ctf-challenges/?categories=cloud-forensics)

Tactics: [Persistence](https://cyberdefenders.org/blueteam-ctf-challenges/?tactics=persistence), [Privilege Escalation](https://cyberdefenders.org/blueteam-ctf-challenges/?tactics=privilege-escalation), [Credential Access](https://cyberdefenders.org/blueteam-ctf-challenges/?tactics=credential-access)

Tool: [Splunk](https://cyberdefenders.org/blueteam-ctf-challenges/?tools=splunk)



Knowing which user account was compromised is essential for understanding the attacker's initial entry point into the environment. What is the username of the compromised user?

<figure><img src=".gitbook/assets/image (19).png" alt=""><figcaption></figcaption></figure>

We must investigate the events following the initial compromise to understand the attacker's motives. What is the timestamp for the first access to an S3 object by the attacker?

<figure><img src=".gitbook/assets/image (20).png" alt=""><figcaption></figcaption></figure>

Among the S3 buckets accessed by the attacker, one contains a DWG file. What is the name of this bucket?

<figure><img src=".gitbook/assets/image (21).png" alt=""><figcaption></figcaption></figure>

We've identified changes to a bucket's configuration that allowed public access, a significant security concern. What is the name of this particular S3 bucket?

<figure><img src=".gitbook/assets/image (25).png" alt=""><figcaption></figcaption></figure>

Creating a new user account is a common tactic attackers use to establish persistence in a compromised environment. What is the username of the account created by the attacker?

<figure><img src=".gitbook/assets/image (24).png" alt=""><figcaption></figcaption></figure>

Following account creation, the attacker added the account to a specific group. What is the name of the group to which the account was added?

<br>

<figure><img src=".gitbook/assets/image (23).png" alt=""><figcaption></figcaption></figure>



I successfully completed AWSRaid Blue Team Lab at @CyberDefenders! https://cyberdefenders.org/blueteam-ctf-challenges/achievements/Defend\_and\_Defeat/awsraid/

\#CyberDefenders #CyberSecurity #BlueYard #BlueTeam #InfoSec #SOC #SOCAnalyst #DFIR #CCD #CyberDefender
