<p align="center">
	<a href="https://www.yingeo.com/"><img src="https://yingeo-img.oss-cn-shenzhen.aliyuncs.com/logo.svg"></a>
</p>
<p align="center">
	<strong>银歌开源收银系统 - 新一代开店软件，智慧零售，数字门店</strong>
</p>
<p align="center">
	👉 <a href="https://www.yingeo.com">https://www.yingeo.com</a> 👈
</p>

-------------------------------------------------------------------------------

## 📚 项目介绍

银歌收银系统（YINGEO-POS）是一套全平台综合型开源收银系统，领先SaaS云端技术收银系统，支持连锁，单店，联营等多种模式，线上线下联动，高度融合，到店、到家多生意形态。

银歌收银系统使用`Spring Cloud`和`Ant Design Vue`开发，集成`Spring Security`实现权限管理功能，是一套非常实用的web开发框架。

### 🎁 名称的由来

YINGEO = 银歌，是由原红河华云信息技术有限公司旗下分公司（深圳市银歌云技术有限公司）带领团队深度研发，凭借丰富的行业经验和敏锐的商业洞察，利用云计算、移动互联网、人工智能和物联网等先进技术，为企业提供POS-ERP软件、移动支付、全渠道营销及大数据运营等数字化服务，通过构建具有前瞻性的智慧商业模式，帮助企业实现商业价值的全面提升。


### 🍟 项目体验

- 银歌收银系统后台体验：[https://pos.yingeo.com/](https://pos.yingeo.com "银歌收银系统后台体验")
- 银歌收银系统android收银端下载体验：[https://www.yingeo.com/1.apk](https://www.yingeo.com/1.apk "android收银端下载")

### 🍎 项目特点

* 微信服务架构，支持分布式部署，高并发
* 提供http形式接口，提供各语言的`sdk`实现，方便对接
* 接口请求和响应数据采用签名机制，保证交易安全可靠
* 管理平台操作界面简洁、易用
* 支付平台到商户系统的订单通知使用MQ实现，保证了高可用，消息可达
* 使用`spring security`实现权限管理
* 前后端分离架构，方便二次开发
* 由原红河华信息技术云`银歌`团队开发，有着多年大型系统研发经验

## 🥞 系统架构

> 银歌收银系统系统架构图

![银歌系统架构图](https://www.yingeo.com/img/jg.png "银歌系统架构图")


> 核心技术栈

| 软件名称  | 描述 | 版本|
|---|---|---|
|Jdk | Java环境 | 1.8|
|Spring Cloud | 开发框架 | 2.4.5|
|Redis | 分布式缓存 | 3.2.8 或 高版本|
|MySQL | 数据库 | 5.7.X 或 8.0 高版本|
|MQ | 消息中间件 | ActiveMQ 或 RabbitMQ 或 RocketMQ|
|[Ant Design Vue](https://www.antdv.com/docs/vue/introduce-cn/) | Ant Design的Vue实现，前端开发使用 | 2.1.2|
|[MyBatis-Plus](https://mp.baomidou.com/) | MyBatis增强工具 | 3.4.2|
|[WxJava](https://gitee.com/binary/weixin-java-tools) | 微信开发Java SDK | 4.1.0|
|[Hutool](https://www.hutool.cn/) | Java工具类库 | 5.6.6|

> 项目结构

```lua
YINGEO-POS
├── eureka-server -- 注册中心
└── conf-server -- 配置中心
└── zuul-server -- 网关服务
└── es-server -- 店铺服务
├── commodity-server -- 商品服务
├── order-server -- 订单服务
├── pay-server -- 支付服务
├── push-server -- 推送服务
├── wechat-server -- 微信服务
└── alipay-server -- 支付宝服务
```

## 🍯 系统截图

`以下截图是从实际已完成功能界面截取,截图时间为：2021-12-12 12:12`

![银歌收银端演示界面](https://www.yingeo.com/img/syd1.png "银歌收银端演示界面")

![银歌收银端演示界面](https://www.yingeo.com/img/syd2.png "银歌收银端演示界面")

![银歌后台演示界面](https://www.yingeo.com/img/ybp.png "银歌后台演示界面")

![银歌后台演示界面](https://www.yingeo.com/img/sj.png "银歌后台演示界面")

![银歌后台演示界面](https://www.yingeo.com/img/spgl.png "银歌后台演示界面")

![银歌后台演示界面](https://www.yingeo.com/img/gys.png "银歌后台演示界面")

![银歌后台演示界面](https://www.yingeo.com/img/gys2.png "银歌后台演示界面")

![银歌掌柜演示界面](https://www.yingeo.com/img/zgd.jpg "银歌掌柜演示界面")

![银歌会员演示界面](https://www.yingeo.com/img/why.jpg "银歌会员演示界面")

## 🥪 关于我们
***
微信扫描下面二维码，关注官方公众号：银歌收银，获取更多精彩内容。

<img src="https://www.yingeo.com/img/gzh.jpg" alt="银歌收银公众号" title="银歌收银公众号" style="zoom: 20%;" />

微信扫描下方二维码，邀请进官方微信交流群（加好友备注：邀请进群或银歌收银咨询）。

<img src="https://www.yingeo.com/img/wx.jpg" alt="银歌微信交流群" title="银歌微信交流群" style="zoom: 25%;" />
