# 第217期：微信 SQLite 数据库修复实践

## 推荐

[微信 SQLite 数据库修复实践](https://www.diycode.cc/news/2403)

众所周知，微信在后台服务器不保存聊天记录，微信在移动客户端所有的聊天记录都存储在一个 SQLite 数据库中，一旦这个数据库损坏，将会丢失用户多年的聊天记录。而我们监控到现网的损坏率是0.02%，也就是每 1w 个用户就有 2 个会遇到数据库损坏。考虑到微信这么庞大的用户基数，这个损坏率就很严重了。更严重的是我们用的官方修复算法，修复成功率只有 30%。损坏率高，修复率低，这两个问题都需要我们着手解决。

## Android开发

[Android 中的 FORTIFY](https://www.diycode.cc/news/2397)

FORTIFY 是 Android 自 2012 年中以来一直配备的一项重要的安全功能。去年初，在将默认的 C/C++ 编译器从 GCC 迁移为 Clang 后，我们投入大量时间和精力，确保 FORTIFY 在 Clang 中的质量与之前相当。为做到这一点，我们重新设计了某些关键的 FORTIFY 功能的工作方式，具体将在文章中介绍。

[Matisse Android 图片选择器](https://www.diycode.cc/news/2399)

知乎开源的Android客户端图片选择器实现。

[简述Android中的Activity与Window关系](https://www.diycode.cc/news/2400)

AMS是Android系统最为核心的服务之一，其职责包括四大核心组件与进程的管理，而四大组件中Activity最为复杂。 其复杂在于需要跟用户进行UI交互(涉及Window)，WMS其主要职责便是窗口管理，还有跟App,SurfaceFlinger等 模块间相互协同工作。

[PonyMusic：基于OkHttp+Gson+Material Design设计的开源在线音乐播放器](https://github.com/wangchenyan/PonyMusic)

作者开源了自己的毕业设计作品。

[Tiny：媲美微信图片压缩的开源框架](https://github.com/Sunzxyong/Tiny)

![](https://diycode.b0.upaiyun.com/photo/2017/66903adb3fcda10b37fb528ee1f3eced.png)

## 课外话题

[微信成立搜索应用部，微信的搜索有哪些想象空间？](https://www.zhihu.com/question/58981321)

微信事业群下成立搜索应用部。负责微信的搜索业务、阅读推荐业务、AI技术研究及落地、微信数据平台建设和数据能力的应用。周颢担任微信事业群搜索应用部负责人，直接向张小龙汇报。

> 喜欢Diycode每日精选么？喜欢的话，不妨点个 **Star** 吧！

## 关注我们

| 社交账号  |  平台  | 关注人数 | 说明 |
| -------- | -------- | -------- | -------- |
| [Diycode每日精选](http://list.qq.com/cgi-bin/qf_invite?id=d469993d2c888e971c0fbb2309c4d84256968386b126b967)|   邮箱订阅  | 12000+ | 每日分享一次Android、iOS、Swfit技术干货  |
| [Code_News](https://github.com/DiyCodes/code_news) |    Github博客  |750+ | 每日邮件推送列表  |
| [优雅的程序员D](http://weibo.com/u/5891258264) |   微博  | 1500+ | 官方微博，每日分享开源信息  |
| [D_clock爱吃葱花](http://weibo.com/u/2480694892)  |   微博  | 1500+ | 日报发起人  |
|[YasicYu](http://weibo.com/3917305697)  |   微博  | 100+ | 日报发起人  |
|[安卓大王子](http://weibo.com/apkbus/)   |   微博  | 33000+ | 日报发起人  |

**微信公众号：**“优雅的程序员”，微信号：diycodes，目前关注人数 3000+ ；

![](http://upload-images.jianshu.io/upload_images/1846413-b42abfa70f909099.jpg?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

**欢迎童鞋们把优质的技术文章链接分享到 http://www.diycode.cc/news ，让更多童鞋们看到它们！**
