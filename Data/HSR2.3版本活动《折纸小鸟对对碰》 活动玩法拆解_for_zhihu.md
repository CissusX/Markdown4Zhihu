# 概述

* 拆解对象：《崩坏：星穹铁道》2.3版本活动玩法《折纸小鸟对对碰》

* 本文将围绕2个核心问题进行分析：

  * 活动玩法的核心体验是什么？这种核心体验是如何实现的？

  * 活动设计如何适应玩家需要？



# 规则

仅对单局规则和主要循环作简要图示，详细文字描述见：[ 《折纸鸟》活动玩法规则描述](https://h6dcn2ovif.feishu.cn/docx/JcmddNtFsoLsF3x0NsEccuBBndb?from=from_copylink)



图例：

* 紫色表示某个游戏行为

* 黄色表示某个游戏资源

![单局玩法示意图（仅单个玩家，图中简化了外部循环）](https://raw.githubusercontent.com/CissusX/Markdown4Zhihu/master/Data/HSR2.3版本活动《折纸小鸟对对碰》 活动玩法拆解/image-7.png)

![活动流程与奖励 示意图](https://raw.githubusercontent.com/CissusX/Markdown4Zhihu/master/Data/HSR2.3版本活动《折纸小鸟对对碰》 活动玩法拆解/image-8.png)



![](https://raw.githubusercontent.com/CissusX/Markdown4Zhihu/master/Data/HSR2.3版本活动《折纸小鸟对对碰》 活动玩法拆解/diagram.png)



# 包装

* “折纸小鸟”形象融合角色特征，强化玩家对角色的记忆，利好卖卡和社区二创

![](https://raw.githubusercontent.com/CissusX/Markdown4Zhihu/master/Data/HSR2.3版本活动《折纸小鸟对对碰》 活动玩法拆解/image-9.png)

# 体验

## 核心体验：消除、博弈

1. **消除**的爽快感

2. 获胜（取得前三）的成就感

3. **博弈**过程中紧张刺激的感受（濒死状态下进一步强化）



## 如何强化消除的爽快感

### 循环

![三消的基础循环](https://raw.githubusercontent.com/CissusX/Markdown4Zhihu/master/Data/HSR2.3版本活动《折纸小鸟对对碰》 活动玩法拆解/image.png)

![增加【炸弹】](https://raw.githubusercontent.com/CissusX/Markdown4Zhihu/master/Data/HSR2.3版本活动《折纸小鸟对对碰》 活动玩法拆解/image-1.png)

![增加【技能】](https://raw.githubusercontent.com/CissusX/Markdown4Zhihu/master/Data/HSR2.3版本活动《折纸小鸟对对碰》 活动玩法拆解/image-2.png)

通过增加【技能】机制，构建新的强化循环（如图3），使每次操作触发消除的次数大大增加，从而强化消除的爽快感

### 表现

![](https://raw.githubusercontent.com/CissusX/Markdown4Zhihu/master/Data/HSR2.3版本活动《折纸小鸟对对碰》 活动玩法拆解/旋转动画+特效.png)

![](https://raw.githubusercontent.com/CissusX/Markdown4Zhihu/master/Data/HSR2.3版本活动《折纸小鸟对对碰》 活动玩法拆解/特殊消除的特效.png)

![](https://raw.githubusercontent.com/CissusX/Markdown4Zhihu/master/Data/HSR2.3版本活动《折纸小鸟对对碰》 活动玩法拆解/水果消除特效.png)

略。主要是动画与特效。



## 强调心理博弈的决策设计

这部分主要围绕：

* 单局玩法是如何融合三消与自走棋框架的？

### 单局决策节奏

决策维度较少，弱化了三消部分的决策，以上层的心理博弈为主：

* 博弈：【生命值】/【濒死机会】/【超级炸弹】的分配

* 三消：交换水果的选择



决策时间上，同时存在时间限制与步数限制，对玩家有一定要求：

* 限时设计使玩家不能够分配较多时间在三消的选择上

* 步数与操作限制使玩家依旧需要考虑每一步消除的收益

![](https://raw.githubusercontent.com/CissusX/Markdown4Zhihu/master/Data/HSR2.3版本活动《折纸小鸟对对碰》 活动玩法拆解/image-3.png)

主要决策内容将随单局进程从【三消】转移到【博弈】：

* 【超级炸弹】数量增多，玩家基本不需要思考三消选择，释放限时思考三消选择的压力

* 决策维度减少后，玩家能够分配部分注意力资源用于观察敌方行为与状态

### 【超级炸弹】：串联三消和自走棋框架的核心元素

【超级炸弹】如何被设计为单局的核心资源（通过影响该回合扣除的生命值）？

* 机制1：玩家将继承前一轮的最终场地（【超级炸弹】）

* 机制2：关卡机制使得单局中后期能获得稳定数量的【超级炸弹】（需要启动成本）

* 机制3：【超级炸弹】只能通过玩家操作触发

* 机制4：【超级炸弹】x2 的单次消除收益较高且可预期

![](https://raw.githubusercontent.com/CissusX/Markdown4Zhihu/master/Data/HSR2.3版本活动《折纸小鸟对对碰》 活动玩法拆解/image-4.png)



### 不完全信息动态博弈

![](https://raw.githubusercontent.com/CissusX/Markdown4Zhihu/master/Data/HSR2.3版本活动《折纸小鸟对对碰》 活动玩法拆解/image-5.png)

单回合对抗中，玩家需要基于对方行为（需要等待动画，有滞后性）和公开信息，基于以下目标做出最有利的决策：

* 保证仍有【濒死机会】/【生命值】，使自己不出局

* 在保证生存的情况下，保留尽可能多的【超级炸弹】



### 【超级炸弹】数量-单次消除收益的平衡

* 避免囤积【超级炸弹】成为单局玩法中的统治性策略

  * 平衡循环构成：由于【超级炸弹只能通过交换消除】，积攒的超级炸弹会占据棋盘格，使得能被炸弹消除的水果数量变少，消除触发机制次数变少，产生的超级炸弹变少

![](https://raw.githubusercontent.com/CissusX/Markdown4Zhihu/master/Data/HSR2.3版本活动《折纸小鸟对对碰》 活动玩法拆解/image-6.png)



## 适应游戏本体的设计：轻量化、多端平衡

### 表现：直观

* 通过“折纸小鸟的大小”反映对抗双方的战斗力：在需要根据多个信息进行决策的情况下，有效减轻信息获取负担

![](https://raw.githubusercontent.com/CissusX/Markdown4Zhihu/master/Data/HSR2.3版本活动《折纸小鸟对对碰》 活动玩法拆解/大小1.png)

![](https://raw.githubusercontent.com/CissusX/Markdown4Zhihu/master/Data/HSR2.3版本活动《折纸小鸟对对碰》 活动玩法拆解/大小2.png)

### 交互：易操作

* 操作行为简单（滑动/拖拽），操作频次低，兼顾了以下2点：

  * 作为多端适配游戏，需要同时考虑触屏、键鼠、手柄的交互体验

  * 作为有对抗要素的玩法，需要平衡不同平台下操作差异对对局的影响

### 玩法：低复杂度，强调娱乐而非竞技

学习成本低，技巧深度浅，以娱乐性为主：

* 弱化三消玩法的策略思考，将重心转移到核心资源的分配上：适配自走棋模式较快的对局节奏，同时减少策略思考负担，降低游玩门槛；

* 较少的玩法元素（对比自走棋组卡、位置排布等），以减少玩法复杂度；



![](https://raw.githubusercontent.com/CissusX/Markdown4Zhihu/master/Data/HSR2.3版本活动《折纸小鸟对对碰》 活动玩法拆解/image-10.png)

## 如何平衡不同技巧水平玩家的游玩体验

* 玩法设计上弱化了技巧深度，同时通过单人部分承接部分的引导和教学，使得大部分玩家技巧差异较小

* 通过增多随机要素，减少技巧对对局结果的影响

  * case：技能目标的随机、三消玩法本身的随机

* 匹配机制上的设&#x8BA1;*（不清楚是否有人机和玩家能力分数等设计，不展开但需要考虑）*

## 如何减少失败的负反馈

* 低重开成本：短单局时间（每2回合增加战损，加快单局节奏）

* 目标分层：前3名（单局6名玩家）都视为部分胜利

![活动联机玩法-战绩界面](https://raw.githubusercontent.com/CissusX/Markdown4Zhihu/master/Data/HSR2.3版本活动《折纸小鸟对对碰》 活动玩法拆解/image-11.png)



## 作为长线运营游戏活动的设计点

* 常驻内容的选择：仅常驻可控的消耗性内容（单人部分），回避了多人对抗类玩法平衡性上的潜在问题

  * 单人部分作为教学引导和消耗性内容，常驻

  * 多人部分作为版本大活动的支撑部分，非常驻

