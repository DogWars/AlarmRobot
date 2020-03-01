# 微信提醒机器人
一个微信提醒机器人，你可以像给朋友发消息那样让它提醒你，相比传统的闹钟等提醒事项app微信提醒机器人具有以下优势
1. 打扰程度低，基于微信的轻量化提醒
2. 设置提醒流程简单，不需要单门找出一个待办提醒app 去设置提醒的内容、时间、铃声等等，只需要一句家常话就能创建一个提醒
3. 提醒频率可控，可以周期性提醒。比如每小时提醒我起来喝口水，每隔几天、几星期提醒

# 主要功能

目前功能主要有三个大的模块

- 日程提醒
- 好友提醒
- 功能提醒

# 部分截图

![](https://raw.githubusercontent.com/mortimer-cra/mypic/master/20200301232445.jpg)

![](https://raw.githubusercontent.com/mortimer-cra/mypic/master/20200301232652.jpg)

# 技术实现
- 项目基于python3.7
- 微信交互api借助 [ Mocha-L/WechatPCAPI ](https://github.com/Mocha-L/WechatPCAPI) 的微信API项目
- 任务调度基于apschedule
- 存储采用mongoDB
- 第三方功能由于涉及key等个人信息暂不上传，请自行搜索相关api请求即可

# 成品体验
![](https://raw.githubusercontent.com/mortimer-cra/mypic/master/20200301233929.jpg)

