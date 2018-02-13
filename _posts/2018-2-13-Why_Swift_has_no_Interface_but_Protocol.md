---
layout: post
title: 为何Swift没有接口（Interface），却使用了协议（Protocol)来称呼类似接口的概念？
---

Summary：
Protocol最早出现于smalltalk，而OC则继续发扬光大了Protocol这个概念。Interface则是Java从Smalltalk和OC等前辈语言中整理并自创出来的概念。因此可以说Interface继承（但并不仅仅继承）自Protocol。
Swift为了保持与OC的兼容性，以及苹果内部的一些生态理由，同样选择了继续使用Protocol而不是Interface。
Interface和Protocol并不相同但越来越相似。
