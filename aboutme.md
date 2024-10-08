---
layout: page
title: "Personal Profile"
permalink: /aboutme
author_profile: true
redirect_from:
  - /resume
---

# 个人简介

## 关于本人

**本博客是关于一个在IT以及分布式领域深耕多年的程序员的故事!**

2005年入川读书，一直在电子科技大学通信学院直到硕士毕业进入社会。

2012年硕士毕业入职华为公司，当时入职的部门是云计算下面的分布式存储。之后一直在做分布式存储相关的业务，直到2020年决定离开。

2020年2月加入阿里巴巴-阿里云，现在主攻数据湖方向。

更详细的介绍请参考[alex-yan的个人简历](https://alex-yan.github.io/cv/)


## 如何联系作者

* 本人与几个志同道合的大厂朋友经营着一个公众号：高梵师哥。该公号聚焦大厂的技能以及职场经验的分享。  

   ![saomaguanzhu](/img/erweima.jpg)

* 个人有一个github账户，用来分享一些优秀的开源项目: -[alex-yan的github](https://github.com/alex-yan)

* 个人邮箱 chaoxiyan1225@163.com


## 其他声明

本博客的任何内容都是所见即所得可以任意分享，如果你觉得受益，希望不吝推广宣传，感谢您花费的时间！  

# 职业简历

## 教育背景

* 学士学位，通信与信息工程, 电子科技大学, 2005-2009
* 硕士学位  通信与信息工程, 电子科技大学, 2009-2012

## 技术总结

* 熟练Java ，熟悉C、shell，生产平台是linux
* 参与企业级云平台开发工作，熟悉公有云/私有云应用程序开发与设计
* 参与企业级分布式忘记系统N9000开发工作，对分布式系统的升级、部署等熟练
* 熟悉分布式基础知识,擅长分布式数据一致性&可靠性技术，对2PC/3PC、NRW、vector Clock、handoff、raft、LSM Tree、DHT等熟练，有扎实的高可用系统的设计与实战经验
* 熟悉S3协议的基础接口，对基于AWS S3的SDK熟练
* 熟悉web后端开发以及RESTful API设计，熟悉jetty、Memcached、MQ等框架
* 熟悉Java的并发编程、NIO、jvm、内存模型等
* 熟悉敏捷开发流程，能带领团队端到端聚焦客户面交付，对项目进度、风险、资源协调等管控
* 优秀的跨团队协调勾勾通能力，熟悉敏捷开发以及项目管理，具有华为项目管理资格证书

## 工作经验

* 华为技术有限公司       分布式存储  2012.7-2020.2
* 阿里巴巴技术有限公司   阿里云      2020.2-至今

## 项目经验 

### 阿里云技术有限公司

* 项目1- 数据湖3.0项目：数据湖3.0产品是基于OSS产品的湖仓一体化解决方案，定位做世界领先的数据湖产品。存储底座采用最先进的ARK 架构，全面提升大数据场景的性能以及成本竞争力，个人职责跟贡献如下：

   * 1）-负责3.0版本的底层存储引擎切到ARKDB的设计与实现
   * 2）-通过引入opten+QLC达成100G/100T的带宽竞争力

* 项目2- OSS产品Sprint X项目：阿里云对象存储OSS（Object Storage Service）是一款海量、安全、低成本、高可靠的云存储服务，可提供99.9999999999%（12个9）的数据持久性，99.995%的数据可用性，国内竞争力最强的云存储产品。Sprint X项目作为OSS的性能、竞争力提升版本，提供了内存池/cache，proxywrite、存储引擎range下载等性能提升以及成本优化的关键能力，个人作为版本经理以及开发者贡献如下：

   * 1)-负责整个版本的发布计划以及版本发布，拉通关键特性特性开发以及测试、设计等关键角色，按质量以及进度推进，按时发布版本并负责现网局点变更。
   * 2)-负责关键特性：内存池提升以及进程级cache等关键特性，独立设计以及开发，性能提升XX倍，特性发布之后现网变更业务中断故障范围从XXX到XX，稳定性提升X个点，内存节约XXG，整体成本节约X个点。
   * 3)- 负责代理写关键特性：为了解决单kvserver的热点导致性能瓶颈的架构问题，通过代理写做到负载均衡，提升产品的竞争力。
   * 4)-组织完善测试平台以及测试工具的优化，弥补测试人力不足关键瓶颈，版本中首次尝试开发人员通过平台工具能端到端cover测试流程，完成端到端发布版本人力节省X人力。

