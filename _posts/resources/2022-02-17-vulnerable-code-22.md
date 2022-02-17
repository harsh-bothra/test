---
title: "Vulnerable Code Snippet - 22"
classes: wide
tag: 
  - ""
header:
  teaser: /assets/images/htb/htb.png
ribbon: green
description: "CMD Injextion"
categories:
  - Vulnerable Code Snippet
---
### SecurityExplained S-35: Vulnerable Code Snippet - 22

#### Vulnerable Code:

![Vulnerable Code](https://github.com/harsh-bothra/SecurityExplained/blob/main/media/code-22.jpg)

#### Solution:

As per @SonarSource, Arbitrary arguments can be added to the tar command, e.g. by creating a file named “-I touch shell” in /opt/webapp. The -I argument allows executing an arbitrary command, here “touch shell”. --checkpoint-action works too.

Twitter Thread: https://twitter.com/harshbothra_/status/1489630710025830400

##### Code Credits: SonarSource

[Follow Twitter Thread](https://twitter.com/harshbothra_/status/1489630648159846400?s=20&t=DGEwqEwXwFbWH0VXkOKVsQ)
