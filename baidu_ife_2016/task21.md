任务二十一：基础JavaScript练习（四）【已经结束】

- 面向人群：

  JavaScript初学者

- 难度：

  中等

### 重要说明

百度前端技术学院的课程任务是由百度前端工程师专为对前端不同掌握程度的同学设计。我们尽力保证课程内容的质量以及学习难度的合理性，但即使如此，真正决定课程效果的，还是你的每一次思考和实践。

课程多数题目的解决方案都不是唯一的，这和我们在实际工作中的情况也是一致的。因此，我们的要求不仅仅是实现设计稿的效果，更是要多去思考不同的解决方案，评估不同方案的优劣，然后使用在该场景下最优雅的方式去实现。那些最终没有被我们采纳的方案，同样也可以帮助我们学到很多知识。所以，我们列出的参考资料未必是实现需求所必须的。有的时候，实现题目的要求很简单，甚至参考资料里就有，但是背后的思考和亲手去实践却是任务最关键的一部分。在学习这些资料时，要多思考，多提问，多质疑。相信通过和小伙伴们的交流，能让你的学习事半功倍。

### 任务目的

- 学习与实践JavaScript的基本语法、语言特性
- 练习使用JavaScript实现拖拽功能

### 任务描述

- 基于任务20，将任务20的代码进行抽象、封装，然后在此基础上实现[如图](http://7xrp04.com1.z0.glb.clouddn.com/task_2_21_1.jpg)中的两个需求：Tag输入和兴趣爱好输入
- 如示例图上方，实现一个tag输入框
  - 要求遇到用户输入空格，逗号，回车时，都自动把当前输入的内容作为一个tag放在输入框下面。
  - Tag不能有重复的，遇到重复输入的Tag，自动忽视。
  - 每个Tag请做trim处理
  - 最多允许10个Tag，多于10个时，按照录入的先后顺序，把最前面的删掉
  - 当鼠标悬停在tag上时，tag前增加删除二字，点击tag可删除
- 如示例图下方，实现一个兴趣爱好输入的功能
  - 通过一个Textarea进行兴趣爱好的输入，可以通过用回车，逗号（全角半角均可），顿号，空格（全角半角、Tab等均可）等符号作为间隔。
  - 当点击“确认兴趣爱好”的按钮时，将textarea中的输入按照你设定的间隔符，拆解成一个个的爱好，显示在textarea下方
  - 爱好不能重复，所以在下方呈现前，需要做一个去重
  - 每个爱好内容需要做trim处理
  - 最多允许10个兴趣爱好，多于10个时，按照录入的先后顺序，把最前面的删掉

### 任务注意事项

- 实现简单功能的同时，请仔细学习JavaScript基本语法、事件、DOM相关的知识
- 示例图仅为参考，不需要完全一致
- 请注意代码风格的整齐、优雅
- 代码中含有必要的注释
- 建议不使用任何第三方库、框架

### 任务协作建议

- 团队集中讨论，明确题目要求，保证队伍各自对题目要求认知一致
- 各自完成任务实践
- 交叉互相Review其他人的代码，建议每个人至少看一个同组队友的代码
- 相互讨论，最后合成一份组内最佳代码进行提交

### 在线学习参考资料

- [JavaScript入门篇](http://www.imooc.com/view/36)

- [MDN JavaScript](https://developer.mozilla.org/zh-CN/docs/Web/JavaScript)

- http://v.youku.com/v_show/id_XNTM1NTQxMDMy.html http://v.youku.com/v_show/id_XNjIwNTEzMTA0.html?from=y1.2-1-176.3.3-2.1-1-1-2-0

### 已提交任务的团队（*150*）

|                                          | 提交团队                                     | 提交时间        | 得分   |
| ---------------------------------------- | ---------------------------------------- | ----------- | ---- |
| [点击按钮进行评价](http://ife.baidu.com/review/detail?workId=4364) | 「东成西就」 ([团队详情](http://ife.baidu.com/group/profile?groupId=1306)) | 03-27 00:07 | 0    |
| [点击按钮进行评价](http://ife.baidu.com/review/detail?workId=4458) | interstring ([团队详情](http://ife.baidu.com/group/profile?groupId=1502)) | 03-27 15:35 | 0    |
| [点击按钮进行评价](http://ife.baidu.com/review/detail?workId=4505) | 菜虽菜，但不怂 ([团队详情](http://ife.baidu.com/group/profile?groupId=795)) | 03-27 18:05 | 0    |
| [点击按钮进行评价](http://ife.baidu.com/review/detail?workId=4552) | TechFE ([团队详情](http://ife.baidu.com/group/profile?groupId=1792)) | 03-27 20:44 | 0    |
| [点击按钮进行评价](http://ife.baidu.com/review/detail?workId=4616) | 前端泡沫组 ([团队详情](http://ife.baidu.com/group/profile?groupId=524)) | 03-27 23:21 | 0    |
| [点击按钮进行评价](http://ife.baidu.com/review/detail?workId=4664) | Beethoven ([团队详情](http://ife.baidu.com/group/profile?groupId=605)) | 03-28 08:46 | 0    |
| [点击按钮进行评价](http://ife.baidu.com/review/detail?workId=4967) | FELikeSea ([团队详情](http://ife.baidu.com/group/profile?groupId=250)) | 03-29 00:15 | 0    |
| [点击按钮进行评价](http://ife.baidu.com/review/detail?workId=5053) | 湖工大在线 ([团队详情](http://ife.baidu.com/group/profile?groupId=491)) | 03-29 12:11 | 0    |
| [点击按钮进行评价](http://ife.baidu.com/review/detail?workId=5090) | 进击的前端菜鸟 ([团队详情](http://ife.baidu.com/group/profile?groupId=211)) | 03-29 15:00 | 0    |
| [点击按钮进行评价](http://ife.baidu.com/review/detail?workId=5281) | 夜猫分舵（18点后在） ([团队详情](http://ife.baidu.com/group/profile?groupId=3486)) | 03-30 00:01 | 0    |
| [点击按钮进行评价](http://ife.baidu.com/review/detail?workId=5535) | 大屁股啊 ([团队详情](http://ife.baidu.com/group/profile?groupId=378)) | 03-30 22:43 | 0    |
| [点击按钮进行评价](http://ife.baidu.com/review/detail?workId=5539) | BigFE ([团队详情](http://ife.baidu.com/group/profile?groupId=350)) | 03-30 23:09 | 0    |
| [点击按钮进行评价](http://ife.baidu.com/review/detail?workId=5656) | 五好青年 ([团队详情](http://ife.baidu.com/group/profile?groupId=2773)) | 03-31 13:11 | 0    |
| [点击按钮进行评价](http://ife.baidu.com/review/detail?workId=5660) | IT Studio ([团队详情](http://ife.baidu.com/group/profile?groupId=540)) | 03-31 13:17 | 0    |
| [点击按钮进行评价](http://ife.baidu.com/review/detail?workId=5672) | IFE.FrontEnd ([团队详情](http://ife.baidu.com/group/profile?groupId=925)) | 03-31 13:32 | 0    |
| [点击按钮进行评价](http://ife.baidu.com/review/detail?workId=5807) | xilixili ([团队详情](http://ife.baidu.com/group/profile?groupId=1366)) | 03-31 20:20 | 0    |
| [点击按钮进行评价](http://ife.baidu.com/review/detail?workId=5853) | EUXstudy ([团队详情](http://ife.baidu.com/group/profile?groupId=1157)) | 03-31 21:49 | 0    |
| [点击按钮进行评价](http://ife.baidu.com/review/detail?workId=5933) | 我好萌啊 ([团队详情](http://ife.baidu.com/group/profile?groupId=1109)) | 04-01 09:58 | 0    |
| [点击按钮进行评价](http://ife.baidu.com/review/detail?workId=5941) | 战舰起飞 ([团队详情](http://ife.baidu.com/group/profile?groupId=1468)) | 04-01 10:48 | 0    |
| [点击按钮进行评价](http://ife.baidu.com/review/detail?workId=6070) | KB310 ([团队详情](http://ife.baidu.com/group/profile?groupId=3915)) | 04-01 17:25 | 0    |
| [点击按钮进行评价](http://ife.baidu.com/review/detail?workId=6968) | MELOIFE ([团队详情](http://ife.baidu.com/group/profile?groupId=136)) | 04-03 12:59 | 0    |
| [点击按钮进行评价](http://ife.baidu.com/review/detail?workId=7008) | lancelot ([团队详情](http://ife.baidu.com/group/profile?groupId=600)) | 04-03 14:25 | 0    |
| [点击按钮进行评价](http://ife.baidu.com/review/detail?workId=7207) | Lollipop ([团队详情](http://ife.baidu.com/group/profile?groupId=1690)) | 04-03 18:27 | 0    |
| [点击按钮进行评价](http://ife.baidu.com/review/detail?workId=7340) | FEcoders ([团队详情](http://ife.baidu.com/group/profile?groupId=421)) | 04-03 20:17 | 0    |
| [点击按钮进行评价](http://ife.baidu.com/review/detail?workId=8065) | 南方柚子 ([团队详情](http://ife.baidu.com/group/profile?groupId=525)) | 04-04 16:15 | 0    |
| [点击按钮进行评价](http://ife.baidu.com/review/detail?workId=8082) | 小攻城狮 ([团队详情](http://ife.baidu.com/group/profile?groupId=2158)) | 04-04 18:36 | 0    |
| [点击按钮进行评价](http://ife.baidu.com/review/detail?workId=8083) | PX ([团队详情](http://ife.baidu.com/group/profile?groupId=2481)) | 04-04 18:41 | 0    |
| [点击按钮进行评价](http://ife.baidu.com/review/detail?workId=8102) | 哈工大阿法狗 ([团队详情](http://ife.baidu.com/group/profile?groupId=2831)) | 04-04 20:16 | 0    |
| [点击按钮进行评价](http://ife.baidu.com/review/detail?workId=8329) | IFE-dataV ([团队详情](http://ife.baidu.com/group/profile?groupId=234)) | 04-06 18:34 | 0    |
| [点击按钮进行评价](http://ife.baidu.com/review/detail?workId=8412) | 小明 ([团队详情](http://ife.baidu.com/group/profile?groupId=2615)) | 04-07 12:54 | 0    |
| [点击按钮进行评价](http://ife.baidu.com/review/detail?workId=8419) | 成电小分队 ([团队详情](http://ife.baidu.com/group/profile?groupId=2316)) | 04-07 13:38 | 0    |
| [点击按钮进行评价](http://ife.baidu.com/review/detail?workId=8422) | Web@BD ([团队详情](http://ife.baidu.com/group/profile?groupId=483)) | 04-07 13:41 | 0    |
| [点击按钮进行评价](http://ife.baidu.com/review/detail?workId=8491) | 笨鸟快快飞啊快快飞 ([团队详情](http://ife.baidu.com/group/profile?groupId=776)) | 04-07 22:31 | 0    |
| [点击按钮进行评价](http://ife.baidu.com/review/detail?workId=8516) | Game of Scripts ([团队详情](http://ife.baidu.com/group/profile?groupId=1517)) | 04-08 09:38 | 0    |
| [点击按钮进行评价](http://ife.baidu.com/review/detail?workId=8528) | 来自D版带着爱3队 ([团队详情](http://ife.baidu.com/group/profile?groupId=3877)) | 04-08 11:11 | 0    |
| [点击按钮进行评价](http://ife.baidu.com/review/detail?workId=8536) | 玩呀玩呀玩 ([团队详情](http://ife.baidu.com/group/profile?groupId=2744)) | 04-08 12:23 | 0    |
| [点击按钮进行评价](http://ife.baidu.com/review/detail?workId=8540) | 学三810 ([团队详情](http://ife.baidu.com/group/profile?groupId=3480)) | 04-08 13:58 | 0    |
| [点击按钮进行评价](http://ife.baidu.com/review/detail?workId=8585) | EJS ([团队详情](http://ife.baidu.com/group/profile?groupId=334)) | 04-08 22:28 | 0    |
| [点击按钮进行评价](http://ife.baidu.com/review/detail?workId=8611) | 丁丁 ([团队详情](http://ife.baidu.com/group/profile?groupId=2294)) | 04-09 12:32 | 0    |
| [点击按钮进行评价](http://ife.baidu.com/review/detail?workId=8624) | ccccc ([团队详情](http://ife.baidu.com/group/profile?groupId=2172)) | 04-09 14:56 | 0    |
| [点击按钮进行评价](http://ife.baidu.com/review/detail?workId=8630) | 前端怎么端 ([团队详情](http://ife.baidu.com/group/profile?groupId=3960)) | 04-09 15:18 | 0    |
| [点击按钮进行评价](http://ife.baidu.com/review/detail?workId=8644) | 路梦有点窄 ([团队详情](http://ife.baidu.com/group/profile?groupId=1563)) | 04-09 17:22 | 0    |
| [点击按钮进行评价](http://ife.baidu.com/review/detail?workId=8658) | UESTC_FEDOG ([团队详情](http://ife.baidu.com/group/profile?groupId=289)) | 04-09 18:59 | 0    |
| [点击按钮进行评价](http://ife.baidu.com/review/detail?workId=8679) | void(0) ([团队详情](http://ife.baidu.com/group/profile?groupId=816)) | 04-09 21:45 | 0    |
| [点击按钮进行评价](http://ife.baidu.com/review/detail?workId=8688) | win or out ([团队详情](http://ife.baidu.com/group/profile?groupId=3034)) | 04-10 07:40 | 0    |
| [点击按钮进行评价](http://ife.baidu.com/review/detail?workId=8746) | 秋名山老司机 ([团队详情](http://ife.baidu.com/group/profile?groupId=1153)) | 04-10 16:02 | 0    |
| [点击按钮进行评价](http://ife.baidu.com/review/detail?workId=8761) | BigFrontEnd ([团队详情](http://ife.baidu.com/group/profile?groupId=2526)) | 04-10 19:00 | 0    |
| [点击按钮进行评价](http://ife.baidu.com/review/detail?workId=8786) | 前端社区网团队 ([团队详情](http://ife.baidu.com/group/profile?groupId=2749)) | 04-11 00:54 | 0    |
| [点击按钮进行评价](http://ife.baidu.com/review/detail?workId=8805) | 前端梦之旅 ([团队详情](http://ife.baidu.com/group/profile?groupId=2498)) | 04-11 12:15 | 0    |
| [点击按钮进行评价](http://ife.baidu.com/review/detail?workId=8866) | sdu学线前端 ([团队详情](http://ife.baidu.com/group/profile?groupId=1500)) |             |      |

