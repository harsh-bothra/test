---
title: "Vulnerable Code Snippet - 10"
classes: wide
tag: 
  - ""
header:
  teaser: /assets/images/htb/htb.png
ribbon: green
description: "authentication bypass"
categories:
  - Vulnerable Code Snippet
---
### SecurityExplained S-22: Vulnerable Code Snippet - 10

#### Vulnerable Code:

![Vulnerable Code](https://raw.githubusercontent.com/harsh-bothra/SecurityExplained/main/media/code-10.jpg)

#### Solution:

The code is vulnerable to authentication bypass vulnerability. An attacker can impersonate and login as any user as at the line-10 the code doesn't validate the JWT signature.

##### Code Credits: SonarSource

[Follow Twitter Thread](https://twitter.com/harshbothra_/status/1484947412443545602?s=20&t=DGEwqEwXwFbWH0VXkOKVsQ)
