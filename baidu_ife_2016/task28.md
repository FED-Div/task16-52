任务二十八：行星与飞船（三）【已经结束】

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

- 基于任务二十七，我们继续改善
- 第二代宇宙飞船系统进步了很多，但是我们依然无法知道飞船的能源消耗情况，可能有的时候我们发出开始飞行的指令，但飞船早就没有能量了，所以我们再次进行升级，这次我们需要增加一个飞船状态的监视系统
- 我们为每个飞船增加一个信号发射器，飞船会通过BUS系统定时（比如每秒）广播自己的飞行状态。发送的时候，我们通过已经安装在飞船上的Adapter把状态数据翻译成二进制码形式，把飞船自身标示，飞行状态，能量编码成一个16位的二进制串，前四位用于飞船自身标示，接下来4位表示飞行状态，0010为停止，0001为飞行，1100表示即将销毁，后八位用于记录飞船剩余能源百分比
- 行星上有一个信号接收器，用于通过BUS系统接受各个飞船发送过来的信号
- 当信号接收器接收到飞船信号后，会把信息传给数据处理中心（DC），数据处理中心依然是调用Adapter模块，把这些二进制数据转为对象格式存储在DC中
- 实现一个行星上的监视大屏幕[（如图）](http://7xrp04.com1.z0.glb.clouddn.com/task_2_28_1.jpg)，用来显示所有飞船的飞行状态及能源情况，当数据处理中心飞船数据发生变化时，它会相应在监视器上做出变化

### 任务注意事项

- 实现功能的同时，请仔细学习JavaScript相关的知识
- 相关信息发送、接受等，建议在控制台中输出
- 实现各种功能、模块时，不需要生搬硬套设计模式，但希望你就设计模式相关知识进行学习，并进行合理的借鉴运用
- 任务说明中的各种数值说明只是参考，可能存在不合理性，可以自行设定
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
  - 飞船发射器
  - Adapter调整
  - 数据处理中心
  - 监视大屏幕

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

### 已提交任务的团队（*52*）

|                                          | 提交团队                                     | 提交时间        | 得分   |
| ---------------------------------------- | ---------------------------------------- | ----------- | ---- |
| [点击按钮进行评价](http://ife.baidu.com/review/detail?workId=4510) | sunshine ([团队详情](http://ife.baidu.com/group/profile?groupId=359)) | 03-27 18:30 | 0    |
| [点击按钮进行评价](http://ife.baidu.com/review/detail?workId=4734) | 五个非洲人 ([团队详情](http://ife.baidu.com/group/profile?groupId=261)) | 03-28 13:49 | 0    |
| [点击按钮进行评价](http://ife.baidu.com/review/detail?workId=4948) | 使命必达（深圳） ([团队详情](http://ife.baidu.com/group/profile?groupId=567)) | 03-28 23:17 | 0    |
| [点击按钮进行评价](http://ife.baidu.com/review/detail?workId=6304) | We Are The World ([团队详情](http://ife.baidu.com/group/profile?groupId=202)) | 04-02 12:28 | 0    |
| [点击按钮进行评价](http://ife.baidu.com/review/detail?workId=6459) | HashCoding ([团队详情](http://ife.baidu.com/group/profile?groupId=372)) | 04-02 17:58 | 0    |
| [点击按钮进行评价](http://ife.baidu.com/review/detail?workId=7483) | 前端泡沫组 ([团队详情](http://ife.baidu.com/group/profile?groupId=524)) | 04-03 21:35 | 0    |
| [点击按钮进行评价](http://ife.baidu.com/review/detail?workId=8032) | DUT-FEDXXX ([团队详情](http://ife.baidu.com/group/profile?groupId=2879)) | 04-04 11:43 | 0    |
| [点击按钮进行评价](http://ife.baidu.com/review/detail?workId=8663) | 贝尔多爸爸 ([团队详情](http://ife.baidu.com/group/profile?groupId=2926)) | 04-09 19:48 | 0    |
| [点击按钮进行评价](http://ife.baidu.com/review/detail?workId=8670) | xilixili ([团队详情](http://ife.baidu.com/group/profile?groupId=1366)) | 04-09 20:01 | 0    |
| [点击按钮进行评价](http://ife.baidu.com/review/detail?workId=9035) | 进击的前端菜鸟 ([团队详情](http://ife.baidu.com/group/profile?groupId=211)) | 04-13 08:54 | 0    |
| [点击按钮进行评价](http://ife.baidu.com/review/detail?workId=9087) | 组团来卖萌的 ([团队详情](http://ife.baidu.com/group/profile?groupId=137)) | 04-13 14:29 | 0    |
| [点击按钮进行评价](http://ife.baidu.com/review/detail?workId=9119) | 圣剑在我手上 ([团队详情](http://ife.baidu.com/group/profile?groupId=453)) | 04-13 18:05 | 0    |
| [点击按钮进行评价](http://ife.baidu.com/review/detail?workId=9465) | 艾欧尼亚 ([团队详情](http://ife.baidu.com/group/profile?groupId=198)) | 04-17 21:13 | 0    |
| [点击按钮进行评价](http://ife.baidu.com/review/detail?workId=9554) | oho ([团队详情](http://ife.baidu.com/group/profile?groupId=1979)) | 04-18 18:14 | 0    |
| [点击按钮进行评价](http://ife.baidu.com/review/detail?workId=9560) | Rivers ([团队详情](http://ife.baidu.com/group/profile?groupId=3040)) | 04-18 18:59 | 0    |
| [点击按钮进行评价](http://ife.baidu.com/review/detail?workId=9623) | bupt小白 ([团队详情](http://ife.baidu.com/group/profile?groupId=2705)) | 04-19 10:51 | 0    |
| [点击按钮进行评价](http://ife.baidu.com/review/detail?workId=9642) | Avatar ([团队详情](http://ife.baidu.com/group/profile?groupId=1798)) | 04-19 11:19 | 0    |
| [点击按钮进行评价](http://ife.baidu.com/review/detail?workId=9735) | ZLFE ([团队详情](http://ife.baidu.com/group/profile?groupId=1572)) | 04-19 23:10 | 0    |
| [点击按钮进行评价](http://ife.baidu.com/review/detail?workId=9776) | FEcoders ([团队详情](http://ife.baidu.com/group/profile?groupId=421)) | 04-20 12:29 | 0    |
| [点击按钮进行评价](http://ife.baidu.com/review/detail?workId=9819) | KB310 ([团队详情](http://ife.baidu.com/group/profile?groupId=3915)) | 04-20 15:53 | 0    |
| [点击按钮进行评价](http://ife.baidu.com/review/detail?workId=9838) | 大大泡泡糖 ([团队详情](http://ife.baidu.com/group/profile?groupId=3945)) | 04-20 16:07 | 0    |
| [点击按钮进行评价](http://ife.baidu.com/review/detail?workId=9966) | UESTC_FEDOG ([团队详情](http://ife.baidu.com/group/profile?groupId=289)) | 04-20 22:23 | 0    |
| [点击按钮进行评价](http://ife.baidu.com/review/detail?workId=9992) | Struggle ([团队详情](http://ife.baidu.com/group/profile?groupId=4235)) | 04-20 23:26 | 0    |
| [点击按钮进行评价](http://ife.baidu.com/review/detail?workId=10011) | 男神 ([团队详情](http://ife.baidu.com/group/profile?groupId=1127)) | 04-20 23:29 | 0    |
| [点击按钮进行评价](http://ife.baidu.com/review/detail?workId=10027) | 617天团 ([团队详情](http://ife.baidu.com/group/profile?groupId=3316)) | 04-21 00:10 | 0    |
| [点击按钮进行评价](http://ife.baidu.com/review/detail?workId=10029) | 前端社区网团队 ([团队详情](http://ife.baidu.com/group/profile?groupId=2749)) | 04-21 02:02 | 0    |
| [点击按钮进行评价](http://ife.baidu.com/review/detail?workId=10089) | 前端超级队 ([团队详情](http://ife.baidu.com/group/profile?groupId=432)) | 04-21 13:56 | 0    |
| [点击按钮进行评价](http://ife.baidu.com/review/detail?workId=10105) | 花样姐姐与野兽 ([团队详情](http://ife.baidu.com/group/profile?groupId=2700)) | 04-21 14:19 | 0    |
| [点击按钮进行评价](http://ife.baidu.com/review/detail?workId=10309) | Bug ([团队详情](http://ife.baidu.com/group/profile?groupId=1021)) | 04-21 20:57 | 0    |
| [点击按钮进行评价](http://ife.baidu.com/review/detail?workId=10358) | Hello World ([团队详情](http://ife.baidu.com/group/profile?groupId=92)) | 04-21 21:30 | 0    |
| [点击按钮进行评价](http://ife.baidu.com/review/detail?workId=10373) | XJSE ([团队详情](http://ife.baidu.com/group/profile?groupId=2866)) | 04-21 21:37 | 0    |
| [点击按钮进行评价](http://ife.baidu.com/review/detail?workId=10392) | 对对队 ([团队详情](http://ife.baidu.com/group/profile?groupId=1836)) | 04-21 21:50 | 0    |
| [点击按钮进行评价](http://ife.baidu.com/review/detail?workId=10416) | 程序员篮子 ([团队详情](http://ife.baidu.com/group/profile?groupId=1360)) | 04-21 22:04 | 0    |
| [点击按钮进行评价](http://ife.baidu.com/review/detail?workId=10456) | 我咬一口你听听脆不脆 ([团队详情](http://ife.baidu.com/group/profile?groupId=3105)) | 04-21 22:18 | 0    |
| [点击按钮进行评价](http://ife.baidu.com/review/detail?workId=10491) | 成电小分队 ([团队详情](http://ife.baidu.com/group/profile?groupId=2316)) | 04-21 22:30 | 0    |
| [点击按钮进行评价](http://ife.baidu.com/review/detail?workId=10511) | sniper. 夜 ([团队详情](http://ife.baidu.com/group/profile?groupId=771)) | 04-21 22:40 | 0    |
| [点击按钮进行评价](http://ife.baidu.com/review/detail?workId=10526) | Onload ([团队详情](http://ife.baidu.com/group/profile?groupId=582)) | 04-21 22:46 | 0    |
| [点击按钮进行评价](http://ife.baidu.com/review/detail?workId=10567) | IFE大喇叭小分队 ([团队详情](http://ife.baidu.com/group/profile?groupId=853)) | 04-21 23:05 | 0    |
| [点击按钮进行评价](http://ife.baidu.com/review/detail?workId=10579) | lfe ([团队详情](http://ife.baidu.com/group/profile?groupId=109)) | 04-21 23:07 | 0    |
| [点击按钮进行评价](http://ife.baidu.com/review/detail?workId=10584) | 幻灭的羔羊 ([团队详情](http://ife.baidu.com/group/profile?groupId=956)) | 04-21 23:08 | 0    |
| [点击按钮进行评价](http://ife.baidu.com/review/detail?workId=10608) | Just go ([团队详情](http://ife.baidu.com/group/profile?groupId=706)) | 04-21 23:14 | 0    |
| [点击按钮进行评价](http://ife.baidu.com/review/detail?workId=10614) | 前端精英 ([团队详情](http://ife.baidu.com/group/profile?groupId=815)) | 04-21 23:15 | 0    |
| [点击按钮进行评价](http://ife.baidu.com/review/detail?workId=10628) | 滑水冠军队 ([团队详情](http://ife.baidu.com/group/profile?groupId=190)) | 04-21 23:19 | 0    |
| [点击按钮进行评价](http://ife.baidu.com/review/detail?workId=10678) | code matters ([团队详情](http://ife.baidu.com/group/profile?groupId=2038)) | 04-21 23:42 | 0    |
| [点击按钮进行评价](http://ife.baidu.com/review/detail?workId=10685) | void(0) ([团队详情](http://ife.baidu.com/group/profile?groupId=816)) | 04-21 23:44 | 0    |
| [点击按钮进行评价](http://ife.baidu.com/review/detail?workId=10719) | OnePiece ([团队详情](http://ife.baidu.com/group/profile?groupId=1625)) | 04-21 23:49 | 0    |
| [点击按钮进行评价](http://ife.baidu.com/review/detail?workId=10732) | 学前班5s ([团队详情](http://ife.baidu.com/group/profile?groupId=636)) | 04-21 23:50 | 0    |
| [点击按钮进行评价](http://ife.baidu.com/review/detail?workId=10774) | sdu学线前端 ([团队详情](http://ife.baidu.com/group/profile?groupId=1500)) | 04-21 23:59 | 0    |
| [点击按钮进行评价](http://ife.baidu.com/review/detail?workId=5260) | echo ([团队详情](http://ife.baidu.com/group/profile?groupId=831)) | 03-29 22:59 | 10   |
| [点击按钮进行评价](http://ife.baidu.com/review/detail?workId=8967) | XD微客 ([团队详情](http://ife.baidu.com/group/profile?groupId=691)) |             |      |

