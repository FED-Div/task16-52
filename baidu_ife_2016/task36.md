task36



任务三十六：听指令的小方块（四）【已经结束】

- 面向人群：

  有一定JavaScript基础

- 难度：

  高

### 重要说明

百度前端技术学院的课程任务是由百度前端工程师专为对前端不同掌握程度的同学设计。我们尽力保证课程内容的质量以及学习难度的合理性，但即使如此，真正决定课程效果的，还是你的每一次思考和实践。

课程多数题目的解决方案都不是唯一的，这和我们在实际工作中的情况也是一致的。因此，我们的要求不仅仅是实现设计稿的效果，更是要多去思考不同的解决方案，评估不同方案的优劣，然后使用在该场景下最优雅的方式去实现。那些最终没有被我们采纳的方案，同样也可以帮助我们学到很多知识。所以，我们列出的参考资料未必是实现需求所必须的。有的时候，实现题目的要求很简单，甚至参考资料里就有，但是背后的思考和亲手去实践却是任务最关键的一部分。在学习这些资料时，要多思考，多提问，多质疑。相信通过和小伙伴们的交流，能让你的学习事半功倍。

### 任务目的

- 练习JavaScript在DOM、字符串处理相关知识
- 利用JavaScript实践寻路相关算法

### 任务描述

