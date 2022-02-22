---
title: "Vulnerable Code Snippet - 30"
classes: wide
tag: 
  - ""
header:
  teaser: /assets/images/htb/htb.png
ribbon: green
description: "RCE via SSTI"
categories:
  - Vulnerable Code Snippet
---
### SecurityExplained S-43: Vulnerable Code Snippet - 30

#### Vulnerable Code: 

![Vulnerable Code](https://raw.githubusercontent.com/harsh-bothra/SecurityExplained/main/media/code-30.jpg)


#### Solution: 


This code is vulnerable to SSTI and as a result, an attacker may attempt to gain RCE. The code uses "user input" to search in its store. However, it does not filter the return value of the template render.

Ex Payload: {{10-6}} => 4


Twitter Thread: https://twitter.com/harshbothra_/status/1492332636756398083

##### Code Credits: @Brumens2 
 
