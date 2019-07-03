# Tinder即时通讯系统

持续时间：2019.07.01 ~ 2019.07.12

# 项目输出：

1. 软件开发计划(SDP)
2. 软件配置管理计划(SCMP)
3. 文档编号规则(DNR)
4. 软件文档规范(SDS)
5. 软件需求规格说明书(SRS)
6. 软件(结构)设计说明(SDD)
7. 数据库(顶层)设计说明(DBDD)
8. 软件测试说明(STD)
9. 软件测试报告(STR)
10. 软件用户手册(SUM)
11. 项目开发总结报告(PDSR)
12. 项目进度报告(PPR)
13. 会议纪要
14. 每日工作报告
15. 分工情况
16. 项目计划甘特图
17. 工程代码
18. 答辩PPT 

# 今日分工：07.03

## 当天提交：
- ~~负责小组：第三小组, 截止时间：17:00, 审核人：杜少恒~~
    - ~~完成情况：未完成~~
    - ~~任务内容：数据库相关类实现~~
- ~~负责人：陈子源, 截止时间：10:00, 审核人：王智超~~
    - ~~完成情况：已完成~~
    - ~~任务内容：沟通并重撰项目内容中的功能需求描述~~
- ~~负责人：王智超, 截止时间：09:20, 审核人：陈子源~~
    - ~~完成情况：已完成~~
    - ~~任务内容：沟通并添加第一小组的当日任务~~
- 负责人：第一小组, 截止时间：17:30, 审核人：王智超
    - 完成情况：未完成
    - 任务内容：和第二小组沟通合作完成个人和群的消息传输和文件传输功能
- 负责人：杜少恒, 截止时间：17:30, 审核人：陈子源
    - 完成情况：未完成
    - 任务内容：沟通并添加第三小组的次日任务
- ~~负责人：陈子源, 截止时间：15:00, 审核人：杜少恒~~
    - ~~完成情况：未完成~~
    - ~~任务内容：第一次会议纪要~~
- ~~负责人：陈子源, 截止时间：17:30, 审核人：胡品爵~~
    - ~~完成情况：未完成~~
    - ~~任务内容：第二次会议纪要~~
- ~~负责人：张涵, 截止时间：09:50, 审核人：陈子源~~
    - ~~完成情况：未完成~~
    - ~~任务内容：完成技术文档模板[doc/Management/...]~~
- ~~负责人：徐传旭, 截止时间：10:40, 审核人：陈子源~~
    - ~~完成情况：未完成~~
    - ~~任务内容：~~
        - ~~制作日工作报告模板、周工作报告模板和会议纪要模板[doc/Management/...]~~
        - ~~在文档编号规则里面增加周工作报告，修改日工作模板~~
        - ~~文件命名格式依据文档编号规则[doc/Process/1-项目计划研究阶段/...]~~
- ~~负责人：张莹, 截止时间：09:40, 审核人：陈子源~~
    - ~~完成情况：未完成~~
    - ~~任务内容：软件测试说明文档审查~~
- ~~负责人：刘文佳, 截止时间：10:00, 审核人：陈子源~~
    - ~~完成情况：未完成~~
    - ~~任务内容：~~
        - ~~制作分工计划模板，需要安装markdown编辑器~~
        - ~~昨天的文件命名格式依据文档编号规则[doc/Process/1-项目计划研究阶段/...]~~

## 非当天提交：
- 负责人：张涵, 截止时间：07.04 09:40, 审核人：陈子源
    - 任务内容：
        - 完成软件开发计划[doc/Process/1-项目计划研究阶段/...]
        - 文件命名格式依据文档编号规则[doc/Process/1-项目计划研究阶段/...]
- 负责人：张莹, 截止时间：07.04 10:00, 审核人：陈子源
    - 任务内容：
        - 完成软件配置管理计划[doc/Process/1-项目计划研究阶段/...]
        - 文件命名格式依据文档编号规则[doc/Process/1-项目计划研究阶段/...]
- 负责人：徐传旭, 截止时间：07.04 10:20, 审核人：陈子源
    - 任务内容：
        - 与第三小组组长沟通合作，完成数据库(顶层)设计说明[doc/Process/3-设计阶段/...]
        - 文件命名格式依据文档编号规则[doc/Process/1-项目计划研究阶段/...]
- 负责人：刘文佳, 截止时间：07.04 10:40, 审核人：陈子源
    - 任务内容：
        - 与第一小组组长沟通合作，完成软件设计需求规格说明书[doc/Process/2-需求分析阶段/...]
        - 文件命名格式依据文档编号规则[doc/Process/1-项目计划研究阶段/...]
- 负责小组：第二小组, 截止时间：07.04 12:00, 审核人：胡品爵
    - 任务内容：群聊功能、管理员功能和个人信息修改功能

# 项目内容：

## 1. 项目简述
本软件为企业内部使用的即时通讯软件，具备文字消息、视频通话、语音通话、文件传输、群聊等功能。

## 2. 功能需求描述
### 2.1 注册登录
本通讯软件需要在注册登录后才能使用，登录时会通过服务器认证使用者的登录信息，仅允许通过注册的使用者登录并进行聊天。
(SRS需要用到的额外信息：不能重复登录)
### 2.2 文字传输
本通讯软件可以在企业内部网络下进行文字聊天，使用者可以在企业内部网络下对在线用户发起私聊。
### 2.3 部门管理
本通讯软件可以在管理员的维护下，对企业部门进行管理，能够实现分配职员、创建部门和修改部门等操作。
### 2.4 安全加密
本通讯软件本着用户隐私至上的原则，对用户所发送的消息和文件进行加密，保证用户信息的安全性。
### ~~2.3 视频通话~~
~~本通讯软件可以在企业内部网络下进行实时视频通话，使用者可以在企业内部网络下对在线用户发起一对一的视频聊天。~~
### ~~2.4 语音通话~~
~~本通讯软件可以在企业内部网络下进行实时语音通话，使用者可以在企业内部网络下对在线用户发起一对一的语音聊天。~~
### 2.5 文件传输
本通讯软件可以在企业内部网络下进行~~端到端的~~文件传输，使用者可以在企业内部网络下对在线用户发起一对一的文件传输请求，接收方客户端会对文件进行完整性检查，在确认文件完整性后保存到用户目录。
(优化细节：发文件时会在聊天框显示)
### 2.6 部门群聊
本通讯软件可以在企业内部网络下发起由各部门人员参与的文字通讯和文件传输。
(SRS需要用到的额外消息：群聊功能由管理员负责维护，用户不可给非自身所在的群聊发送消息)
### 2.7 聊天记录
本通讯软件可以存储使用者的聊天记录，并在继续上次会话的时候恢复到上一次的消息状态。
### 2.8 消息提醒
本通讯软件在用户收到消息的时候，可以自行将这些消息对话框置顶，并醒目显示，提示使用者查看。
### 2.9 个人信息修改
本通讯软件的使用者可以修改自己的密码、性别、年龄和个人简介信息。
### 2.10 名片展示
使用者可以将自己的个人信息(性别、年龄和个人简介)显示在使用者的个人名片上。
### 2.10 位置共享
本通讯软件的使用者可以发送自己当前的位置信息，消息的接收方能够~~在地图上~~看到位置发送者的定位信息。
### 2.11 统一用户管理
本通讯软件由管理员进行统一的账号注册和管理，使用者在获得登录用的用户名后可以修改个人信息、密码等信息。管理员有权限对用户进行创建、封禁、删号和重置密码等操作。管理员还肩负管理部门群聊的功能。
(SRS需要用到的额外信息：封禁时可以接受消息，不得发送消息)