### 华为技术有限公司 （2012.7-2020.2）

* 项目1- 中移动NFVI 5GC项目交付（2019-6至今）项目峰值人力  50人：
该项目是中移动总公司对NFVI系统整体升级到5GC，构建运营商与物流、制造、化工、园区、农业等行业协同发展新生态，涉及xx万台服务器，作为分布式存储的交付经理工作如下：
    * 1）拉通用户、产品经理、BA、SA以及周边解决方案、研发对齐交付要求，深挖需求，竞争分析以及软件交付。
    * 2）与中移动设计院、网络所、测试所等甲方单位进行技术以及交付沟通及赋能。
    * 3）对中移动 5GC的存储整体诉求理解深刻，过程对风险识别以及解决即时高效，整体拉通产品上线保障。目前以及完成中移动NFVI 一期项目交付。


* 项目2- FusionStorage block（2018-11至2019-6）项目峰值人力  180人：
该项目是分布式块服务，对外典型应用是虚拟机以及数据库，该版本新增EC特性，降低持有成本，形成成本竞争力，作为版本经理工作如下：
   * 1）项目全周期采用IPD流程，端到端构建分布式块产品竞争力，业界首次推出EC
以及异步复制容灾特性
   * 2）拉通三地（深圳成都上海）五部门协同开发，交付EC、异步复制等大颗粒需求50W行代码，保证项目进度按期推进，并最终成功上市
   * 3）与周边解决方案、一线等协调对齐需求以及交付计划
   * 4）内部的特性按敏捷交付计划对齐以及风向管控
    

* 项目3- FusionStorage （2016-至今）项目峰值人力  100人：
该项目提供分布式对象服务的双活特性，支持多写多读，基于S3协议实现。项目完成后华为公有云/私有云具备异地容灾、跨region访问等特性竞争力。个人工作 如下：
   * 1）拉通周边SE等需求澄清，并基线。
   * 2）跟一线对齐交付范围与时间点，以及沟通实验局。
   * 3）跟周边解决方案拉通对齐联调计划，并例行管理。
   * 4）基于敏捷流程，拉通各部件做整体版本计划以及里程碑，管理风险。
   * 5）处理新增市场需求，并与已接纳需求排序。
   * 6）对服务、维护以及MO等做培训材料导入，支持产品上市。
   * 7）E2E拉通生产制造交付整版本，最终版本评估5星级。

* 项目4-N9000 （2015-2016）：
该项目为企业提供分布式文件服务，对外提供NFS/CIFS协议接口，主流使用场景为视频监控、海关、公安。个人主要工作如下：
   * 1）作为teamleader带领团队完成50K代码交付，过程严控质量，至今无网上事
故
   * 2）完成对整集群性能指标监控并对接性能报表。
   * 3）对集群管理子系统组件监控模（240K）块做重构，重构后缺陷密度降低2个/KL。
   * 4）配合完成了对象服务集成到N9000平台的安装、升级、部署等功能，实现了一
套集群同时出对象以及文件服务。
   * 5)负责集群管理模块的问题接口以及committer。


* 项目5-UDS （2012-2015）：
该期间华为云从2012年7月启动的第一个商用版本开发，一路探索，主要聚焦架构的稳定以及S3接口对标AWS的补齐。后续不断完善架构以及功能，系统规格支持5000W桶，100亿对象，EB级数据量。个人主要工作如下：
   * 1)学习和理解了AWS的Dynamo系统。
   * 2)设计和实现了bucket/object的S3接口，支持大并发（单节点1000）。
   * 3)实现了SOD模块（kv store）节点扩容、减容下rebalance。
   * 4)实现了基于gossip机制的分布式故障检测。
   * 5)设计和实现了副本数据主动一致性校验。
   * 6)设计和实现了系统的垃圾数据删除。


## 荣誉&证书

* 华为明日之星（第一届）
* IT产品线优秀基层主管
* P&S优秀基本团队总裁奖
* 华为RDPM资格认证证书

## 致谢

* 如果您看到这句话，感谢您付出宝贵的时间，希望后续能与您共事。

![road](/img/road.jpg)

