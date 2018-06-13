## 微信小程序版豆瓣同城
### 写在前面
* 本项目作为本人入门小程序的学习，借助学习Github上的项目 [wechat-webapp-douban-location](https://github.com/bruintong/wechat-webapp-douban-location)

* 自我学习使用，无任何商业用途

### 概述
- 数据来源：[豆瓣同城API](https://developers.douban.com/wiki/?title=event_v2)
- 小程序请求豆瓣API报403解决方法(采用代理)
   - 原因是小程序把豆瓣公开的api给禁掉了
   - `https://api.douban.com` 代理为 `使用https://douban.uieee.com` 或 `http://t.yushu.im`