- [如图](http://7xrp04.com1.z0.glb.clouddn.com/task_2_36_1.jpg)，新增元素“墙”，墙是正方形不可进入、越过的区域
- 新增修墙的指令，BUILD，执行指令时，会在当前方块面对的方向前修建一格墙壁，如果被指定修墙的地方超过边界墙或者已经有墙了，则取消修墙操作，并调用浏览器的console.log方法打印一个错误日志
- 新增粉刷的指令，BRU color，color是一个字符串，保持和css中颜色编码一致。执行指令时，如果当前方块蓝色边面对方向有紧相邻的墙，则将这个墙颜色改为参数颜色，如果没有，则通过调用浏览器的console.log方法，打印一个错误日志
- 尝试写一段代码，实现在空间内修建一个长长的五颜六色的墙或者有趣的图形
- 新增一个按钮，可以在空间内随机生成一些墙
- 增加一个指令：MOV TO x, y，会使得方块从当前位置移动到坐标为x，y的地方，移动过程中不能进入墙所在的地方，寻路算法请自行选择并实现，不做具体要求

### 任务注意事项

- 实现功能的同时，请仔细学习JavaScript相关的知识
- 请注意代码风格的整齐、优雅
- 代码中含有必要的注释
- 建议不使用任何第三方库、框架
- 寻路算法可以参考已有代码，但不建议直接引用现成的算法文件，最起码自己敲一遍
- 有余力的同学，可以实现多种寻路算法，并在MOV TO指令中增加算法的选择功能，比如MOV TO x,y BY xxx（算法标示）

### 任务协作建议

- 如果是各自工作，可以按以下方式：
  - 团队集中讨论，明确题目要求，保证队伍各自对题目要求认知一致
  - 各自完成任务实践
  - 交叉互相Review其他人的代码，建议每个人至少看一个同组队友的代码
  - 相互讨论，最后合成一份组内最佳代码进行提交
- 如果是分工工作（推荐），可以按以下模块切分
  - 墙相关的功能
  - 碰撞检测
  - 新指令的解析
  - 各种寻路算法，可以每人实现一个

### 在线学习参考资料

- [JavaScript入门篇](http://www.imooc.com/view/36)
- [MDN JavaScript](https://developer.mozilla.org/zh-CN/docs/Web/JavaScript)
- [各种寻路算法的可视化呈现](http://qiao.github.io/PathFinding.js/visual/)

### 已提交任务的团队（*47*）

|                                          | 提交团队                                     | 提交时间        | 得分   |
| ---------------------------------------- | ---------------------------------------- | ----------- | ---- |
| [点击按钮进行评价](http://ife.baidu.com/review/detail?workId=2811) | 黄桷垭车神交易天团 ([团队详情](http://ife.baidu.com/group/profile?groupId=1161)) | 03-22 20:02 | 0    |
| [点击按钮进行评价](http://ife.baidu.com/review/detail?workId=4417) | 没什么需求实现不了 ([团队详情](http://ife.baidu.com/group/profile?groupId=3099)) | 03-27 11:49 | 0    |
| [点击按钮进行评价](http://ife.baidu.com/review/detail?workId=8027) | 组团来卖萌的 ([团队详情](http://ife.baidu.com/group/profile?groupId=137)) | 04-04 10:43 | 0    |
| [点击按钮进行评价](http://ife.baidu.com/review/detail?workId=8239) | 五湖四海 ([团队详情](http://ife.baidu.com/group/profile?groupId=2085)) | 04-05 21:23 | 0    |
| [点击按钮进行评价](http://ife.baidu.com/review/detail?workId=8615) | lancelot ([团队详情](http://ife.baidu.com/group/profile?groupId=600)) | 04-09 13:57 | 0    |
| [点击按钮进行评价](http://ife.baidu.com/review/detail?workId=9127) | 圣剑在我手上 ([团队详情](http://ife.baidu.com/group/profile?groupId=453)) | 04-13 18:08 | 0    |
| [点击按钮进行评价](http://ife.baidu.com/review/detail?workId=9337) | xilixili ([团队详情](http://ife.baidu.com/group/profile?groupId=1366)) | 04-16 15:12 | 0    |
| [点击按钮进行评价](http://ife.baidu.com/review/detail?workId=9515) | pkufront ([团队详情](http://ife.baidu.com/group/profile?groupId=3320)) | 04-18 16:40 | 0    |
| [点击按钮进行评价](http://ife.baidu.com/review/detail?workId=9600) | vvvvip ([团队详情](http://ife.baidu.com/group/profile?groupId=392)) | 04-19 00:07 | 0    |
| [点击按钮进行评价](http://ife.baidu.com/review/detail?workId=9741) | 滑水冠军队 ([团队详情](http://ife.baidu.com/group/profile?groupId=190)) | 04-20 00:02 | 0    |
| [点击按钮进行评价](http://ife.baidu.com/review/detail?workId=9753) | 康村前端小分队 ([团队详情](http://ife.baidu.com/group/profile?groupId=1342)) | 04-20 09:18 | 0    |
| [点击按钮进行评价](http://ife.baidu.com/review/detail?workId=9806) | 我们的前端 ([团队详情](http://ife.baidu.com/group/profile?groupId=72)) | 04-20 14:28 | 0    |
| [点击按钮进行评价](http://ife.baidu.com/review/detail?workId=9878) | 大大泡泡糖 ([团队详情](http://ife.baidu.com/group/profile?groupId=3945)) | 04-20 17:53 | 0    |
| [点击按钮进行评价](http://ife.baidu.com/review/detail?workId=9895) | D&C ([团队详情](http://ife.baidu.com/group/profile?groupId=3285)) | 04-20 19:58 | 0    |
| [点击按钮进行评价](http://ife.baidu.com/review/detail?workId=9922) | IFE大喇叭小分队 ([团队详情](http://ife.baidu.com/group/profile?groupId=853)) | 04-20 20:33 | 0    |
| [点击按钮进行评价](http://ife.baidu.com/review/detail?workId=9983) | 南方柚子 ([团队详情](http://ife.baidu.com/group/profile?groupId=525)) | 04-20 23:21 | 0    |
| [点击按钮进行评价](http://ife.baidu.com/review/detail?workId=10015) | Struggle ([团队详情](http://ife.baidu.com/group/profile?groupId=4235)) | 04-20 23:30 | 0    |
| [点击按钮进行评价](http://ife.baidu.com/review/detail?workId=10022) | 男神 ([团队详情](http://ife.baidu.com/group/profile?groupId=1127)) | 04-20 23:31 | 0    |
| [点击按钮进行评价](http://ife.baidu.com/review/detail?workId=10066) | 名字都是浮云 ([团队详情](http://ife.baidu.com/group/profile?groupId=2164)) | 04-21 13:24 | 0    |
| [点击按钮进行评价](http://ife.baidu.com/review/detail?workId=10112) | 花样姐姐与野兽 ([团队详情](http://ife.baidu.com/group/profile?groupId=2700)) | 04-21 14:33 | 0    |
| [点击按钮进行评价](http://ife.baidu.com/review/detail?workId=10179) | 前端泡沫组 ([团队详情](http://ife.baidu.com/group/profile?groupId=524)) | 04-21 17:49 | 0    |
| [点击按钮进行评价](http://ife.baidu.com/review/detail?workId=10266) | XD微客 ([团队详情](http://ife.baidu.com/group/profile?groupId=691)) | 04-21 20:29 | 0    |
| [点击按钮进行评价](http://ife.baidu.com/review/detail?workId=10318) | Bug ([团队详情](http://ife.baidu.com/group/profile?groupId=1021)) | 04-21 20:58 | 0    |
| [点击按钮进行评价](http://ife.baidu.com/review/detail?workId=10349) | oho ([团队详情](http://ife.baidu.com/group/profile?groupId=1979)) | 04-21 21:28 | 0    |
| [点击按钮进行评价](http://ife.baidu.com/review/detail?workId=10369) | Hello World ([团队详情](http://ife.baidu.com/group/profile?groupId=92)) | 04-21 21:32 | 0    |
| [点击按钮进行评价](http://ife.baidu.com/review/detail?workId=10413) | 程序员篮子 ([团队详情](http://ife.baidu.com/group/profile?groupId=1360)) | 04-21 22:02 | 0    |
| [点击按钮进行评价](http://ife.baidu.com/review/detail?workId=10442) | 我咬一口你听听脆不脆 ([团队详情](http://ife.baidu.com/group/profile?groupId=3105)) | 04-21 22:16 | 0    |
| [点击按钮进行评价](http://ife.baidu.com/review/detail?workId=10461) | 海贼兄弟 ([团队详情](http://ife.baidu.com/group/profile?groupId=4060)) | 04-21 22:19 | 0    |
| [点击按钮进行评价](http://ife.baidu.com/review/detail?workId=10519) | 成电小分队 ([团队详情](http://ife.baidu.com/group/profile?groupId=2316)) | 04-21 22:42 | 0    |
| [点击按钮进行评价](http://ife.baidu.com/review/detail?workId=10558) | SHSF ([团队详情](http://ife.baidu.com/group/profile?groupId=286)) | 04-21 23:02 | 0    |
| [点击按钮进行评价](http://ife.baidu.com/review/detail?workId=10590) | lfe ([团队详情](http://ife.baidu.com/group/profile?groupId=109)) | 04-21 23:09 | 0    |
| [点击按钮进行评价](http://ife.baidu.com/review/detail?workId=10593) | 幻灭的羔羊 ([团队详情](http://ife.baidu.com/group/profile?groupId=956)) | 04-21 23:10 | 0    |
| [点击按钮进行评价](http://ife.baidu.com/review/detail?workId=10622) | Just go ([团队详情](http://ife.baidu.com/group/profile?groupId=706)) | 04-21 23:15 | 0    |
| [点击按钮进行评价](http://ife.baidu.com/review/detail?workId=10626) | 前端精英 ([团队详情](http://ife.baidu.com/group/profile?groupId=815)) | 04-21 23:16 | 0    |
| [点击按钮进行评价](http://ife.baidu.com/review/detail?workId=10666) | 捕虫战队 ([团队详情](http://ife.baidu.com/group/profile?groupId=2066)) | 04-21 23:36 | 0    |
| [点击按钮进行评价](http://ife.baidu.com/review/detail?workId=10671) | code matters ([团队详情](http://ife.baidu.com/group/profile?groupId=2038)) | 04-21 23:40 | 0    |
| [点击按钮进行评价](http://ife.baidu.com/review/detail?workId=10730) | OnePiece ([团队详情](http://ife.baidu.com/group/profile?groupId=1625)) | 04-21 23:50 | 0    |
| [点击按钮进行评价](http://ife.baidu.com/review/detail?workId=10749) | 学前班5s ([团队详情](http://ife.baidu.com/group/profile?groupId=636)) | 04-21 23:55 | 0    |
| [点击按钮进行评价](http://ife.baidu.com/review/detail?workId=10757) | FELikeSea ([团队详情](http://ife.baidu.com/group/profile?groupId=250)) | 04-21 23:57 | 0    |
| [点击按钮进行评价](http://ife.baidu.com/review/detail?workId=3702) | Lollipop ([团队详情](http://ife.baidu.com/group/profile?groupId=1690)) | 03-24 20:43 | 8    |
| [点击按钮进行评价](http://ife.baidu.com/review/detail?workId=5563) | Sublime Us ([团队详情](http://ife.baidu.com/group/profile?groupId=1617)) | 03-30 23:46 | 2    |
| [点击按钮进行评价](http://ife.baidu.com/review/detail?workId=8846) | 艾欧尼亚 ([团队详情](http://ife.baidu.com/group/profile?groupId=198)) | 04-11 20:20 | 9    |
| [点击按钮进行评价](http://ife.baidu.com/review/detail?workId=9631) | bupt小白 ([团队详情](http://ife.baidu.com/group/profile?groupId=2705)) | 04-19 10:55 | 0    |
| [点击按钮进行评价](http://ife.baidu.com/review/detail?workId=4191) | DUT-FEDXXX ([团队详情](http://ife.baidu.com/group/profile?groupId=2879)) | 03-26 14:08 | 7    |
| [点击按钮进行评价](http://ife.baidu.com/review/detail?workId=4425) | PreWebDeveloper ([团队详情](http://ife.baidu.com/group/profile?groupId=2166)) | 03-27 12:15 | 9.5  |
| [点击按钮进行评价](http://ife.baidu.com/review/detail?workId=3014) | IFE.FrontEnd ([团队详情](http://ife.baidu.com/group/profile?groupId=925)) | 03-23 10:16 | 7.8  |
| [点击按钮进行评价](http://ife.baidu.com/review/detail?workId=3660) | 锟斤拷 ([团队详情](http://ife.baidu.com/group/profile?groupId=1304)) |             |      |

