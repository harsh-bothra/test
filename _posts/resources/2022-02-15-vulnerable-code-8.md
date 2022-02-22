---
title: "Vulnerable Code Snippet - 8"
classes: wide
tag: 
  - ""
header:
  teaser: /assets/images/htb/htb.png
ribbon: green
description: "Path Traversal"
categories:
  - Vulnerable Code Snippet
---
### SecurityExplained S-20: Vulnerable Code Snippet - 8

#### Vulnerable Code:

![Vulnerable Code](https://raw.githubusercontent.com/harsh-bothra/SecurityExplained/main/media/code-8.jpg)

#### Solution:

The code is vulnerable to path traversal attack. There is a sanitization against this attack but the protection is not sufficient and can be bypassed with the payloads such as ".\./.\.shell.jsp".

##### Code Credits: SonarSource

[Follow Twitter Thread](https://twitter.com/harshbothra_/status/1484208541707927554?s=20&t=DGEwqEwXwFbWH0VXkOKVsQ)
