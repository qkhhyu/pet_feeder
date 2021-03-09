# 宠物喂食器开发计划书

This project is developed using Tuya SDK, which enables you to quickly develop branded apps connecting and controlling smart scenarios of many devices.

For more information, please check Tuya Developer Website

# 一、方案标题

宠物喂食器开发计划书

# 二、方案应用场景

地点：养有猫的家中；

功能：

1. 定时喂食，周定时循环，食量可选

* 上班期间，中午不在家，但是猫需要定时喂食，连接上涂鸦的平台，能够控制时间出粮和出粮的量；
* 一次设定后，可选择生效的时间，比如周一至周五生效，周末不需要生效，可以手动控制；

手机可操控，点击选择喂食份量

2. 余粮不足告警

* 设置称重传感器实时监测余量情况，当低于一定值是，上报平台，手机接收；
* 出粮出现故障时，上报平台，手机接收；

3. 可以看喂食记录

* 每次出粮和加粮情况，上报平台，包括余粮，本次出粮量，时间等，记录；

4. 语音控制

* 通过语音模块，设定开关，包括出粮的量，以及设定出粮的时间；
* 通过手机设备端，可以与喂食器通话，喊话，提醒猫咪吃猫粮；

5. 供电方式

* 支持电池和适配器供电方式，当停电时，亦能工作

# 三、开发计划

3月25前完成.

1. 3月14号前准备物料
2. 3月10-25日嵌入式开发、云开发
3. 3月25日前整体调试。
4. 3月28日前提交
