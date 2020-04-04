# pcap-tutorial

PCAP 从入门到成神

---

在学习一门技术之前

首先要想清楚三件事：

1. What
2. Why
3. How

其次，如果想要在学习的路上走得更远，就应该记住这六个字：

> 用什么学什么。

最后，随着学习的慢慢深入，知识体系会越来越庞大，这是就得搞明白另外两个字

> 舍，得。

假如目标是“成神”，那就还要完成一件至关重要的事情

> 为自己找一个坚持下去的理由。

---

## Content

- 基础
- 核心库
- 编程库
- 教程文档
- 进阶
- 其它

## 基础

- [Wikipedia.org-PCAP](https://en.wikipedia.org/wiki/Pcap)：请认真读一读

- [TCPDump-Manpage of PCAP](https://www.tcpdump.org/manpages/pcap.3pcap.html)：请认真读一读，熟悉一下各种函数的作用

- [Programming with pcap](https://www.tcpdump.org/pcap.html)：大致浏览，熟悉一下 PCAP 的基本流程

- [Manpage of PCAP-FILTER](https://www.tcpdump.org/manpages/pcap-filter.7.html)：很重要，可作为手册使用
- [TCP/IP 详解卷(Ⅰ)](https://www.kancloud.cn/lifei6671/tcp-ip/139758)

## 核心库

#### Libpcap

- [Wikipedia.org-TCPDump](https://zh.wikipedia.org/wiki/Tcpdump)：请认真读一读

- [TCPDump.org](https://www.tcpdump.org/)：官方网站

- [Stanford.edu-A Libpcap tutorial](http://yuba.stanford.edu/~casado/pcap/section1.html)：很重要，可作为手册使用

#### Winpcap：基于 Libpcap

- [Winpcap.org-Documentation](https://www.winpcap.org/docs/docs_412/html/main.html)：与 Libpcap 有重合内容，作为手册使用

#### Npcap：基于 Winpcap

- [Namp.org-Npcap](https://nmap.org/npcap/)：只是个介绍，大致浏览

## 编程库

#### Java

- [Pcap4J](https://www.pcap4j.org/)（只推荐这一个）
- [pkts]([https://github.com/aboutsip/pkts)（不是纯粹的 PCAP 库，只用于处理 .pcap 文件）

#### Python

- scapy（只推荐这一个）

#### C#

- winpcap（最底层，不推荐）

#### C/C++（日常使用不推荐）

- libpcap（最底层，不推荐）
- winpcap（最底层，不推荐）

## 教程文档

#### 原理教程

- [Intro to PCAP](./doc/intro-to-pcap-public-release.pdf)
- [SCU-网络监听](./doc/scu-ppt.pdf)

#### 过滤器(PCAP-Filter)教程

- [Libpcap-Filter](https://www.tcpdump.org/manpages/pcap-filter.7.html)
- [Winpcap-Filter](https://www.winpcap.org/docs/docs_412/html/group__wpcap__tut5.html)
- [Ethereal-TCPDump-Filter](./doc/ethereal-tcpdump.pdf)

#### 编程库教程（较少，我是没看到能用的）

- [Pcap4J-Tutorial](https://github.com/1uvu/pcap4j-tutorial)：按照文档走一遍，甚至抄一遍代码，基本上就是入门了
- [Packet Kit(Pkit)](https://github.com/1uvu/pkit)：可以参观其中 PCAP 相关的源码

研究生期间我打算录制 Pcap4J 的教程放到 B 站，等吧。

## 进阶

- [IETF.org](https://datatracker.ietf.org/)：各种 RFC 文档，精通 PCAP 之后可在此基础之上进阶

## 其它（有兴趣看一看，值得）

- [Wireshark User’s Guide](https://www.wireshark.org/docs/wsug_html_chunked/)
- [Xcap](http://xcap.weebly.com/)
- [Awesome-pcaptools](https://github.com/caesar0301/awesome-pcaptools)