---
title: 'Python Coroutine'
title_cn: "python 协程"
date: "2019-04-22 14:39:27"
author: "Yan Xu"
tags:
  - python
  - coroutine
  - python__concept
  - 协程
categories:
  - python
  - tech
---


### What (meaning)
---
- 协程，又称微线程，纤程。英文名: coroutine
- 协程看上去像子程序，但但执行的过程中内部可中断，执行其他的协程，在适当的时候再返回来接着执行。
- 协程是一个线程执行
- "子程序就是协程的一种特例" _—— Donald Knuth

### Feature
---
- 极高执行效率
    - 协程之间的切换不是线程之间的切换，而是由程序自身控制，没有线程切换的开销
    - 不需要多线程的锁机制，不存在写变量冲突，通过判断状态来控制共享资源

### Why (mechanism)
---


### How (usages)
---
- 多进程 + 多协程：既充分利用多核，又能够发挥多协程的优势。





