# 无需复制 cookie,云函数托管掘金自动签到！

**直接部署后托管就行了，懂我意思吧**

文档地址：[https://juejin.cn/post/7102344275043549221](https://juejin.cn/post/7102344275043549221)

## 腾讯云函数收费了，项目已修改为 github actions 执行

1. Fork 仓库

2. 在仓库 `Settings->Secrets->Actions`中添加如下几个变量：

- EMAIL_USER 发送邮件的邮箱账号
- EMAIL_PASS 发送邮件的 token
- USER_MOBILE 掘金账号 - 手机号
- USER_PASSWORD 掘金账号 - 密码
- USER_EMAIL 接收通知的邮箱账号
