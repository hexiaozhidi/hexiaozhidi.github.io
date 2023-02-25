---
layout: post
title: "遥控 AI 画师 - Intelligent Ecstatic Illustrator"
description: ""
tags: [AI, Web, 绘画]
---

<figure>
	<a href="/images/iei/iei.png"><img src="/images/iei/iei.png" alt=""></a>
	<figcaption>Intelligent Ecstatic Illustrator</figcaption>
</figure>

该项目部署在两台服务器上。服务器 A 基于 Django 实现了远程设置 AI 绘画参数、布置绘画任务、查看生成的图片等功能；服务器 B 基于 Stable Diffusion 和 WebUI 实现了向 A 轮询、接受并完成绘画任务、上传结果等功能。自动产粮不是梦想~

[GitHub](https://github.com/hexiaozhidi/IntelligentEcstaticIllustrator) [访问网站](https://m5.gs/aHJtYn)
