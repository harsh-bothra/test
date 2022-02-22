---
title: "Vulnerable Code Snippet - 14"
classes: wide
tag: 
  - ""
header:
  teaser: /assets/images/htb/htb.png
ribbon: green
description: "Code Execution"
categories:
  - Vulnerable Code Snippet
---
### SecurityExplained S-26: Vulnerable Code Snippet - 14

#### Vulnerable Code:

![Vulnerable Code](https://raw.githubusercontent.com/harsh-bothra/SecurityExplained/main/media/code-14.jpg)

#### Solution:

The code is vulnerable to code execution due to use of array_map() function. An attacker can perform attack like: array.php?map=phpinfo, that execute phpinfo() in it.

##### Code Credits: Octagon Networks

[Follow Twitter Thread](https://twitter.com/harshbothra_/status/1486375951084961792?s=20&t=DGEwqEwXwFbWH0VXkOKVsQ)
