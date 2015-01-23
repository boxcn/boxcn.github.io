---
layout: post
title: Github简介
categories: Tools
tags: Git Github 分布式 Fork 开源
keywords: Github,开源
tagline: Supporting tagline
---
**[GitHub](https://github.com/ "Github官网")** is a web-based hosting service for projects that use the Gitrevision control system. It is written using ***[Ruby on Rails](http://baike.baidu.com/link?url=qBhCo53ZRao1p-YEm7mTn3gXqTilyuv46WkV2mqp4z6Uf-87c6iMQ34vBpHIScS0yFe1uCzWJ8kyz06GFOKMUK)*** by Logical Awesome developers Chris Wanstrath, PJ Hyett, and Tom Preston-Werner. GitHub offers both commercial plans and free accounts for open source projects. According to the Git User's Survey in 2009, GitHub is the most popular Git hosting site.

要了解 [GitHub](https://github.com/ "Github官网")，我们首先要知道 [Git](http://baike.baidu.com/subview/1531489/12032478.htm)，[Git](http://baike.baidu.com/subview/1531489/12032478.htm) 是管理代码的工具，写代码不是件轻松的事儿，一个人写的时候已经不轻松了，一群人写就更不轻松了，但这世界上很多事都是怎么不轻松怎么来的，大部分人都会 和别人一起写代码，问题在于，这么多人写一个东西，你今天写一点，我明天写一点，然后发现你写错了，又影响到了我前天写的，最后汇总的时候怎么查找错误？ 又在什么时候汇总？这些问题太多了，想想就觉得还是食物美好。为了让写代码这件事儿美好一点，我们有了一种名叫代码管理的东西，[Git](http://baike.baidu.com/subview/1531489/12032478.htm) 正是其中之一，我使用过的还有 SVN，但是今天我们只讲 [Git](http://baike.baidu.com/subview/1531489/12032478.htm)。

[Git](http://baike.baidu.com/subview/1531489/12032478.htm) 的核心思想是『分布式』，我们在服务器上面有一个『主仓库』，这里放的是拿得出台面的代码，我们也可以在自己的电脑上创建分支，这些分支由『主仓库』克隆 而来，然后我们就可以愉快的在自己的电脑上写代码了，写完代码可以同步在自己电脑的分支里面，当你觉得自己的代码拿得出台面，我们可以申请把自己的代码更 新到『主仓库』里面，一旦通过这样的审核，我们就对『主仓库』做了某种贡献，世界各地的杰出程序员不断的为一个项目的『主仓库』做贡献，让这个项目变得越 来越完善。

[GitHub](https://github.com/) 是运用 [Git](http://baike.baidu.com/subview/1531489/12032478.htm) 思想来工作的一个商业网站，所有开发者都可以在 [GitHub](https://github.com/) 上面为自己的项目创建一个『主仓库』，好的项目就像狼群中的小鲜肉一样，大量的开发者会把这个主仓库中的代码克隆到自己的『分仓库』去，用更性感的话来 说，就是『Fork』。

[Git](http://baike.baidu.com/subview/1531489/12032478.htm) 的方式的确很优雅，但问题在于，会有人愿意把自己辛辛苦苦的代码拿出来公布，并且让人 Fork 么？

会，不仅会，而且很多，[GitHub](https://github.com/) 有超过 140 万用户，你可能会撇撇嘴说那个啥啥社交软件都有 2000 万用户，区区 140 万算个啥。可是这 140 万用户几乎涵盖了这个世界上最优秀的开发者，我相信，你那个有 2000W 用户的社交软件的工程师，肯定也是用 [GitHub](https://github.com/) 的。任何项目，在 [GitHub](https://github.com/) 上面获得 fork 或 star，都意味着其它工程师对这个项目的认可，这比 100 个 QQ 空间的赞更有价值。
<img src="/assets/pictures/Tools/the_github_user.png">

为什么这些优秀的工程师会开源自己的项目？

因为开源是一种精神。

无数的软件开发者苦心积虑保护自己的代码不被破解，而还是被聪明绝顶的脚本小子破解了，但破解无数软件的脚本小子在接下来的破解中却傻眼了，因为这是开源的，不用破解也就破解了破解。

闭源意味着封闭，而开源则意味着开放，封闭很难进步，开放才会进步。开放让人类的智慧有聚集的可能，人类的智慧聚集起来不再是1+1=2，这是 开源的力量。闭源是一种排斥，而开源是包容，闭源是单打独斗，开源是同仇敌忾，闭源是敝帚自珍，开源是无私奉献，闭源是小富即安，开源是世界大同，闭源是 资本主义，开源是共产主义。

闭源让微软成帝国，让苹果成神话，但是，这是商业，如果没有技术的开源，这些商业的闭源也基本是无米之炊。商业需要闭源，而技术需要开源，利益需要闭源，而情怀需要开源。

开源是技术的『本善』。

我不排斥闭源，但是我赞美开源，就像我我忍受黑暗，但却心存光明一样，就像我顿顿吃素，却依然热爱肉食一样。当然，我没有顿顿吃素。

#### 其他参考资料： ####
1. [GotGitHub的介绍](http://www.worldhello.net/gotgithub/index.html "gotgithub")
2. [图解Git](http://marklodato.github.io/visual-git-guide/index-zh-cn.html "图解Git")
3. [Git - 简易指南(小清新风格，简单易懂)](http://rogerdudler.github.io/git-guide/index.zh.html "Git - 简易指南(小清新风格，简单易懂)")