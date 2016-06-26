# 第34期：Android App热补丁动态修复技术专题：深度对比微信、淘宝、支付宝、QQ空间热修复方案

## 专题日报

 当一个App发布之后，突然发现了一个严重bug需要进行紧急修复，这时候公司各方就会忙得焦头烂额：重新打包App、测试、向各个应用市场和渠道换包、提示用户升级、用户下载、覆盖安装。有时候仅仅是为了修改了一行代码，也要付出巨大的成本进行换包和重新发布。
 
 这时候就提出一个问题：有没有办法以补丁的方式动态修复紧急Bug，不再需要重新发布App，不再需要用户重新下载，覆盖安装？答案当然是有的，那就是最近涌现出来得热补丁方案，主要包括淘宝的Dexposed、支付宝的AndFix、QQ空间的ClassLoader、微信的Tinker、Nuwa五种。事实上，Android官方也使用热补丁技术实现Instant Run。它分为Hot Swap、Warm Swap与Cold Swap三种方式，大家可以参考英文介绍，也可以看参考文章中的翻译稿。最新的Instant App应该也是采用类似的原理，但是Google Play是不允许下发代码的，这个海外App需要注意一下。
 
 关于热补丁方案做了如下专题文章推荐，如果大家有更多好的文章，欢迎Pull

1、[	Dexposed、AndFix、ClassLoader等各大热补丁方案分析和比较](http://blog.zhaiyifan.cn/2015/11/20/HotPatchCompare/)

主要分析了Dexposed、AndFix、ClassLoader这三种方案的原理原理和各自的优缺点，感觉现在文章可以加入Instant Run和微信的Tinker热补丁方案了

2、[Android App热补丁动态修复技术介绍及QQ空间热补丁动态修复技术方案原理 ](https://mp.weixin.qq.com/s?__biz=MzI1MTA1MzM2Nw==&mid=400118620&idx=1&sn=b4fdd5055731290eef12ad0d17f39d4a)

Android QQ空间团队提出了独特的解决方法，该方案基于的是android dex分包方案的。具体大家直接点击原文查看

3、[微信Android热补丁实践演进之路](https://github.com/WeMobileDev/article/blob/master/%E5%BE%AE%E4%BF%A1Android%E7%83%AD%E8%A1%A5%E4%B8%81%E5%AE%9E%E8%B7%B5%E6%BC%94%E8%BF%9B%E4%B9%8B%E8%B7%AF.md#rd)

文章介绍了热补丁主要是让应用能够在无需重新安装的情况实现更新，帮助应用快速建立动态修复能力，同时对比了Dexposed、AndFix、QQ空间的ClassLoader 等等的业务局限然后根据微信自身的需求推出了微信自己的热补丁方案Tinker。

4、[Alibaba-AndFix Bug热修复框架原理及源码解析](http://blog.csdn.net/qxs965266509/article/details/49816007)

5、[Instant Run英文原文](https://medium.com/google-developers/instant-run-how-does-it-work-294a1633367f#.c088qhdxu)
   [Instant Run工作原理及用法](http://www.jianshu.com/p/2e23ba9ff14b)
   
6、[基于Nuwa实现Android自动化HotFix](http://www.jianshu.com/p/72c17fb76f21)
   [Android 热修复Nuwa的原理及Gradle插件源码解析](http://blog.csdn.net/sbsujjbcy/article/details/50812674)
   
7、[Buck exopackage 介绍](https://buckbuild.com/article/exopackage.html)

## 关注我们

目前已经超过**一万两千位**同学订阅了我们的日报，想要订阅[猛戳这里](http://list.qq.com/cgi-bin/qf_invite?id=d469993d2c888e971c0fbb2309c4d84256968386b126b967)


**Github ：**
[code_news](https://github.com/DiyCodes/code_news)：目前Watch 15，Star 140，Fork 32；

**官方微博：**
[优雅的程序员D](http://weibo.com/u/5891258264?topnav=1&wvr=6&topsug=1&is_all=1) ：关注人数 500 人；

**管理员微博：**
[安卓大王子](http://weibo.com/apkbus/) ：关注人数 32100 人；
[D_clock爱吃葱花](http://weibo.com/u/2480694892) ：关注人数 872 ；


**微信公众号：**
“优雅的程序员”微信号：diycodes，目前关注人数 723 人；
![](http://diycode.b0.upaiyun.com/photo/2016/f031fc25263f7294711038efa72ae579.jpg)



**如果你是一个爱写技术博客的童鞋，欢迎发稿时在微博@上小编哦，优秀的文章能让更多童鞋们看到！小编：**[D_clock爱吃葱花](http://weibo.com/2480694892/profile?rightmod=1&wvr=6&mod=personinfo&is_all=1)
