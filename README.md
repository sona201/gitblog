## git 记录一些博客

学习yihong，使用这种方式记录，尝试不同的体验。因为自己已经建了git.io的静态博客，但似乎有些不满意，试试这个方式。

https://github.com/yihong0618/gitblog/issues/282

特别喜欢加的todo-list，这个是我一直想搞的。因为常常把时间浪费在刷推或者一些小视频上，想换个方式。




### 阅读

[TTY 到底是什么？](https://www.kawabangga.com/posts/4515) 
这周再把文章看一遍, 然后写下笔记跟读后感吧, 记录下自己不熟悉的知识
tty 这个了解了，"Line discipline" 可以实现 Ctrl+U  Ctrl+W 的功能
这个记录下笔记，才能算完成
https://cs.pynote.net/sf/linux/shell/202111273/
https://cs.pynote.net/sf/linux/shell/202110285/


- [架构设计 the Easy Way](https://blog.alswl.com/2023/07/architecture-design-the-easy-way/)  
文章还没有来的及仔细研读，但总体内容比较喜欢，讲了一些"大道理"，也举例具体案例，都是比较贴近我的日常实践。\
思考: 看这个文章的会有什么收获？要是我来做会怎么做，从运维的角度有什么不一样的结果？


- 关于半队列, 全队列的知识点, 之前不是很理解. 最近复习了一些网络基础知识再看就清晰很多了.
[从一次线上问题说起，详解 TCP 半连接队列、全连接队列](https://www.51cto.com/article/687595.html) \
[TCP 半连接队列和全连接队列](https://www.cnblogs.com/xiaolincoding/p/12995358.html) \
再回过头看 小林coding 讲的网络基础知识确实不错, 而且会有一些"课后作业", 似乎更懂我哪里还不熟


[排障文章](https://xxchan.me/cs/2023/02/08/profiling-101.html)
profiling 的入门介绍，之前一直以为是排障文章，但文章的主要目的被我搞错了

[eBPF技术介绍](https://imliuda.com/post/1047)
其实我记得陈浩也写了一篇这个文章的，但没有好好看，todo。。。\
这个文章很好，但我好像暂时用不到，很想了解一个技术，但目前没有实践的机会，更主要的是不知道什么场景需要用这个技术 \
再牛逼的技术，没有应用场景也是白搭。

## 四象限法
### 【重要不紧急1(有计划的执行)】
- django的单元测试学习
- django的中间件记录请求日志，中间件的使用，高级
- 这周找到两个关于网络底层的文章，真的很想自己也能有这样的能力，争取能写成文章 \
https://plantegg.github.io/2019/06/21/%E5%B0%B1%E6%98%AF%E8%A6%81%E4%BD%A0%E6%87%82%E6%8A%93%E5%8C%85--WireShark%E4%B9%8B%E5%91%BD%E4%BB%A4%E8%A1%8C%E7%89%88tshark/
- 学习k8s -> kubernetes网络权威指南，这个优先级降低，遇到问题解决问题，因为系统过于庞大，系统性的学习成本很大，优势不清楚。
### 【重要紧急2(立即处理)】
### 【不重要紧急3(合理授权)】
### 【不重要不紧急4(控制比例)】

#### 文章
知乎博主
https://www.zhihu.com/people/giantchen
https://www.zhihu.com/people/skywind3000

#### 学习
- hugo 主题美化, 改成自己喜欢的样子.
- 李三红的极客时间视频学习。这个应该能坚持学完吧，貌似对调优有提高。
- java入门(廖雪峰java学习指南) -> 学习使用spring框架，写一个小demo网上收集了一个文章讲破解java的json序列化的，用来学习 \
[基础入门Fastjson系列漏洞](https://mp.weixin.qq.com/s/SOKLC_No0hV9RhAavF2hcw)
- 在序列化的时候，用序列化，可以学习下官方文档，怎么处理序列化在命令行处理。
- nat 网关ip 转换是怎么实现的，原理是怎样的？
- 搞清楚request请求的链路，比如view层的get请求   ==>  可以让代码写的更快更好
- django restful serializer 与 get_queryset 的代码执行顺序, 怎么看源码
- django 中 mysql的orm调用返回datetime是时区类型，怎么能自动改成普通类型
- django debug tool https://github.com/jazzband/django-debug-toolbar
- django prometheus 暴露
- https://pypi.org/project/django-sql-explorer/ (这个已经不重要了，有sql抓包)
- django源码学习，是否需要每周产出笔记？但不需要为了产出而产出
- 算法学习
- python Django channel 模块的理解，并写一篇文档
- 办一场 django 的框架会议，先把 django restful 的抽象理解，自己操作一遍，写一篇文章
- 还是要搞个 django 可用框架，就是搭建 restful 使用。把自己没踩完的坑填上。（这个可以写到简历里）
  - xops的好多功能都没有玩过，要加油了，要自己写个服务，开源玩起来。
- django 暂时不研究源码，从实践出发，看看别人的项目是怎么做的。
  - 先尝试启动 jumpserver的项目，了解项目架构，这个优先级不高，做成了没有太大的反馈。
  - 这么做的目的是啥？是为了学习什么？目标不要大，不要盲目。
- 英语参考资料(https://catcoding.me/p/new_english_tools/) https://discord.gg/english


#### 视频

[陈硕推荐视频twitter链接](https://twitter.com/bnu_chenshuo/status/1638958411357507584)

- [youtube·Linux 文件系统九讲](https://www.youtube.com/playlist?list=PL3wVcVGXqdnbp8ww_ogY39Mnk8IVNE3B1)
- [bilibili合集·Linux 文件系统九讲](https://space.bilibili.com/1356949475/channel/collectiondetail?sid=1211802)
- [bilibili合集·LevelDB 磁盘数据结构](https://space.bilibili.com/1356949475/channel/collectiondetail?sid=1198509)
- [bilibili合集·重温模拟电路](https://space.bilibili.com/1356949475/channel/collectiondetail?sid=1198507)


https://www.google.com/search?q=neovim&oq=neovim&gs_lcrp=EgZjaHJvbWUyBggAEEUYOTIGCAEQRRhBMgYIAhBFGEEyBggDEEUYQdIBCDE1NjZqMGo3qAIAsAIA&sourceid=chrome&ie=UTF-8#fpstate=ive&vld=cid:dfe44e23,vid:6pAG3BHurdM,st:0
- 再次学习陈浩的专栏，应该会有收获 -> 每天中午在看陈浩的书

#### 笔记
- [如何拯救一台glibc被干掉的Linux服务器?](https://zhuanlan.zhihu.com/p/20062978)
- [wiki busybox](https://zh.wikipedia.org/wiki/BusyBox)
- [cnblog Busybox是什么?](https://www.cnblogs.com/myitm/archive/2011/08/15/2139465.html)
- [什么是 BusyBox 以及它的用途？](https://cn.linux-console.net/?p=7799)
- [BUSYBOX  Official website](https://busybox.net/about.html)
- [Welcome to Gentoo, a highly flexible, source-based Linux distribution.](https://www.gentoo.org/)
- [dotfiles新手教程](https://luolei.org/dotfiles-tutorial#%E4%BD%BF%E7%94%A8git%E5%A4%87%E4%BB%BD)
- [懒程序员和他的 dotfiles](https://blog.coderzh.com/2016/03/19/dotfiles/)
- [CTSS Compatible Time-Sharing System](https://en.wikipedia.org/wiki/Compatible_Time-Sharing_System)
- [有关 TLS/SSL 证书的一切](https://www.kawabangga.com/posts/5330)
- [obsdian使用心得](https://sspai.com/post/82501)

## 博客待输出
- [微信读书上有他的《复旦经济课》](https://twitter.com/plantegg/status/1701066986648899722)
- [分析与思考——黄奇帆的复旦经济课笔记](https://plantegg.github.io/2020/03/01/%E9%BB%84%E5%A5%87%E5%B8%86%E7%9A%84%E5%A4%8D%E6%97%A6%E7%BB%8F%E6%B5%8E%E8%AF%BE--%E7%AC%94%E8%AE%B0/)

[工作焦虑鸡汤]
- [程序员如何把控自己的职业](https://coolshell.cn/articles/20977.html)
- [Hiring Site Reliability Engineers](https://www.usenix.org/system/files/login/articles/login_june_07_jones.pdf) \
- [SRE工程师需要具备的10个基本技能](https://cloud.kapostcontent.net/pub/1418185e-b325-49d3-b65c-de338e45cb6f/ebook-10-essential-skills-of-a-site-reliability-engineer-sre.pdf) \
- [What is Site Reliability Engineering (SRE)?](https://sre.google/)
这个能做个笔记就行了，毕竟做了就忘了，能留在脑子的东西不多。

## 想看的书
- [efficient linux at the command line](https://reconshell.com/wp-content/uploads/2022/01/Efficient-Linux-at-the-Command-Line.pdf) 高效的linux命令行 能把这本书看完么？




---
罗永浩采访

https://www.bilibili.com/video/BV1V4421c7Es/
好像了解的越多，就越喜欢罗永浩。更理解之前的一些同事朋友为什么喜欢他。纯纯的理想主义者。
也能理解他书读的多，越能反驳老师，把别人说的哑口无言。这是一种逻辑能力与知识积累的展现。
他能在家安心读书，（老罗有推荐过哪些书）


- [管理方法](https://p-c8wi.tower.im/p/r0lu)


看了yihong的如何提pr，倒是很有感触，大概就是摸清一个项目如何从零开始启动，且如何搞bug的
挺有意思的：https://github.com/yihong0618/gitblog/issues/296


- 计算机网络（TCP/IP详解）
  - xiaolin 网络：https://xiaolincoding.com/network/
  - 思考下网络知识点，还有就是，想想怎么学习网络知识，为什么要学习，有什么好处。 https://cloud.tencent.com/developer/article/1824735
  - 
- k8s网络
