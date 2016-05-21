任务二十七：行星与飞船（二）【已经结束】

- 面向人群：

  有一定JavaScript基础，希望学习或加强面向对象编程及设计模式相关知识的同学

- 难度：

  中等

### 重要说明

百度前端技术学院的课程任务是由百度前端工程师专为对前端不同掌握程度的同学设计。我们尽力保证课程内容的质量以及学习难度的合理性，但即使如此，真正决定课程效果的，还是你的每一次思考和实践。

课程多数题目的解决方案都不是唯一的，这和我们在实际工作中的情况也是一致的。因此，我们的要求不仅仅是实现设计稿的效果，更是要多去思考不同的解决方案，评估不同方案的优劣，然后使用在该场景下最优雅的方式去实现。那些最终没有被我们采纳的方案，同样也可以帮助我们学到很多知识。所以，我们列出的参考资料未必是实现需求所必须的。有的时候，实现题目的要求很简单，甚至参考资料里就有，但是背后的思考和亲手去实践却是任务最关键的一部分。在学习这些资料时，要多思考，多提问，多质疑。相信通过和小伙伴们的交流，能让你的学习事半功倍。

### 任务目的

- 练习JavaScript面向对象设计
- 实践一些基础的设计模式

### 任务描述

- 基于任务二十六，我们继续改善我们的任务
- 第一代宇宙飞船系统真是糟糕的实现，所以我们需要进行改进飞船自身，我们在几个部件进行了更多的组合可能性，在创建新飞船时可以自行选择，[如图](http://7xrp04.com1.z0.glb.clouddn.com/task_2_27_1.jpg)我们新增了几种动力系统，能够让飞船飞得更快，相应的能源消耗也会不同我们新增了集中能源系统，能够让飞船能量补充能源速度越快
- 接下来改进的是指令的传播问题
  - 我们发明了新一代的传播介质BUS，它的单次传播失败率降低到10%，传播速度提升到300ms，而且他增加了多次重试的功能，可以保证信息一定能够传递出去，请你实现这个可以通过多次重试保证在10%丢包率情况下顺利将信息传递出去的BUS传播介质
  - 但BUS有个弱点，就是无法直接传递JSON格式，它只能传递二进制码，但指挥官并不能够直接下达二进制编码指令，所以我们需要在行星上的发射器部分增加一个模块Adapter，把原来的指令格式翻译成二进制码。同时还需要在飞船的接收器部分增加一个Adapter，用来把二进制码翻译成原来能够理解的指令格式
  - 二进制码格式自定，可以参考的例子：前四位标示飞船编号，后四位标示具体指令（0001：开始飞行，0010：停止飞行，1100：自我销毁）

### 任务注意事项

- 实现功能的同时，请仔细学习JavaScript相关的知识
- 相关信息发送、接受等，建议在控制台中输出
- 任务说明中的各种数值说明只是参考，可能存在不合理性，可以自行设定
- 实现各种功能、模块时，不需要生搬硬套设计模式，但希望你就设计模式相关知识进行学习，并进行合理的借鉴运用
- 请注意代码风格的整齐、优雅
- 代码中含有必要的注释
- 允许使用jQuery等库，但不建议使用React、Angular等框架

### 任务协作建议

- 如果是各自工作，可以按以下方式：
  - 团队集中讨论，明确题目要求，保证队伍各自对题目要求认知一致
  - 各自完成任务实践
  - 交叉互相Review其他人的代码，建议每个人至少看一个同组队友的代码
  - 相互讨论，最后合成一份组内最佳代码进行提交
- 如果是分工工作（推荐），可以按以下模块切分
  - 飞船类
  - Adapter
  - BUS

### 在线学习参考资料

- [JavaScript Design Patterns](http://www.dofactory.com/javascript/design-patterns)
- [4 JavaScript Design Patterns You Should Know](https://scotch.io/bar-talk/4-javascript-design-patterns-you-should-know)
- [JavaScript Design Patterns](https://carldanley.com/javascript-design-patterns/)
- [Understanding Design Patterns in JavaScript](http://code.tutsplus.com/tutorials/understanding-design-patterns-in-javascript--net-25930)
- [在线电子书：Learning JavaScript Design Patterns](https://addyosmani.com/resources/essentialjsdesignpatterns/book/)
- [JavaScript 设计模式 – 第一部分： 单例模式、组合模式和外观模式](http://www.adobe.com/cn/devnet/html5/articles/javascript-design-patterns-pt1-singleton-composite-facade.html)
- [JavaScript 设计模式 – 第二部分： 适配器、装饰者和工厂模式](http://www.adobe.com/cn/devnet/html5/articles/javascript-design-patterns-pt2-adapter-decorator-factory.html)
- [JavaScript设计模式一：工厂模式和构造器模式](https://segmentfault.com/a/1190000002525792)
- [JavaScript 设计模式读书笔记(五)——工厂模式](https://segmentfault.com/a/1190000000491074)
- [Alloy JavaScript 设计模式](http://www.alloyteam.com/2012/10/common-javascript-design-patterns/)
- [常用的Javascript设计模式](http://blog.jobbole.com/29454/)
- [javascript常见的设计模式举例](http://blog.csdn.net/yingyiledi/article/details/26725795)
- [前端攻略：javascript 设计模式](http://www.cnblogs.com/Darren_code/archive/2011/08/31/JavascripDesignPatterns.html)

### 已提交任务的团队（*56*）

|                                          | 提交团队                                     | 提交时间        | 得分   |
| ---------------------------------------- | ---------------------------------------- | ----------- | ---- |
| [点击按钮进行评价](http://ife.baidu.com/review/detail?workId=4265) | sunshine ([团队详情](http://ife.baidu.com/group/profile?groupId=359)) | 03-26 18:54 | 0    |
| [点击按钮进行评价](http://ife.baidu.com/review/detail?workId=5022) | ccccc ([团队详情](http://ife.baidu.com/group/profile?groupId=2172)) | 03-29 10:45 | 0    |
| [点击按钮进行评价](http://ife.baidu.com/review/detail?workId=5378) | echo ([团队详情](http://ife.baidu.com/group/profile?groupId=831)) | 03-30 13:37 | 0    |
| [点击按钮进行评价](http://ife.baidu.com/review/detail?workId=5905) | 艾欧尼亚 ([团队详情](http://ife.baidu.com/group/profile?groupId=198)) | 04-01 00:58 | 0    |
| [点击按钮进行评价](http://ife.baidu.com/review/detail?workId=6337) | HashCoding ([团队详情](http://ife.baidu.com/group/profile?groupId=372)) | 04-02 13:37 | 0    |
| [点击按钮进行评价](http://ife.baidu.com/review/detail?workId=7477) | 前端泡沫组 ([团队详情](http://ife.baidu.com/group/profile?groupId=524)) | 04-03 21:34 | 0    |
| [点击按钮进行评价](http://ife.baidu.com/review/detail?workId=8109) | 贝尔多爸爸 ([团队详情](http://ife.baidu.com/group/profile?groupId=2926)) | 04-04 21:25 | 0    |
| [点击按钮进行评价](http://ife.baidu.com/review/detail?workId=8535) | xilixili ([团队详情](http://ife.baidu.com/group/profile?groupId=1366)) | 04-08 12:23 | 0    |
| [点击按钮进行评价](http://ife.baidu.com/review/detail?workId=8560) | 进击的前端菜鸟 ([团队详情](http://ife.baidu.com/group/profile?groupId=211)) | 04-08 16:45 | 0    |
| [点击按钮进行评价](http://ife.baidu.com/review/detail?workId=8966) | XD微客 ([团队详情](http://ife.baidu.com/group/profile?groupId=691)) | 04-12 18:35 | 0    |
| [点击按钮进行评价](http://ife.baidu.com/review/detail?workId=9086) | 组团来卖萌的 ([团队详情](http://ife.baidu.com/group/profile?groupId=137)) | 04-13 14:28 | 0    |
| [点击按钮进行评价](http://ife.baidu.com/review/detail?workId=9118) | 圣剑在我手上 ([团队详情](http://ife.baidu.com/group/profile?groupId=453)) | 04-13 18:05 | 0    |
| [点击按钮进行评价](http://ife.baidu.com/review/detail?workId=9224) | KB310 ([团队详情](http://ife.baidu.com/group/profile?groupId=3915)) | 04-14 21:10 | 0    |
| [点击按钮进行评价](http://ife.baidu.com/review/detail?workId=9298) | min ([团队详情](http://ife.baidu.com/group/profile?groupId=3229)) | 04-15 21:25 | 0    |
| [点击按钮进行评价](http://ife.baidu.com/review/detail?workId=9547) | 前端机智小能手 ([团队详情](http://ife.baidu.com/group/profile?groupId=1769)) | 04-18 17:47 | 0    |
| [点击按钮进行评价](http://ife.baidu.com/review/detail?workId=9553) | oho ([团队详情](http://ife.baidu.com/group/profile?groupId=1979)) | 04-18 18:09 | 0    |
| [点击按钮进行评价](http://ife.baidu.com/review/detail?workId=9559) | Rivers ([团队详情](http://ife.baidu.com/group/profile?groupId=3040)) | 04-18 18:59 | 0    |
| [点击按钮进行评价](http://ife.baidu.com/review/detail?workId=9622) | bupt小白 ([团队详情](http://ife.baidu.com/group/profile?groupId=2705)) | 04-19 10:50 | 0    |
| [点击按钮进行评价](http://ife.baidu.com/review/detail?workId=9641) | Avatar ([团队详情](http://ife.baidu.com/group/profile?groupId=1798)) | 04-19 11:19 | 0    |
| [点击按钮进行评价](http://ife.baidu.com/review/detail?workId=9772) | 夜猫分舵（18点后在） ([团队详情](http://ife.baidu.com/group/profile?groupId=3486)) | 04-20 11:52 | 0    |
| [点击按钮进行评价](http://ife.baidu.com/review/detail?workId=9775) | FEcoders ([团队详情](http://ife.baidu.com/group/profile?groupId=421)) | 04-20 12:29 | 0    |
| [点击按钮进行评价](http://ife.baidu.com/review/detail?workId=9837) | 大大泡泡糖 ([团队详情](http://ife.baidu.com/group/profile?groupId=3945)) | 04-20 16:07 | 0    |
| [点击按钮进行评价](http://ife.baidu.com/review/detail?workId=9868) | LiveUrDreams ([团队详情](http://ife.baidu.com/group/profile?groupId=855)) | 04-20 17:01 | 0    |
| [点击按钮进行评价](http://ife.baidu.com/review/detail?workId=9938) | 广药前端小分队 ([团队详情](http://ife.baidu.com/group/profile?groupId=196)) | 04-20 21:30 | 0    |
| [点击按钮进行评价](http://ife.baidu.com/review/detail?workId=9965) | UESTC_FEDOG ([团队详情](http://ife.baidu.com/group/profile?groupId=289)) | 04-20 22:21 | 0    |
| [点击按钮进行评价](http://ife.baidu.com/review/detail?workId=9990) | Struggle ([团队详情](http://ife.baidu.com/group/profile?groupId=4235)) | 04-20 23:25 | 0    |
| [点击按钮进行评价](http://ife.baidu.com/review/detail?workId=10010) | 男神 ([团队详情](http://ife.baidu.com/group/profile?groupId=1127)) | 04-20 23:29 | 0    |
| [点击按钮进行评价](http://ife.baidu.com/review/detail?workId=10034) | 前端超级队 ([团队详情](http://ife.baidu.com/group/profile?groupId=432)) | 04-21 09:55 | 0    |
| [点击按钮进行评价](http://ife.baidu.com/review/detail?workId=10104) | 花样姐姐与野兽 ([团队详情](http://ife.baidu.com/group/profile?groupId=2700)) | 04-21 14:17 | 0    |
| [点击按钮进行评价](http://ife.baidu.com/review/detail?workId=10113) | ZRLLL ([团队详情](http://ife.baidu.com/group/profile?groupId=1041)) | 04-21 14:35 | 0    |
| [点击按钮进行评价](http://ife.baidu.com/review/detail?workId=10199) | 锟斤拷_西电 ([团队详情](http://ife.baidu.com/group/profile?groupId=2002)) | 04-21 18:38 | 0    |
| [点击按钮进行评价](http://ife.baidu.com/review/detail?workId=10308) | Bug ([团队详情](http://ife.baidu.com/group/profile?groupId=1021)) | 04-21 20:57 | 0    |
| [点击按钮进行评价](http://ife.baidu.com/review/detail?workId=10356) | Hello World ([团队详情](http://ife.baidu.com/group/profile?groupId=92)) | 04-21 21:29 | 0    |
| [点击按钮进行评价](http://ife.baidu.com/review/detail?workId=10372) | XJSE ([团队详情](http://ife.baidu.com/group/profile?groupId=2866)) | 04-21 21:36 | 0    |
| [点击按钮进行评价](http://ife.baidu.com/review/detail?workId=10391) | 对对队 ([团队详情](http://ife.baidu.com/group/profile?groupId=1836)) | 04-21 21:48 | 0    |
| [点击按钮进行评价](http://ife.baidu.com/review/detail?workId=10415) | 程序员篮子 ([团队详情](http://ife.baidu.com/group/profile?groupId=1360)) | 04-21 22:03 | 0    |
| [点击按钮进行评价](http://ife.baidu.com/review/detail?workId=10458) | 我咬一口你听听脆不脆 ([团队详情](http://ife.baidu.com/group/profile?groupId=3105)) | 04-21 22:19 | 0    |
| [点击按钮进行评价](http://ife.baidu.com/review/detail?workId=10490) | 成电小分队 ([团队详情](http://ife.baidu.com/group/profile?groupId=2316)) | 04-21 22:29 | 0    |
| [点击按钮进行评价](http://ife.baidu.com/review/detail?workId=10524) | Onload ([团队详情](http://ife.baidu.com/group/profile?groupId=582)) | 04-21 22:45 | 0    |
| [点击按钮进行评价](http://ife.baidu.com/review/detail?workId=10536) | 滑水冠军队 ([团队详情](http://ife.baidu.com/group/profile?groupId=190)) | 04-21 22:51 | 0    |
| [点击按钮进行评价](http://ife.baidu.com/review/detail?workId=10564) | IFE大喇叭小分队 ([团队详情](http://ife.baidu.com/group/profile?groupId=853)) | 04-21 23:04 | 0    |
| [点击按钮进行评价](http://ife.baidu.com/review/detail?workId=10577) | lfe ([团队详情](http://ife.baidu.com/group/profile?groupId=109)) | 04-21 23:07 | 0    |
| [点击按钮进行评价](http://ife.baidu.com/review/detail?workId=10581) | 幻灭的羔羊 ([团队详情](http://ife.baidu.com/group/profile?groupId=956)) | 04-21 23:08 | 0    |
| [点击按钮进行评价](http://ife.baidu.com/review/detail?workId=10606) | Just go ([团队详情](http://ife.baidu.com/group/profile?groupId=706)) | 04-21 23:14 | 0    |
| [点击按钮进行评价](http://ife.baidu.com/review/detail?workId=10613) | 前端精英 ([团队详情](http://ife.baidu.com/group/profile?groupId=815)) | 04-21 23:14 | 0    |
| [点击按钮进行评价](http://ife.baidu.com/review/detail?workId=10676) | code matters ([团队详情](http://ife.baidu.com/group/profile?groupId=2038)) | 04-21 23:41 | 0    |
| [点击按钮进行评价](http://ife.baidu.com/review/detail?workId=10682) | void(0) ([团队详情](http://ife.baidu.com/group/profile?groupId=816)) | 04-21 23:43 | 0    |
| [点击按钮进行评价](http://ife.baidu.com/review/detail?workId=10718) | OnePiece ([团队详情](http://ife.baidu.com/group/profile?groupId=1625)) | 04-21 23:48 | 0    |
| [点击按钮进行评价](http://ife.baidu.com/review/detail?workId=10726) | 学前班5s ([团队详情](http://ife.baidu.com/group/profile?groupId=636)) | 04-21 23:49 | 0    |
| [点击按钮进行评价](http://ife.baidu.com/review/detail?workId=10771) | sdu学线前端 ([团队详情](http://ife.baidu.com/group/profile?groupId=1500)) | 04-21 23:58 | 0    |

