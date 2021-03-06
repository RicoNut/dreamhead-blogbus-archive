---
layout: post
title: Hello，Moco（番外篇）
author: dreamhead
date: 2012-12-30 17:20:00 +0800
tags: [ 'Moco', '移动开发' ]
categories: [ 'Moco', '移动开发' ]
---

你可以创造一个东西，至于它怎样发展，那就不是你所能预期的了。

我写[Moco](https://github.com/dreamhead/moco)的初衷是为了简化集成，设计API是我最主要的关注点。Moco Runner是一个顺手完成的部分，让Moco可以独立运行起来。但每个人的关注点是不同的，有人把Moco用了起来，但是用法同我最初的设想完全不一样。

我知道的第一个Moco用户是我的一个同事，我在澳洲出差的那段时间给他介绍了Moco，他当时正要写一个iOS上的一个客户端。因为服务器端API尚未开发，更准确的说，连API应该是什么样子还没有人清楚。为了能够让他的iOS客户端能够顺利编写下去，他用Moco模拟了一个服务器，来什么请求，返回什么样的应答。于是，他高高兴兴地写起了他的客户端。在开发的过程中，他不断地调整着API的设计，因为只有通过实际的开发，他才知道自己真正想要的API是什么样子的。就这样，在服务器端代码还没有真正动手之前，他已经提供出一份真正满足他需要的API文档，剩下的就是服务器端照着这份API去实现了。

公司内部正与[立人图书馆](http://www.xctsg.org/)展开合作，帮助他们开发一个图书管理的手机端应用。你猜对了，这个项目里Moco也起到了作用。手机端应用在服务器端尚未就绪的情况下便启动了，他们用Moco模拟了一个服务器，这样，手机端应用就可以顺利地开始开发了。Moco新增了一个功能，当配置文件修改时，自动重新加载，这个功能就是由这个项目的人提出的。

从这两个例子里可以看到，在移动开发中，Moco起到了很大的作用：在服务器端开发完成之前，客户端通过Moco构建的模拟服务器就可以进行开发。

把Moco和移动开发结合起来，这是我设计Moco时从未有过的想法，这也是创造一个东西的魅力所在，你无法预期它会朝着哪个方向发展。近来不断地将Moco介绍给更多的人，越来越多的新想法也涌现了出来。有人想把它与前端开发结合起来，有人想让它反过来支持客户端的模拟。

我原以为Moco已经没什么好做的了，因为我想实现的东西都有了，现在看来，还停不下来。


