## WorkTool

本安卓应用是一个依附于企业微信来运行的无人值守群管理机器人，非hook非侵入式，使用安卓系统原生支持的无障碍服务能力，手机无需Root，应用兼容99%的手机，长时间运行稳定且因为没有修改系统和软件所以理论上不存在被外挂监测和封号风险。
机器人支持查看问答记录，创建群、群管理，群发等功能，还支持接入自己的问答接口来全面接管机器人。

## 演示

**发送消息**

<img src="https://github.com/gallonyin/worktool/blob/master/images/send_message.gif"  height="500" width="280">
注：动图为机器人自动运行
更多演示看这里
https://worktool.apifox.cn/doc-840833


<img src="https://github.com/gallonyin/worktool/blob/master/images/chatgpt.png"  height="500" width="360">
机器人集成ChatGPT效果


## 兼容版本（重要）

⏬ 开源版兼容：企业微信 4.0.2 至 4.1.10  
⏬ 商业版兼容：企业微信 4.0.2 至 4.1.22（最新版本）、企业微信政务版

⚠️ 开源版本请修改包名后再自行编译测试

## 快速使用

💡 [快速入门文档](https://worktool.apifox.cn/)


1. 安卓端APP需要您自己提供一台手机（需可运行企业微信，手机型号和系统版本不限，本软件兼容99%的安卓手机 系统要求>=Android7.0）。
2. 如果您是开发者可以自行编译源码运行，建议改造包名或者集成到其他项目中使用；如果没有研发能力，我们更推荐您使用我们准备好的商业版WorkTool APP安装包：[点击下载](https://cdn.asrtts.cn/uploads/worktool/apk/worktool-latest.apk)
3. 任务调度平台公有云服务(SaaS)由官方提供，您只需要在您的业务中使用申请好的机器人id(即robot_id），调用对应的 API 完成对接即可。

如果您想使用自己开发的QA回调接口接收机器人收到的所有消息并定制回答，请参考[第三方QA回调接口规范(点击这里)](https://worktool.apifox.cn/doc-861677)开发接口，并在[机器人第三方QA配置(点击这里)](https://worktool.apifox.cn/api-22587884)提交您的机器人id和回调接口地址

## 文档

这里有所有详细的API文档和调用示例！！！

这里有所有详细的API文档和调用示例！！！

这里有所有详细的API文档和调用示例！！！

📝 https://worktool.apifox.cn/doc-850007

## 零代码集成

- 🤗 集简云: https://www.jijyun.cn/apps/detail/1000983

## 混淆

绝大部分代码均可以混淆，但由于使用的类库如okhttp、umeng不能混淆等情况，已经列在proguard-rules.pro当中，可以直接使用

#  Copyright

Apache License, Version 2.0

#  联系方式

- ⭐️ 官网: https://worktool.ymdyes.cn/
- ⭐️ 合作申请: https://admin.worktool.ymdyes.cn/form/consult (私有化/微信版/协议/定制)
- 💻 Email: gallonyin@163.com
- 🤗 QQ群: 技术交流、问题反馈
<img src="https://cdn.asrtts.cn/static/image/QQQRcode.png"  height="200" width="200">

# 版本更新

v2.8.1 2023-11-19 自动通过好友请求开关;执行队列去重算法优化

v2.8.0 2023-10-18 兼容企微4.1.10;其他已知问题优化

v2.7.4 2023-10-15 消息发送优化和准确率提升

v2.7.3 2023-10-12 发送消息优化

v2.7.2 2023-10-10 已知问题修复

v2.7.1 2023-09-11 优化兼容鸿蒙;优化获取群名;其他已知问题修复

<details>
<summary><b>往期更新</b></summary>

v2.7.0 2023-08-27 兼容企微4.1.9;其他已知问题优化

v2.6.8 2023-08-12 删除联系人;其他已知问题优化

v2.6.7 2023-07-31 修复房间类型错误;其他已知问题优化

v2.6.6 2023-07-25 优化消息接收;其他已知问题优化

v2.6.5 2023-07-14 优化发送文件;其他已知问题优化

v2.6.4 2023-06-28 修复发消息功能缺陷;其他已知问题优化

v2.6.3 2023-06-26 日志文件分享

v2.6.2 2023-06-25 增加防卡顿模式;自动删除已退出群;群信息保存通讯录;消息检查优化;其他已知问题修复

v2.6.1 2023-06-13 控件检索优化;其他已知问题修复

v2.6.0 2023-05-28 anr自动处理;其他已知问题修复

v2.5.9 2023-05-12 自动通过群邀请;拉人进群发送邀请;获取群聊全称;获取群二维码;其他已知问题修复

v2.5.8 2023-04-06 优化消息一致性检查;执行异常自动重试;兼容性更新;其他已知问题修复

v2.5.7 2023-03-15 自动通过群邀请;优化消息识别;异常环境监测;其他已知问题修复

v2.5.6 2023-02-06 兼容主流模拟器;其他已知缺陷修复

v2.5.5 2023-02-02 文件发送优化;新消息增强校验;其他已知缺陷修复

v2.5.4 2023-01-28 文件发送优化;消息列表识别优化;切换企业;其他已知缺陷修复

v2.5.3 2023-01-11 群模板兼容新版;消息类型识别优化;其他已知缺陷修复

v2.5.2 2023-01-05 返回首页缺陷修复

v2.5.1 2023-01-04 优化返回首页和回复速度;支持群二维码回调;其他已知缺陷修复

v2.4.2 2022-12-14 优化at;优化通过好友请求;其他已知缺陷修复

v2.4.1 2022-12-9 集成悬浮窗启停功能;房间检索优化;界面更新;其他已知缺陷修复

v2.4.0 2022-11-23 修改用户备注;添加待办;重要宕机缺陷修复

v2.3.3 2022-10-28 解散群;改群模板;其他已知问题优化

v2.3.1 2022-10-25 优化推送文件;特殊符号兼容;交互提示;其他已知问题修复

v2.3.0 2022-10-17 支持at多人;支持推送任意文件;支持群备注修改;交互提示优化;其他已知问题修复

v2.2.6 2022-09-16 优化搜索

v2.2.5 2022-09-15 主动加好友可改附言;移除[自动回复]前缀;群内回复@提醒;搜索更加精准;学校类企业兼容

v2.2.3 2022-08-26 兼容主动添加好友;文本匹配优化;其他已知问题优化

v2.2.1 2022-08-25 多控件类型兼容;兼容多版本系统;其他已知问题修复

v2.1.2 2022-08-18 多控件类型兼容;兼容多版本系统

v2.1 2022-08-17 真@提醒;获取未读消息优化;其他已知问题修复

v2.0 2022-08-11 全面兼容企业微信最新版本(4.0.12)和政务微信;控件搜索优化;已知问题修复

v1.3 2022-08-02 被动添加好友优化

v1.2 2022-07-11 内部群已读数过滤;避免群名重复创建;可回调获取群二维码;其他稳定性优化

v1.1 2022-06-20 大幅度提高系统稳定性和响应速度

v1.0 2022-05-27 首次可用版本更新
</details>


