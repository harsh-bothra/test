---
title: "Vulnerable Code Snippet - 38"
classes: wide
tag: 
  - ""
header:
  teaser: /assets/images/htb/htb.png
ribbon: green
description: "DOM XSS"
categories:
  - Vulnerable Code Snippet
---
### SecurityExplained S-51: Vulnerable Code Snippet - 38

#### Vulnerable Code: 

![Vulnerable Code](https://raw.githubusercontent.com/harsh-bothra/SecurityExplained/main/media/code-38.jpg)


#### Solution: 

The code is vulnerable to DOM-based XSS and allows execution of XSS using "s" parameter using payloads like: x'onmouseover=alert(1)//

Twitter Thread: https://twitter.com/harshbothra_/status/1495224184611524608

##### Code Credits: @Brumens2
