---
title: 离线安装chrome商店的插件
id: 176
categories:
  - 零碎
date: 2016-07-18 10:38:24
tags:
---

想要安装谷歌插件，但是又没有网络怎么办？可以通过离线安装的方式进行安装。比如我现在在公司内网不能够上外网，我先在一台已经安装过了Visual-Event的电脑上找到它的ID,在chrome地址栏输入下面命令，打开chrome扩展程序页面,查看插件ID
<pre>chrome://extensions</pre>
[![QQ截图20160718103422](http://echo.chenbitao.com/wp-content/uploads/2016/07/QQ截图20160718103422.jpg)](http://echo.chenbitao.com/wp-content/uploads/2016/07/QQ截图20160718103422.jpg)

访问下面这个网址，直接用id搜索下载。
<pre>[http://chrome-extension-downloader.com/](http://chrome-extension-downloader.com/)</pre>
[![QQ截图20160718103453](http://echo.chenbitao.com/wp-content/uploads/2016/07/QQ截图20160718103453.jpg)](http://echo.chenbitao.com/wp-content/uploads/2016/07/QQ截图20160718103453.jpg)

复制crx到内网，在chrome地址栏输入下面命令，打开chrome扩展程序页面
<pre>chrome://extensions</pre>
直接把下载的插件拖进去，点击确认就OK啦