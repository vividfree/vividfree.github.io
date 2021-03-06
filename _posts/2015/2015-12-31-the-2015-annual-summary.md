---
layout: post
title: 2015年度总结——知识沉淀
category: 年度总结
tagline: 
tags: [年度总结]
theme :
  name : bootstrap-3
---
{% include JB/setup %}

年度总结是一面镜子，照照镜子看到自己的优缺点，想好自己的努力方向，希望明天的自己要比今天更强大。

## 工作

在小组中能够担下更大的项目，能够负责算法策略的优化以提升广告营收（广告联盟业务），也能够带若干人组成的项目组一起完成项目（[360旅游预测](http://trends.businessdata.360.cn/)、人口属性预测(PC端二期 & 移动端一期)）。

在算法策略方面，虽然还是像以前一样一直都会读些文献，从顶级会议paper 到 lecture note 到 toturial，找具体的专题系统性的读读，进一步夯实了机器学习模型的知识体系，但觉得还是做得不够好，还需更花更大的心思。反倒是觉得最大的进步在于面对实际业务需求时，现在考虑的策略会比以前更全面，不但会思考如何建立起离线数据挖掘流程和在线流程，还会考虑什么样的数据源会有用，数据或者特征有啥特点有多稀疏，如何把握好特征粒度。此外在实现设计方案时，不仅是更快速地实现，而且也会考虑系统的风险点，以及时间空间的开销。当时间空间开销大时，首先想到的是能否从技术上做快速优化，而不是粗暴得做剪枝。很多时候因为不同业务会有不同需求，但还是会要求自己开发出一套尽可能通用的流程。今年自己开发的最满意模块是9月份开发的大规模稀疏矩阵相乘流程，基于倒排索引思路，该流程的每个模块上都充分考虑了数据倾斜带来的影响，并提供了相应的解决办法。

在项目管理方面也有一点经验积累。在进行360旅游预测项目之前，并没有真正带过一个含有前端页面的线上项目。当时部门的产品经理业务压力大，没有精力支持此项目，上司就让我既当产品经理又当项目经理，既需要定PRD文档，找交互找视觉找前端找测试，还找了好几个兄弟团队帮忙提供一些数据支持。后端研发人力又有限，除了需要定离线流程和在线流程的设计方案，还需要码代码，主要参与到爬取和解析一些旅游相关的数据以生成一些必要的词典。好在队友都很给力，项目最终顺利上线。虽然自己肯定还不是合格的项目经理，更算不上产品经理，但经过这个项目，收获还是很大的。不同角色的团队的思维习惯不同，所以需要沟通去适应大家的习惯。从和大家的沟通中能了解和学习到很多自己不熟悉的点。当然还普及了下国情知识，比如国内的340余个地级市，将近170个民用机场及其三字码，将近2300个火车站及其编号（截止到2015年2月份），还接触到贝塞尔曲线在前端上的应用。

此外，闲暇时间逼着自己写了几篇中文专利灌了灌水，确实比发paper要简单很多，不过灌水的事还是少做，不如把这些时间攒下来沉淀知识。

## 学习

隔三差五地就会思考以后要做什么，也有时跟朋友聊聊在做啥，当了解到啥名词时就在Google、知乎、quora里收集资料。挺喜欢这种状态的，知识的增长总是能给人一种踏实愉悦的感觉。读过一些快餐书，像《增长黑客：创业公司的用户与收入增长秘籍》、《即时引爆社交红利2.0》、《断点：互联网进化启示录》之类的，可能里面的观点之前或多或少都有所接触和体会，这些书没带来啥特别大的兴奋。以后还是得看点有深度的书籍，刺激大脑多多思考。

今年最大的收获是在github上建立起这个博客便于梳理知识，还在github上开辟了一个代码仓库 [alphabeta](https://github.com/vividfree/alphabet) 便于塞塞个人开发的一些代码（与公司业务无关）。github上的博客和代码仓库的基本框架已建好，就等明年添砖加瓦了。

## 生活

跟媳妇一块去云南玩了10天，对于在北京吸过太多雾霾的人而言，彩云之南之旅特别舒服。遗憾的是没买房，没买车。一个靠资金，一个靠运气，这两个都得好好攒攒，争取明年都搞定。

特别喜欢足球，每天中午总是会花点时间看各种足球视频，MSN的配合、莱万的疯狂、暴力鸟的脚法、恒大的绝杀，今年太多经典镜头值得永远回忆。最开心的是巴萨拿五冠（其中一个是欧冠冠军）和恒大拿双冠（其中一个是亚冠冠军）。

## 展望

在工作方面，在 算法策略、工程实现、产品思维 三方面同步发展，并突出 算法策略 方面的能力。

在学习方面，继续在 [vividfree的博客](http://vividfree.github.io/) 写文章；给 [alphabet](https://github.com/vividfree/alphabet) 加代码，goal: to create a **Never-Ending Learning System (NELS)**；在知乎上多参与问答。

在生活方面，搞定房和车，虽然这么说有点落俗了。还有更重要的事，多陪媳妇，和媳妇一块去旅行。

踏踏实实的做好上面这三方面，一步一个脚印往前走，这就是最开心的。最后借乔布斯说过的一句话勉励自己

> **Stay hungry! Stay foolish!**
