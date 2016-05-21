task32

任务三十二：表单（四）实现表单自动生成工厂【已经结束】

- 面向人群：

  初学者

- 难度：

  中等，但较为繁琐

### 重要说明

百度前端技术学院的课程任务是由百度前端工程师专为对前端不同掌握程度的同学设计。我们尽力保证课程内容的质量以及学习难度的合理性，但即使如此，真正决定课程效果的，还是你的每一次思考和实践。

课程多数题目的解决方案都不是唯一的，这和我们在实际工作中的情况也是一致的。因此，我们的要求不仅仅是实现设计稿的效果，更是要多去思考不同的解决方案，评估不同方案的优劣，然后使用在该场景下最优雅的方式去实现。那些最终没有被我们采纳的方案，同样也可以帮助我们学到很多知识。所以，我们列出的参考资料未必是实现需求所必须的。有的时候，实现题目的要求很简单，甚至参考资料里就有，但是背后的思考和亲手去实践却是任务最关键的一部分。在学习这些资料时，要多思考，多提问，多质疑。相信通过和小伙伴们的交流，能让你的学习事半功倍。

### 任务目的

- 加强对JavaScript的掌握
- 熟悉常用表单处理逻辑
- 学习如何模块如何设计，不同模块间如何尽量解耦

### 任务描述

- 实现以JavaScript对象的方式定义表单及验证规则

- 表单配置参考示例如下：（不需要一致，仅为参考）

  ```
      {
          label: '名称',                    // 表单标签
          type: 'input',                   // 表单类型
          validator: function () {...},    // 表单验证规
          rules: '必填，长度为4-16个字符',    // 填写规则提示
          success: '格式正确',              // 验证通过提示
          fail: '名称不能为空'               // 验证失败提示
      }
      
  ```

- 基于该配置项，实现一套逻辑，可以自动生成表单的展现、交互、验证

- 使用你制作的表单工厂，在一个页面上创建两套样式不同的表单

### 任务注意事项

- 实现中，尽可能考虑代码的可读性和可复用性
- 尽量时表单配置、生成、样式、验证几个逻辑之间的耦合度足够低
- 请注意代码风格的整齐、优雅
- 代码中含有必要的注释
- 不允许借助任何第三方组件库实现

### 任务协作建议

- 团队集中讨论，明确题目要求，保证队伍各自对题目要求认知一致
- 各自完成任务实践
- 交叉互相Review其他人的代码，建议每个人至少看一个同组队友的代码
- 相互讨论，最后合成一份组内最佳代码进行提交

### 在线学习参考资料

