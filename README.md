# 系统设计
* Feb2019->May2020

标签（空格分隔）： Interview Database DistributedSystem

---

[TOC]

> + Feb 9: init. 整理System Design Interview的资料

# Reference

## Github
* [CHEATSHEET: SYSTEM DESIGN FOR JOB INTERVIEW](https://cheatsheet.dennyzhang.com/cheatsheet-systemdesign-a4): Very helpful a4 size cheatsheet for everything. 记得他之前的blog有详细的System Deisng分析: 包括architect, AWS implementation, Schema Design. 现在没了...
* [DrawSQL:Database schema templates](https://drawsql.app/templates/): Collection of real world database schemas from open-source packages and real-world apps that you can use as inspiration when architecting your app.
* [A Distributed Systems Reading List](http://dancres.github.io/Pages/)
* [System Design Cheatsheet](https://gist.github.com/vasanthk/485d1c25737e8e72759f)
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
* [数据库中间件基础](https://mjd507.github.io/2019/06/02/middle-ware-db/): 解决单机DB压力: 读写分离 vs 分库/表. 还可以看Alibaba best practice.
* [System Design Interview Questions – Concepts You Should Know](https://www.freecodecamp.org/news/systems-design-for-interviews/) A quick 1 page review of it.
* [Hacking the Software Engineer Interview, TianPan.co](https://tianpan.co/hacking-the-software-engineer-interview), this is a blog I follow and joined their slack channel.
* [The morning paper: Adrian Colye](https://blog.acolyer.org/2015/03/04/paxos-made-simple/)
* [favorite posts on HighScalability](http://highscalability.com/all-time-favorites/)
* [SSM(十八) 秒杀架构实践](https://crossoverjie.top/2018/05/07/ssm/SSM18-seconds-kill/#distributed-redis-tool-%E2%AC%86%EF%B8%8Fv1-0-3)
* [WTF: The Who to Follow Service at Twitter](https://medium.com/@vipulrawat007/wtf-the-who-to-follow-service-at-twitter-dff156fbc0e8): 挺好的paper reading的Blog.
* [1亩3分地 - [系统设计/OOD] 系統設計救星! 一天內手把手教你面試System design](https://www.1point3acres.com/bbs/thread-208829-1-1.html)

## Course
* [freeCodeCamp courses projects](https://www.freecodecamp.org/learn): learn to finish 2 courses (APIs and Microservices Projects & Take Home Projects). Super good and easy to implement.
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

* [Udacity cs253 by Reddit co-founder: STEVE HUFFMAN](https://classroom.udacity.com/courses/cs253):
	* Course Syllabus: https://www.udacity.com/wiki/cs253#lesson-7-scaling-up
	* Lesson 1: How the Web Works
	* Lesson 2: Forms and Input
	* Lesson 2a: Templates
	* Lesson 3: Databases
	* Lesson 4: User Accounts and Security
	* Lesson 5: APIs
	* Lesson 6: Caching
	* Lesson 7: Scaling Up
		* 1.6 Reddit
		* 1.6.1 Reddit Architecture
		* 1.6.2 Reddit Architecture 2
		* 1.6.3 Thing Db
		* 1.6.4 Scaling
		* 1.6.5 Pre-computed Caching
		* 1.6.6 Interview With Neil
		* 1.6.7 App Server Architecture
		* 1.6.8 Database Architecture
		* 1.6.9 Cache Architecture
		* 1.6.10 Problems With Memcachedb
		* 1.6.11 Locking And Memcache
		* 1.6.12 Zookeeper
		* 1.6.13 Improving Memcache
		* 1.6.14 Pre-Compute Architecture
		* 1.6.15 Mapreduce
		* 1.6.16 Hadoop
		* 1.6.17 Dealing With Search Indexing
		* 1.6.18 Using The Queue
		* 1.6.19 Lock Contention
		* 1.6.20 Growing Reddit
		* 1.6.21 Spam Prevention

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

