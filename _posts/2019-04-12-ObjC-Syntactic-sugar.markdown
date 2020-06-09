---
layout: post
title:  "一个NSArray的语法糖"
date:   2019-04-12 09:59:21 +0800
categories: ObjC
---

```
NSArray *array = @[@"A" @"B" @"C"];
```
这会创建一个只包含`"ABC"`的数组

```
NSLog(@"%@", [array[0] isEqual:@"ABC"] ? @"true" : @"false");
// true
```