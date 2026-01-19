---
title: HybridApp
categories: Web开发
---


## HybridApp的定义

<p class="p-indent">
HybridApp(混合应用)指的是原生App+webview组合而成的App，运行在webview中的内容通常是html/js/css完成的h5应用。底座和webview会通过jsBridge形式传递数据或者调用接口。常见的开发框架如Cordova、Ionic、React Native、Flutter、Xamarin、uniapp等，还有一些企业使用自研的方式完成原生与web网页混合。 
</p>
<p class="p-indent">
该类应用通常应用在性能要求不高，渲染容错性高的地方。比如表单信息收集，文本信息传输以及轻量级的娱乐游戏。使用开发框架的时候，该类App开发成本很低，普通的web开发就可以上手应用开发，但涉及的原生应用的开发还是需要掌握对应的技能。
</p>

## 基于Andorid工程项目的混合App实操

1. 搭建AS开发环境

2. Android基础

3. 通过webview调用系统硬件

4. 原生应用向webview传递数据