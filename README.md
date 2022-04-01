# 洞天福地

准备建一个逐步取代豆瓣记录书影音的网站(至少是自我意义上的)。  
希望有人能在 Issues(在本页面左上角) 里帮忙写出意见和想法。    
关于这个页面的留言也可以发在 Issues 里。  
我宁愿有人批评，好过其实没有人care(没人care也许也能学习怎么做，不过没有激励的话可能学习周期会非常非常长)。  

### 站名  
网站名字可以改，本来想叫“洞天福地”，因为我准备把自己ID改成叫“福地蟆”。  
但是不上口，不好记，因此被@Moomo@alive.bar建议改成"洞天"。  
在《西游记》中符合三个标准可以被称为洞天。一是隐匿难寻，二是自成世界，三是平行空间。福地指的是神仙居住的地方或者幸福安乐的地方，对网站来说可能需要等洞天建成之后再看能不能做到。  
因此“洞天”暂时是符合网站定位的。  

### TODO  
- [x] 先做一个没有任何功能的首页。
- [ ] Backend
  - [ ] Start
  - [ ] Auth
  - [ ] Books
- [ ] i8n
- [ ] 基本帐号功能。
  - [x] 注册
  - [x] 登录
  - [ ] 帐号信息
    - [ ] 添加 OAuth 2  
    - [ ] Google  
    - [ ] GitHub  
    - [x] LocalStorage
- [ ] 个人主页
  - [ ] View
  - [ ] API
- [ ] 设置页面
  - [ ] Forms
  - [ ] API
- [ ] 数据表结构
  - [ ] 书
- [ ] 书，从没有页面到非常基本的有
  - [ ] Forms
  - [ ] API
- [ ] 影，从没有页面到非常基本的有
  - [ ] Forms
- [ ] 音，从没有页面到非常基本的有
  - [ ] Forms
- [ ] Demo https://my-awesome-project-a8052.web.app/  
- [ ] 租服务器然后部署。
- [ ] 基本的网站规则。
- [x] [Discord](https://discord.gg/C4Xah9SYmy) 
- [ ] Documentation

### Questions、部分解决方案
- **真的有人需要这样的网站吗？**
  - 有 例子:neodb.social read.land bookwyrm.social
- 怎么复刻豆列？书影音和豆列哪个优先做？
- 怎么获得捐款？
- 怎么进行一个长期不关闭的投票调查？
  - 语雀
- 首页应该长什么样子，需要有哪些基本的板块？
- 做不做广播？还是直接用长毛象？
  - 做， make it compatible with ActivityPub 
- 做不做小组？还是建Discourse/Discord?
  - 做
- Discord怎么用啊?(这个就不用发Issues了，直接在Discord里告诉我吧。)
- 有哪些参考网站？
  - Douban.com Write.as read.land
- 配色怎么选? 
  - http://mcg.mbitson.com/
  - https://material.io/guidelines/style/color.html#color-themes
- 如何记录
  - changelog应该怎么写？
  - 用Github来记录用户反馈和整理目标方向。
- 怎么改善缺少数据的问题？
  - Crawling, Marketing
- 怎么做评分系统？
- 怎么做推荐系统？
- 需要先学System Design吗
- 做不做问答板块？类似知乎那种？
  - 做
- ***我没有考虑到的问题是什么？***
- 不考虑用户内容的话，对一个系统来说，什么是有趣？  
- 需要做 RSS Feed 功能吗
- 需要了解反向代理吗
- 做不做艺术品展览品信息？
- 做不做论文信息？
- 做不做电子商品信息？
- 搜索怎么做?
- 数据表结构怎么设计?
- 使用语言?
  - 语言主要用中文，至少刚开始是中文
- 帐号验证
  - Auth2.0
  - Mastodon
  - 邮箱

### 命名困难
- 设置/偏好?
- 书籍/读书/图书/书?
- 电影/影视/视频/影?
- 音乐/歌曲/声音？
- 用户/成员/友邻/会员/居民/人？
- 消息/私信/站内信/洞邮？
- 书架/书单/列表/收藏？
- 微博/说说/状态/广播/嘟文？

### 暂无开发计划
- 全文搜索功能
- 图片、视频、音频等大量消耗服务器资源的内容
  
### 已听到的部分批评
- 缺少用户
  - 只要成本不高持续做就行了，做就有用户了 
- 缺少书籍数据
  - 导入
  - 持续做
- 完全替代豆瓣是不可能的
  - 持续做
- 帐号验证 OAuth 2  

### 临时社区
Discord  
https://discord.gg/C4Xah9SYmy  
Revolt  
https://app.revolt.chat/invite/caDfD7GZ  
需不需要Slack/飞书/Notion/Matrix?


### Changelog  
2021-09-09  
- 添加了bootstrap.min.js, header的toggle可以触发了    
- 前端添加了git  
- 设计了一下数据表结构 (version 0.0.1 ?)

2021-09-11
- 添加了LocalStorage刷新不会自动登出了  

2021-09-12  
- 添加了网页Footer  

2021-09-13
- 添加了用户页面和设置页面的占位符
- 修改了AuthService

2022-04-01
- 添加了小组和问答页面的占位符
