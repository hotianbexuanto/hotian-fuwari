---
title: Sukisu NoGKI 教程
published: 2025-11-05
description: ""
image: ""
tags:
  - ROOT教程
category: 教程
draft: false
lang: ""
---
## 内核更改 - manual钩子

使用sukisu 提供的钩子补丁
![](../image/SUKISU%20NOGKI%20教程.png)

可在侧边直接下载文件。
- 或复制粘贴文件内容
![](../image/SUKISU%20NOGKI%20教程-1.png)

在内核源码下使用指令

```
patch -p1 < “文件名称”.patch
```

![](../image/SUKISU%20NOGKI%20教程-2.png)

运行后可能无法完全正确修补在内核文件中，
在指令执行后的提示中可以看到。
![](../image/SUKISU%20NOGKI%20教程-3.png)
出现了3个未能修补到内核的文件中的代码文件 .rej
请根据.rej文件中的绿色代码部分来复制粘贴到文件中正确的位置来更改

> [!tip]
> 编译请自行根据其他教程进行 本地/云端 编译
