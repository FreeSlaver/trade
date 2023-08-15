---
layout: page
title:   架构师如何做好技术选型？
category: program-system-design
tags:
keywords:
description:
---

如何做好技术选型，这是技术领导，特别是架构师必须具备的能力。对技术宽度和深度，业务的理解程度，使用场景的具体落地都有极高的能力要求。  

## 主要要从以下几个大的方面考虑：
1. 目前要做的业务核心诉求，功能是什么，这个技术能否很好的满足实际业务需要
2. 技术的成本，包括引入，学习使用，运维，改造等，所以最好选择主流的，大家都熟悉，都用过，接触过的技术
3. 这个技术能否与当前已存在的系统架构很好的融合，后续的升级扩展性如何，对业务的侵入性如何
4. 对技术的风险把控，也就是线上出现了故障，能否快速，最小影响，损失的解决掉，这涉及到技术的语言，文档全面性，社区活跃程度等
5. 考虑各方的利益关系博弈
6. 最后根据以上5点，对几个技术组件的优缺点进行横向的比较，深挖实际业务场景的具体实现，最好做做个MVP，POC
## 为什么从这几个方面考虑？
### 第一点
所有的技术都是为了业务服务的，不是为了技术而技术，更不是为了技术的高大上。这是由公司的属性决定的，  
公司的唯一天职就是盈利赚钱，所有的一切资源，不仅仅是技术，运营，产品，推广等等都是为了赚钱的业务本身服务的。  
更进一步来说是：公司存在的本身决定的。  赚钱才能存活。   
中国由技术驱动的公司非常少，这很悲哀，但却是一个事实。
### 第二点
成本主要有2个方面的：1.所有的成本都是由公司承担的，高成本会压缩公司生存环境。  
2.高成本的技术组件，大家会非常抵触，因为学习，使用成本过高，而又不能带给学习使用者带来任何实质利益。

虽然你引入了这个技术组件，解决了特定的业务核心场景，但是也要考虑到后续，改造，升级，扩展等等方面。  
不要解决了一个问题，却埋下10个坑。  
### 第三点
如果不能很好的融合，为了配合你这一个技术组件，别人的系统，运维撒的都要改，没人有那个动力，  
后续就不好开展工作。如果对业务有侵入性，就会加大开发的工作量，本来开发就对产品改来改去的需求积怨已久，
做技术选型的时候考虑未来 3-5 年的业务量，
你要刚好怼到枪口上，画面不要太美。

### 第四点：
假设，我只是假设啊，万一你引入了这个技术组件，然后某天突然服务大面积故障，掉线，最后定位到是你这个
新引入的组件问题，你怎么办？能不能第一时间解决掉，如果不行，公司每小时的损失可能不是一个月工资能补偿的。  
所以为了预防这种情况，你对这个技术的底层核心原理，架构设计优缺点，常见的Bug和Bug原因都要非常熟悉，  
甚至能预判到可能会出现哪些Bug。
### 第五点：
现代化分工，团队合作是必不可少的，所以你必须考虑各个方面的利益诉求，即使是年底优秀员工，月度奖金这些你都要稍微考虑下。 
### 第六点
要具体看看哪些组件缺少对哪些功能的支持，为什么不支持，那些支持的是如何实现的，实现是否优雅，合乎几个大的设计原则。  
如果是你来实现，你会如何实现？它这种实现，后续可能会有哪些问题？这些你都得考虑。  
证的案例一定是拿公司里面的最复杂的情况进行验证，而且整个验证过程最好是按照日常的工作流程进行模拟
## 以消息中间件举例
常见的消息组件有：





























































