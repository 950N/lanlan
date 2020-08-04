---
title: 许式伟的架构课
description: A class about software architecture.
date: 2018-05
tags:
  - class
layout: layouts/post.njk
---
年初制定计划的时候，就安排上梳理系统架构思路的任务，找了很多资料，大部分只从技术角度提及了【高并发】【高可用】【可扩展】三个系统设计比较常见的的技术需求，以及罗列一些具体的技术选型，这仿佛又回到不断追求具体技术的循环之中，梳理的效果甚微，也没有搞懂架构的本质。

一个多月前，关注到七牛云许式伟老师的架构课，听过其大名，如此出色公司的CEO为何发布这一档课程，应该不是为了赚钱，或许真是分享其多年的知识总结呢？抱着这个希望，购买了本套课程。整套58讲，截至今晚，更新到34课时，提供图文、音频，我觉得评论区的讨论也很精彩，会引出很多思考。

简单介绍一下许式伟老师，七牛云CEO，说是CEO，也是深耕技术多年的大佬，同时兼备着敏锐的商业头脑。技术方面，Golang最早的国内布道者，本来自己团队研发出一门类似的语言，后来发现了Go，而且觉得Go要比自己的更优雅，果断弃之。七牛云起家业务应该是对象存储服务，以前从事的工作有对接过。随着数据的累计，AI的发展，衍生出直播、短视频、泛安防、CDN加速等业务。

docker、k8s都是利用Go开发的著名产品，因为太有名，貌似Go被挂上一个为云而生的语言，其实在web服务、运维方面都有很多应用。我没有写过Go，代码上不好做评价，但是它部署真的是方便高效。有一个奇怪的示例，号称下一代nodejs的deno，立项初期，使用Go来开发，一段时间后，突然发现转为Rust实现，作者rd解释主要原因速度不够快，Go就这么被放弃掉。也因此，引起我对Rust的兴趣，它主要面向系统级应用，号称速度、安全为其王牌，入门一段时间，后来没跟上节奏，有时间得捡起来，貌似越扯越远了！！！

推荐：Carrie Anne的计算机速成课，B站有翻译精校版，英语好的可以去油管看原版。一共40节，每节10min+，刚好对应冯诺依曼体系等基础知识，看完后绝对有成长，非常幸运，同时接触的两门课程，相互补充。

架构设计最迷人也是最难攻坚的点是，根据产品不同时期以及迭代速度、沉淀和更替的变化而变化。产品从一个工程到模块化再到组件化最后插件化，如果能深刻理解项目不同阶段和不同体量的技术架构选型，而且各个流程中，不同阶段存在不同的方案，期间也要保证最大的协同开发效率，这是一件多么具有挑战、令人沸腾的事情。

不以业务驱动的技术开发都是耍流氓，即使身处Google这种强工程师文化的公司(其实Google已经开始受到了一些这种文化带来的恶果，譬如GCP的占有率相比Amazon差一截，一方面是布局晚，另一方面售后服务无法满足客户，工程师不太想去提供咨询)，也要从业务出发，选择最合适的。同样产品的需求也不能脑洞太大，应该实打实来源于客户反馈。

关于工程质量，从一接手就要严格把关，不要依赖后期的重构，重构有时会比从零开发还要耗费时间，为自己，为他人。
