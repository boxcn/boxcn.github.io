---
layout: post
title: Jekyll本地环境故障及解决方法
categories: Tools
tags: Git Jekyll 
keywords: Jekyll,本地环境
tagline: Supporting tagline
---
**[Jekyll](http://jekyllrb.com/)** 是一款简单的博客系统，也可以说是一个静态网站生成器。她有一个模版目录，存放整个静态网站的模版文件，可以通过Liquid处理模版文件，把使用标记语言Textile或Markdown编写的内容文件，按照模版格式，转换成最终的静态网站页面。大名鼎鼎的GitHub Pages就是通过她实现的。

如何搭建本地环境，百度一下网上很多教程。不多介绍了。

之前自己在本地搭建了一套环境，不知道为什么，突然就不能正常运行了。出现很多莫名奇怪的问题，大概意思是Ruby解释器不能识别，Gem不正确。

难道是安装的软件版本、Gem自动更新了？。

根据错误原因，百度了一下解决办法，因为软件版本差异，最终没解决。

最后把Python、Ruby全卸载重新按照教程搭建才好的。

建议：如果遇到我类似的问题，可以尝试将软件换个安装目录。

希望对你有帮助，谢谢

