---
title: "Vulnerable Code Snippet - 16"
classes: wide
tag: 
  - ""
header:
  teaser: /assets/images/htb/htb.png
ribbon: green
description: "XXE"
categories:
  - Vulnerable Code Snippet
---
### SecurityExplained S-28: Vulnerable Code Snippet - 16

#### Vulnerable Code:

![Vulnerable Code](https://github.com/harsh-bothra/SecurityExplained/blob/main/media/code-16.jpg)

#### Solution:

The code is vulnerable to XXE attack because the use of the `LIBXML_NOENT` enables the external entity loading in php8.

Similar Issue: https://blog.sonarsource.com/wordpress-xxe-security-vulnerability

##### Code Credits: SonarSource

[Follow Twitter Thread](https://twitter.com/harshbothra_/status/1487080467861889030?s=20&t=DGEwqEwXwFbWH0VXkOKVsQ)
