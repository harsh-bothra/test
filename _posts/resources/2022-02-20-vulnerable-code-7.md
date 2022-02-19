---
title: "Vulnerable Code Snippet - 7"
classes: wide
tag: 
  - ""
header:
  teaser: /assets/images/htb/htb.png
ribbon: green
description: "RCE via SQLi"
categories:
  - Vulnerable Code Snippet
---
### SecurityExplained S-19: Vulnerable Code Snippet - 7

#### Vulnerable Code:

![Vulnerable Code](https://github.com/harsh-bothra/SecurityExplained/blob/main/media/code-7.jpg)

#### Solution:

The code is vulnerable to Remote Code Execution via SQL Injection. As per SonarSource, addslashes() is not enough to protect against SQL injections because the interpolated value is not surrounded by quotes. This value is later used in the external shell call without proper escaping.

A payload like 1--$(id>foo) is enough to gain RCE!

##### Code Credits: SonarSource

[Follow Twitter Thread](https://twitter.com/harshbothra_/status/1483835811896655877?s=20&t=DGEwqEwXwFbWH0VXkOKVsQ)
