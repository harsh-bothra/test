---
title: "Vulnerable Code Snippet - 36"
classes: wide
tag: 
  - ""
header:
  teaser: /assets/images/htb/htb.png
ribbon: green
description: "SSRF"
categories:
  - Vulnerable Code Snippet
---
### SecurityExplained S-49: Vulnerable Code Snippet - 36

#### Vulnerable Code: 

![Vulnerable Code](https://raw.githubusercontent.com/harsh-bothra/SecurityExplained/main/media/code-36.jpg)


#### Solution: 

This code is vulnerable to Server-Side Request Forgery due to improper filtration in the "connName". An attacker can abuse it perform the attack successfully.

Twitter Thread: https://twitter.com/harshbothra_/status/1494127206552985605

##### Code Credits: @SonarSource
