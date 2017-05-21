---
layout: post
comments: true
author: Tim Peters
title: The Zen of Python
description: 
categories: Python
---

当我们在Python交互环境下，输入“import this”这条指令，便会出现Tim Peters的这首诗：
The Zen of Python。

<!--more-->

![Alt text](http://opvilw9ip.bkt.clouddn.com/a%202017-05-21%20at%2018.49.28.png)

详见 [Zen of Python](https://medium.com/getpy/zen-of-python-aa432db216f5)，
中译版可参考 [蟒之禅](http://wiki.woodpecker.org.cn/moin/PythonZen)

说下我对这首诗的理解，对应Python而言，优美的代码应该是：

- 简洁的
- 目标明确的，即你要确定你这段代码想要实现什么功能
- 可读性强
    - 逻辑清晰
    - 结构扁平化，少嵌套（如if等循环语句的嵌套）
    - 代码不要都挤到一块，每段代码仅仅实现一个功能
- 命名规范，如函数的命名，最好跟函数的功能相关，变量的所有字母小写，单词直接用下划线连接，如
def hello_world( )
- 易实现的，应该有一个最直白的解决方法

关于代码规范，更多请参考

- [Google Python Style Guide](https://google.github.io/styleguide/pyguide.html)
- [PEP 8 -- Style Guide for Python Code](https://www.python.org/dev/peps/pep-0008/)

~ Log

- 17.5.21 修改
- 17.5.19 init



