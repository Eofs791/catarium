---
title: 友人帐
keywords: 链接
description: 友人帐
mine: /json/friends/mine.json
friend: /json/friends/friend.json
idol: /json/friends/idol.json
icon: i-ri-links-fill
random: true
nav: false
---
尝试让箱庭变得稍微热闹一些。
以下顺序随机，不分先后，总之都是我很喜欢的站点~

#### 小伙伴们
感谢你与我交换友链！
<YunLinks :links="frontmatter.friend" :random="frontmatter.random" />

#### 单向链接
仅收藏
<YunLinks :links="frontmatter.idol" :random="frontmatter.random" />

#### 一些我的站点
<YunLinks :links="frontmatter.mine" :random="false" />

#### 友链申请
[关于我](/about) | [关于本站](/about/site)

欢迎来交换友链，下方评论或发送邮件至`791sno@gmail.com`即可，感谢认可 > <
友链申请的要求与大部分博客相同，一般来者不拒

##### 我的博客信息：
```jsonc
// 前者为主站，非博客本体，所以两个地址均可~
"url": "https://saikai.moe" | "https://blog.saikai.moe",
"avatar": "https://avatars.githubusercontent.com/u/91895588?s=128",
"name": "Eofs",
"blog": "-arium",
"desc": "もしもここからまた出会えるのなら",
```

##### 友链交换格式
任意形式提供以下信息即可
```jsonc
"url": "博客URL",
"avatar": "头像URL"，
"blog": "博客名称",
"name": "（可选）博主名称，hover卡片时显示",
"desc": "（可选）博客描述",
"color": "（可选）链接卡片颜色"
```
