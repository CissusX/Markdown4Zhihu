# 概述

* 围绕2个核心问题：

  * 活动玩法的核心体验是什么？

  * 这种核心体验是如何实现的？

* 拆解对象：《崩坏：星穹铁道》2.3版本活动玩法《折纸小鸟对对碰》



# 玩法规则

图例：

* 紫色表示某个游戏行为

* 黄色表示某个游戏资源

![单局玩法示意图（仅单个玩家，图中简化了外部循环）](https://raw.githubusercontent.com/CissusX/Markdown4Zhihu/master/Data/折纸鸟活动拆解/image-4.png)

![活动流程与奖励 示意图](https://raw.githubusercontent.com/CissusX/Markdown4Zhihu/master/Data/折纸鸟活动拆解/image-5.png)



![](https://raw.githubusercontent.com/CissusX/Markdown4Zhihu/master/Data/折纸鸟活动拆解/diagram.png)

* 文字详细描述：[ 《折纸鸟》活动玩法规则描述](https://h6dcn2ovif.feishu.cn/docx/JcmddNtFsoLsF3x0NsEccuBBndb?from=from_copylink)



# 玩法包装

* 将抽象出的角色特征融合进“折纸小鸟”的形象（1.6版本的猫猫糕活动也有类似的设计），作为玩法中操控对战折纸小鸟的形象包装

  * 好处：在活动中增加玩家对角色的记忆点，利好社区二创

# 体验

## 核心体验：消除反馈与策略博弈

1. 消除的爽快感

2. 单局过程中策略博弈的紧张感，博弈成功后对压力的释放



## 如何强化消除的爽快感

### 循环

![三消的基础循环](https://raw.githubusercontent.com/CissusX/Markdown4Zhihu/master/Data/折纸鸟活动拆解/image.png)

![增加【炸弹】](https://raw.githubusercontent.com/CissusX/Markdown4Zhihu/master/Data/折纸鸟活动拆解/image-1.png)

![增加【技能】](https://raw.githubusercontent.com/CissusX/Markdown4Zhihu/master/Data/折纸鸟活动拆解/image-2.png)

通过增加【技能】机制，构建新的强化循环（如图3），使每次操作触发消除的次数大大增加，从而强化消除的爽快感

### 表现

![](https://raw.githubusercontent.com/CissusX/Markdown4Zhihu/master/Data/折纸鸟活动拆解/旋转动画+特效.png)

![](https://raw.githubusercontent.com/CissusX/Markdown4Zhihu/master/Data/折纸鸟活动拆解/特殊消除的特效.png)

![](https://raw.githubusercontent.com/CissusX/Markdown4Zhihu/master/Data/折纸鸟活动拆解/水果消除特效.png)

略。主要是动画与特效。



## 单局策略

### 不完全信息动态博弈

![](https://raw.githubusercontent.com/CissusX/Markdown4Zhihu/master/Data/折纸鸟活动拆解/image-3.png)

单回合对抗中，玩家需要基于对方行为（需要等待动画，有滞后性）和公开信息，基于以下目标做出最有利的决策：

* 保证仍有【濒死机会】/【生命值】，使自己不出局

* 在保证生存的情况下，保留尽可能多的【超级炸弹】



### 【超级炸弹】：串联三消和自走棋的核心元素

【超级炸弹】如何被设计为单局的核心资源（通过影响该回合扣除的生命值）？

* 机制1：玩家将继承前一轮的最终场地（【超级炸弹】）

* 机制2：关卡机制使得单局中后期能获得稳定数量的【超级炸弹】（需要启动成本）

* 机制3：【超级炸弹】只能通过玩家操作触发

* 机制4：【超级炸弹】x2 的单次消除收益较高且可预期

![](https://raw.githubusercontent.com/CissusX/Markdown4Zhihu/master/Data/折纸鸟活动拆解/image-6.png)



## 如何实现轻度休闲

### 直观性

* 通过“折纸小鸟的大小”反映对抗双方的战斗力

![](https://raw.githubusercontent.com/CissusX/Markdown4Zhihu/master/Data/折纸鸟活动拆解/大小1.png)

![](https://raw.githubusercontent.com/CissusX/Markdown4Zhihu/master/Data/折纸鸟活动拆解/大小2.png)



### 低复杂度

* 弱化三消玩法的策略思考：更好地适配自走棋模式的快节奏，降低难度适应玩家群体

* 较少的玩法元素（对比自走棋组卡）

### 易操作

* 只需要滑动屏幕交换水果



PS：作为多端适配游戏，键鼠和手柄的交互体验可能不如移动端触屏的交互体验



## 其他设计

* 【初始战斗力随回合数增加】机制，前期积攒血量优势在后期被缩小（平衡），加快后期节奏（类似大逃杀模式的缩圈机制）

* 超级炸弹数量-超级炸弹收益的平衡

  * 由于【超级炸弹只能通过交换消除】，积攒的超级炸弹会占据棋盘格，使得能被炸弹消除的水果数量变少，消除触发机制次数变少，产生的超级炸弹变少

