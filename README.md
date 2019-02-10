# 系统设计-Feb'19

标签（空格分隔）： Interview Database DistributedSystem

---

[TOC]

> + Feb 9: init. 整理System Design Interview的资料

# Reference

## Github
* [coding-interview-university](https://github.com/jwasham/coding-interview-university)
* [donnemartin/system-design-primer](https://github.com/donnemartin/system-design-primer)
* [checkcheckzz/system-design-interview](https://github.com/checkcheckzz/system-design-interview)
* [binhnguyennus/awesome-scalability](https://github.com/binhnguyennus/awesome-scalability)
* [Java Core Sprout：处于萌芽阶段的 Java 核心知识库](https://github.com/crossoverJie/JCSprout)
* [Tushar Roy的多线程Java实例](https://github.com/mission-peace/interview/tree/master/src/com/interview/multithreaded): 不仅有youtube, 还有完整的代码, 可以方便自己复习.
* [kamranahmedse/developer-roadmap#back-end-roadmap)](https://github.com/kamranahmedse/developer-roadmap#back-end-roadmap)

## Youtube
* [Tushar Roy - Coding Made Simple](https://www.youtube.com/user/tusharroy2525): 这个印度人讲的确实很好. 有system design的分析过程, 也有leetcode的题目解法.
* [Gaurav Sen - System design](https://www.youtube.com/watch?v=5faMjKuB9bc): 拜服. 平时就听他的, 要像他这样烂熟于胸. 可以从头到尾写一遍重要的概念.

## Blog
* [The morning paper: Adrian Colye](https://blog.acolyer.org/2015/03/04/paxos-made-simple/)
* [favorite posts on HighScalability](http://highscalability.com/all-time-favorites/)
* [SSM(十八) 秒杀架构实践](https://crossoverjie.top/2018/05/07/ssm/SSM18-seconds-kill/#distributed-redis-tool-%E2%AC%86%EF%B8%8Fv1-0-3)
* [WTF: The Who to Follow Service at Twitter](https://medium.com/@vipulrawat007/wtf-the-who-to-follow-service-at-twitter-dff156fbc0e8): 挺好的paper reading的Blog.
* [1亩3分地 - [系统设计/OOD] 系統設計救星! 一天內手把手教你面試System design](https://www.1point3acres.com/bbs/thread-208829-1-1.html)

## Course
* [Grokking the System Design Interview](https://www.educative.io/collection/5668639101419520/5649050225344512)
* [System design interview questions with solutions](https://github.com/donnemartin/system-design-primer#system-design-interview-questions-with-solutions): 来自donnemartin/system-design-primer
    * Design Pastebin.com (or Bit.ly)
    * Design the Twitter timeline and search (or Facebook feed and search)
    * Design a web crawler
    * Design Mint.com
    * Design the data structures for a social network
    * Design a key-value store for a search engine
    * Design Amazon's sales ranking by category feature
    * Design a system that scales to millions of users on AWS
* [Scalability Lecture at Harvard](https://www.youtube.com/watch?v=-W9F__D3oY4)
    * horizontal scaling (13:00 - 21:00)
    * load balancing & caching (21:00 – 29:00)
	* shared session state (29:00 – 34:00)
	* RAID (36:00 – 40:00)
	* shared storage tech (42:00)
	* database replication (43:00)
	* load balancing tech (44:00 – 45:00)
	* session affinity (46:00 – 51:00)
	* in-memory caching (59:00 – 1:00:00)
	* data replication – active:passive (1:11:00 - 1:14:00)  
	* active:active (1:16:00 - 1:21:00)
	* partitioning (1:21:00 – 1:34:00)
	* data center redundancy (1:33:00 – 1:39:00)
	* security (1:39:00 – 1:44:00)

* [Using Databases with Python: Coursera](https://www.coursera.org/learn/python-databases). Course project in SQLite, Data modeling.
	
---

# Paper
## Distributed System
* WTF who to follow - Twitter
* Raft: MIT 6.824


## Database
* [ARIES: A Transaction Recovery Method Supporting Fine-Granularity Locking and Partial Rollbacks](https://blog.acolyer.org/2016/01/08/aries/): by Morning Paper
* [Dynamo: Amazon's highly available key-value store](http://muratbuffalo.blogspot.com/2010/11/dynamo-amazons-highly-available-key.html): Metadata blog from Prof. Murut
    * [Pynamo: Exploring the Dynamo Paper in Python](https://www.lurklurk.org/pynamo/pynamo.html)
