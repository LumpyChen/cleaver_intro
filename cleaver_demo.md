title: Cleaverjs的DEMO
author:
  name: Lumpy Chen
  email: lumpychen@outlook.com
  url: http://www.lumpychen.com
output: index.html
controls: true
progress: true
theme: select/cleaver-select-theme

--

# Cleaver指南

--

## Cleaver是什么？

Cleaver 是一个能根据一个 Markdown 文档**快速生成简易 PPT** 的 强大工具

>如果你已经有了一个 Markdown 的文档，30秒就可以制作成幻灯片。

[Github戳这里](https://github.com/jdan/cleaver)

-- 

## 厌倦了PPT？

![](http://b-i.forbesimg.com/carminegallo/files/2013/11/6845.strip_.zoom_-e1385136828745.gif)
--

## 它的优势之处在于：

1. 简易而快速
2. 如果你会用 Markdown ，你不需要额外学习
3. 生成静态网页，易于在线分享
4. 移动端同样易于浏览

--

## 使用Cleaver，你需要：

* Cleaver 基于 HTML5，你需要现代的浏览器
* Cleaver 需要 nodejs 的环境
* 使用 Cleaver 需要掌握 Markdown 的语法

--

## 安装Cleaver

1. 下载并安装 [node.js](https://nodejs.org/download/) （如果需要）
2. 终端里执行以下代码：

```shell
sudo npm install cleaver -g
```

等待其安装成功即可

--

## 使用Cleaver

 Cleaver 和普通的 Markdown 存在一点区别：

1. 需要在 Markdown 文件开头添加少量配置，[配置的API](https://github.com/jdan/cleaver/blob/master/docs/options.md)
2. 需要在正文中使用`--`来进行幻灯片的分页

比如这个幻灯片对应的 markdown 文件[源码在此]()

--

## 常用配置详解

|配置名|默认值|含义|
|:---:|:---:|:---:|
|title| - | 页面的总标题 |
|author| - | 作者信息（需详细配置）|
|theme| jdan/cleaver-retro | 采用主题样式 |
|output| basic.html | 生成的文件 |
|controls| true | 是否显示控制按钮 |

--

## 生成PPT效果的HTML

安装完 cleaver 之后，我们可以来使用它
在终端里面执行：

```shell
cleaver [你的md文件]
```
你就会得到你生成的 html 文件了

--

## 主题样式

 Cleaver 有[很多主题](https://github.com/jdan/cleaver/wiki/Theme-Inde://github.com/jdan/cleaver/wiki/Theme-Index)可供选择：

* jdan/cleaver-retro
* iamstarkov/cleaver-ribbon
* sudodoki/reveal-cleaver-theme
* sjaakvandenberg/cleaver-dark
* sjaakvandenberg/cleaver-light
* select/cleaver-select-theme

个人推荐最后一个

--

## 其它

幻灯片最后一页是自动生成的，会展示作者介绍

Cleaver 仍然还有一点排版上的问题，当然你可以贡献源码

总而言之，如果你需要进行不是一项特别复杂的汇报展示时，我们可以使用 Cleaver 代替 PowerPoint 


