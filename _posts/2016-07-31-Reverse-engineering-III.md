---
layout: post
title: Reverse engineering-III angar
description: comms.ino.hex
summary: comms.ino.hex 
tags: Reverse-engineering 
minute: 1
---

We have lost contact with a space craft. This is it's commination controller file could you please help us reverse engineer it?

[download the code](https://pankace.github.io/violet-rabbit-v2/files//Reverse-engineering-II//sketch_jul02a.ino.standard.hex)

This table might help you decode the messuage in the file 
Note that doing Reverse-engineering-I might yield clues as to how to solve the challenge  


```py
#examples of formatting of I-hex
Address: 013016 = 30410
Byte count: 1016 = 1610
Record type: 0016 = Data
Checksum: C716
Calculated checksum: C716
```
some strings that might help you 

```cpp
'A'; = String(".-");
'B'; = String("-...");
'C'; = String("-.-.");
'D'; = String("-..");
'E'; = String(".");
'F'; = String("..-.");
'G'; = String("--.");
'H'; = String("....");
'I'; = String("..");
'J'; = String(".---");
'K'; = String("-.-");
'L'; = String(".-..");
'M'; = String("--");
'N'; = String("-.");
'O'; = String("---");
'P'; = String(".--.");
'Q'; = String("--.-");
'R'; = String(".-.");
'S'; = String("...");
'T'; = String("-");
'U'; = String("..-");
'V'; = String("...-");
'W'; = String(".--");
'X'; = String("-..-");
'Y'; = String("-.--");
'Z'; = String("--..");
'0'; = String("-----");
```