- [Web相关名词通俗解释](https://www.zhihu.com/question/22689579)
- [MDN HTML入门](https://developer.mozilla.org/zh-CN/docs/Web/Guide/HTML/Introduction)
- [慕课HTML+CSS基础教程视频](http://www.imooc.com/learn/9)
- [JavaScript 表单验证](http://www.w3school.com.cn/js/js_form_validation.asp)
- [HTML表单指南](https://developer.mozilla.org/zh-CN/docs/Web/Guide/HTML/Forms)

### 已提交任务的团队（*60*）

|                                          | 提交团队                                     | 提交时间        | 得分   |
| ---------------------------------------- | ---------------------------------------- | ----------- | ---- |
| [点击按钮进行评价](http://ife.baidu.com/review/detail?workId=3538) | 熊孩子进修班 ([团队详情](http://ife.baidu.com/group/profile?groupId=792)) | 03-24 13:58 | 0    |
| [点击按钮进行评价](http://ife.baidu.com/review/detail?workId=4514) | 组团来卖萌的 ([团队详情](http://ife.baidu.com/group/profile?groupId=137)) | 03-27 18:34 | 0    |
| [点击按钮进行评价](http://ife.baidu.com/review/detail?workId=4515) | frontendless ([团队详情](http://ife.baidu.com/group/profile?groupId=339)) | 03-27 18:35 | 0    |
| [点击按钮进行评价](http://ife.baidu.com/review/detail?workId=4543) | 前端热爱者 ([团队详情](http://ife.baidu.com/group/profile?groupId=203)) | 03-27 20:27 | 0    |
| [点击按钮进行评价](http://ife.baidu.com/review/detail?workId=5275) | Sublime Us ([团队详情](http://ife.baidu.com/group/profile?groupId=1617)) | 03-29 23:33 | 0    |
| [点击按钮进行评价](http://ife.baidu.com/review/detail?workId=5691) | hdu-fe ([团队详情](http://ife.baidu.com/group/profile?groupId=317)) | 03-31 14:29 | 0    |
| [点击按钮进行评价](http://ife.baidu.com/review/detail?workId=6329) | steel team ([团队详情](http://ife.baidu.com/group/profile?groupId=495)) | 04-02 13:28 | 0    |
| [点击按钮进行评价](http://ife.baidu.com/review/detail?workId=6461) | 菜虽菜，但不怂 ([团队详情](http://ife.baidu.com/group/profile?groupId=795)) | 04-02 18:05 | 0    |
| [点击按钮进行评价](http://ife.baidu.com/review/detail?workId=7416) | YUOL-Web-2014 ([团队详情](http://ife.baidu.com/group/profile?groupId=162)) | 04-03 21:03 | 0    |
| [点击按钮进行评价](http://ife.baidu.com/review/detail?workId=8020) | 「东成西就」 ([团队详情](http://ife.baidu.com/group/profile?groupId=1306)) | 04-04 10:13 | 0    |
| [点击按钮进行评价](http://ife.baidu.com/review/detail?workId=8143) | 艾欧尼亚 ([团队详情](http://ife.baidu.com/group/profile?groupId=198)) | 04-04 23:53 | 0    |
| [点击按钮进行评价](http://ife.baidu.com/review/detail?workId=8539) | 共产主义的前端接班人 ([团队详情](http://ife.baidu.com/group/profile?groupId=263)) | 04-08 13:51 | 0    |
| [点击按钮进行评价](http://ife.baidu.com/review/detail?workId=8733) | 前端小分队 ([团队详情](http://ife.baidu.com/group/profile?groupId=70)) | 04-10 13:44 | 0    |
| [点击按钮进行评价](http://ife.baidu.com/review/detail?workId=8890) | xilixili ([团队详情](http://ife.baidu.com/group/profile?groupId=1366)) | 04-12 10:26 | 0    |
| [点击按钮进行评价](http://ife.baidu.com/review/detail?workId=8999) | FELikeSea ([团队详情](http://ife.baidu.com/group/profile?groupId=250)) | 04-12 21:51 | 0    |
| [点击按钮进行评价](http://ife.baidu.com/review/detail?workId=9123) | 圣剑在我手上 ([团队详情](http://ife.baidu.com/group/profile?groupId=453)) | 04-13 18:07 | 0    |
| [点击按钮进行评价](http://ife.baidu.com/review/detail?workId=9182) | uestc ([团队详情](http://ife.baidu.com/group/profile?groupId=3455)) | 04-14 10:18 | 0    |
| [点击按钮进行评价](http://ife.baidu.com/review/detail?workId=9233) | Go ([团队详情](http://ife.baidu.com/group/profile?groupId=2529)) | 04-14 22:07 | 0    |
| [点击按钮进行评价](http://ife.baidu.com/review/detail?workId=9496) | LiveUrDreams ([团队详情](http://ife.baidu.com/group/profile?groupId=855)) | 04-18 13:18 | 0    |
| [点击按钮进行评价](http://ife.baidu.com/review/detail?workId=9606) | oho ([团队详情](http://ife.baidu.com/group/profile?groupId=1979)) | 04-19 00:37 | 0    |
| [点击按钮进行评价](http://ife.baidu.com/review/detail?workId=9627) | bupt小白 ([团队详情](http://ife.baidu.com/group/profile?groupId=2705)) | 04-19 10:53 | 0    |
| [点击按钮进行评价](http://ife.baidu.com/review/detail?workId=9754) | 前端学习小组 ([团队详情](http://ife.baidu.com/group/profile?groupId=1245)) | 04-20 09:18 | 0    |
| [点击按钮进行评价](http://ife.baidu.com/review/detail?workId=9783) | FEcoders ([团队详情](http://ife.baidu.com/group/profile?groupId=421)) | 04-20 13:04 | 0    |
| [点击按钮进行评价](http://ife.baidu.com/review/detail?workId=9788) | 浮生若梦 ([团队详情](http://ife.baidu.com/group/profile?groupId=843)) | 04-20 13:12 | 0    |
| [点击按钮进行评价](http://ife.baidu.com/review/detail?workId=9797) | 打怪升级 ([团队详情](http://ife.baidu.com/group/profile?groupId=1363)) | 04-20 13:56 | 0    |
| [点击按钮进行评价](http://ife.baidu.com/review/detail?workId=9802) | 我们的前端 ([团队详情](http://ife.baidu.com/group/profile?groupId=72)) | 04-20 14:25 | 0    |
| [点击按钮进行评价](http://ife.baidu.com/review/detail?workId=9842) | 大大泡泡糖 ([团队详情](http://ife.baidu.com/group/profile?groupId=3945)) | 04-20 16:08 | 0    |
| [点击按钮进行评价](http://ife.baidu.com/review/detail?workId=9891) | D&C ([团队详情](http://ife.baidu.com/group/profile?groupId=3285)) | 04-20 19:56 | 0    |
| [点击按钮进行评价](http://ife.baidu.com/review/detail?workId=9918) | IFE大喇叭小分队 ([团队详情](http://ife.baidu.com/group/profile?groupId=853)) | 04-20 20:31 | 0    |
| [点击按钮进行评价](http://ife.baidu.com/review/detail?workId=10005) | Struggle ([团队详情](http://ife.baidu.com/group/profile?groupId=4235)) | 04-20 23:28 | 0    |
| [点击按钮进行评价](http://ife.baidu.com/review/detail?workId=10018) | 男神 ([团队详情](http://ife.baidu.com/group/profile?groupId=1127)) | 04-20 23:30 | 0    |
| [点击按钮进行评价](http://ife.baidu.com/review/detail?workId=10072) | 名字都是浮云 ([团队详情](http://ife.baidu.com/group/profile?groupId=2164)) | 04-21 13:37 | 0    |
| [点击按钮进行评价](http://ife.baidu.com/review/detail?workId=10249) | 学三810 ([团队详情](http://ife.baidu.com/group/profile?groupId=3480)) | 04-21 20:12 | 0    |
| [点击按钮进行评价](http://ife.baidu.com/review/detail?workId=10273) | 前端noob ([团队详情](http://ife.baidu.com/group/profile?groupId=2541)) | 04-21 20:40 | 0    |
| [点击按钮进行评价](http://ife.baidu.com/review/detail?workId=10313) | Bug ([团队详情](http://ife.baidu.com/group/profile?groupId=1021)) | 04-21 20:57 | 0    |
| [点击按钮进行评价](http://ife.baidu.com/review/detail?workId=10350) | 京广小分队 ([团队详情](http://ife.baidu.com/group/profile?groupId=470)) | 04-21 21:28 | 0    |
| [点击按钮进行评价](http://ife.baidu.com/review/detail?workId=10363) | Hello World ([团队详情](http://ife.baidu.com/group/profile?groupId=92)) | 04-21 21:31 | 0    |
| [点击按钮进行评价](http://ife.baidu.com/review/detail?workId=10380) | ZLFE ([团队详情](http://ife.baidu.com/group/profile?groupId=1572)) | 04-21 21:40 | 0    |
| [点击按钮进行评价](http://ife.baidu.com/review/detail?workId=10407) | 程序员篮子 ([团队详情](http://ife.baidu.com/group/profile?groupId=1360)) | 04-21 22:02 | 0    |
| [点击按钮进行评价](http://ife.baidu.com/review/detail?workId=10451) | 我咬一口你听听脆不脆 ([团队详情](http://ife.baidu.com/group/profile?groupId=3105)) | 04-21 22:17 | 0    |
| [点击按钮进行评价](http://ife.baidu.com/review/detail?workId=10494) | 学前班5s ([团队详情](http://ife.baidu.com/group/profile?groupId=636)) | 04-21 22:32 | 0    |
| [点击按钮进行评价](http://ife.baidu.com/review/detail?workId=10504) | 成电小分队 ([团队详情](http://ife.baidu.com/group/profile?groupId=2316)) | 04-21 22:36 | 0    |
| [点击按钮进行评价](http://ife.baidu.com/review/detail?workId=10512) | sniper. 夜 ([团队详情](http://ife.baidu.com/group/profile?groupId=771)) | 04-21 22:40 | 0    |
| [点击按钮进行评价](http://ife.baidu.com/review/detail?workId=10585) | lfe ([团队详情](http://ife.baidu.com/group/profile?groupId=109)) | 04-21 23:08 | 0    |
| [点击按钮进行评价](http://ife.baidu.com/review/detail?workId=10600) | Web前端设计 ([团队详情](http://ife.baidu.com/group/profile?groupId=2021)) | 04-21 23:13 | 0    |
| [点击按钮进行评价](http://ife.baidu.com/review/detail?workId=10621) | 前端精英 ([团队详情](http://ife.baidu.com/group/profile?groupId=815)) | 04-21 23:15 | 0    |
| [点击按钮进行评价](http://ife.baidu.com/review/detail?workId=10653) | XD微客 ([团队详情](http://ife.baidu.com/group/profile?groupId=691)) | 04-21 23:30 | 0    |
| [点击按钮进行评价](http://ife.baidu.com/review/detail?workId=10657) | 捕虫战队 ([团队详情](http://ife.baidu.com/group/profile?groupId=2066)) | 04-21 23:32 | 0    |
| [点击按钮进行评价](http://ife.baidu.com/review/detail?workId=10662) | 滚键盘 ([团队详情](http://ife.baidu.com/group/profile?groupId=323)) | 04-21 23:35 | 0    |
| [点击按钮进行评价](http://ife.baidu.com/review/detail?workId=10700) | void(0) ([团队详情](http://ife.baidu.com/group/profile?groupId=816)) | 04-21 23:46 |      |

