## PC活动检测

#### 调用地址

http://api.live.bilibili.com/activity/v1/Raffle/check

需要 App Key 并验证登录状态(Access key)；要求应用申请弹幕权限

#### 参数

|字段|必选|传递方式|类型|说明|
|----|----|--------|----|----|
|cookie|true|GET|string|发布帐号(必须和 Cookies 帐号一致)|
|raffleId|true|GET|int|活动轮次|
