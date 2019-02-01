---
layout: post
title: Sublime Text 常用的 16 个 Sublime Text 快捷键
categories: 工具使用
description: Sublime Text 常用的 16 个 Sublime Text 快捷键
keywords: 快捷键, Sublime Text
---

> 本文由 [简悦 SimpRead](http://ksria.com/simpread/) 转码， 原文地址 http://www.mamicode.com/info-detail-651198.html <script type="text/javascript">mamicode_adload('title_before');</script>

# Sublime Text 常用的 16 个 Sublime Text 快捷键

时间：2015-05-25 00:52:19      阅读：66111      评论：0      收藏：0      <a id="infofavorite" class="acursorpointer" onclick="infofavorite_click();" data-ss1543215261="1">[点我收藏 +]</a> <script type="text/javascript">mamicode_adload('content_before');</script>

标签：

在我做了一次包含一些现场编码的演示后，一些观众问我是如何操作这么快。当然这里没有唯一的答案，答案是一堆简单的快捷键和大量的实践的组合。为了回应那些询问，我觉得有必要看看我每天想都不用想且使用的快捷键。

这里有一个 ~~15~~ 16 个快捷键的精选列表 (1 个自定义快捷键)，以 gif 动画展示，我每天使用。享受吧!

(译者注：原文所列快捷键均为 OS X 环境，为了方便 Windows 和 Linux 环境童鞋的学习，译者将备注 Windows 和 Linux 下对应的快捷键)

### 选择

*   选择一个选中项的下一个匹配项
*   选择一个选中项的所有匹配项
*   **选择与光标关联的开始和结束标签**
*   **选择容器内内容（新）**
*   **选择括号内的内容**

### 移动行和文本

*   **上移或下移行**
*   **复制行或选中项**
*   **增加和减少缩进**

### 剪切和删除，复制和粘贴

*   **剪切行或选中项**
*   **粘贴并保持缩进**
*   **用标签包裹行或选中项**
*   **移除未闭合的******容器**元素**

### 文本和数字操作

*   **计算数学表达式**
*   **递增和递减**
*   **大写和小写**

### 注释和对齐变量

*   注释选中项 / 行
*   AlignTab 自定义快捷键

**选择一个选中项的下一个匹配项: ? + D**

**（译者注：ctrl+d）**

把光标放在一个单词上，按下?+ D, 将选择这个单词。一直按住? 且按 D 多次，将选择当前选中项的下一个匹配项。通过按住?, 再按 D 三次, 将选择三个相同的文本。

![](http://ww1.sinaimg.cn/mw690/6941baebgw1eniih3wmwjg20fk089wge.gif)

**选择一个选中项的所有匹配项: CTRL + ? + G**

****（译者注：**alt+f3）**

和上面一样, 但它选择文件中的所有匹配项。小心使用这个, 因为它能选择一个文件中的所有匹配项. .

![](http://ww3.sinaimg.cn/mw690/6941baebgw1eniih3i5g7g20fk089mzj.gif)

**选择与光标关联的开始和结束标签:?+?+ K**

****（译者注：ctrl+shift+’）****

这是一个法宝。也许你希望所有属性保持不变, 但只是想选择标签。这个快捷键为你这样做, 会注意到你可以在一次操作多个标签。* 需要 Emmet 插件

![](http://ww4.sinaimg.cn/mw690/6941baebgw1eniih35ta2g20fk0890v0.gif)

**选择容器内内容: CTRL + D **

****（译者注：ctrl+shift+a）****

如果你把光标放在文本间再按下上面的键将选择文本, 就像?+ D。但是再次按下它，将选择父容器, 再按, 将选择父容器的父容器。* 需要 Emmet 插件

![](http://ww3.sinaimg.cn/mw690/6941baebgw1eniih2mxsxg20fk089dgr.gif)

**选择括号内的内容: ? + ? + Space**

******（译者注：**ctrl+shift+m**）******

这有助于选择括号之间的一切。同样适用于 CSS。

![](http://ww4.sinaimg.cn/mw690/6941baebgw1eniih2e60vg20fk089gml.gif)

**上移或下移行: CTRL + ? + ↑ 或 ↓**

**********（译者注：******ctrl+shift+****↑** 或 **↓**********）**********

![](http://ww4.sinaimg.cn/mw690/6941baebgw1eniih1tk8rg20fk089dgv.gif)

**复制行或选中项: ? + ? + D**

************（译者注：********ctrl+shift+d********************）如果你已经选中了文本, 它会复制你的选中项。否则, 把光标放在行上, 会复制整行。

![](http://ww2.sinaimg.cn/mw690/6941baebgw1eniih1hs73g20fk089dj4.gif)

**增加和减少缩进: ? + [或]**

****************（译者注：************ctrl+****[** 或 **]********************************）

![](http://ww1.sinaimg.cn/mw690/6941baebgw1eniih10ll0g20fk0893yx.gif)

**剪切行或选中项: ? + X**

******************（译者注：**************ctrl+x********************************）

剪切一行到你的剪切板，你可以粘贴到其他地方.

![](http://ww2.sinaimg.cn/mw690/6941baebgw1eniih0mwing20fk089q3m.gif)

**粘贴并保持缩进: ? + ? + V**

********************（译者注：****************ctrl+shift+v************************************）这是又一个我每次都用的快捷键。在 gif 中我显示了普通粘贴 (?+ V) 和缩进粘贴两种效果的对比。注意缩进如何排列。

![](http://ww1.sinaimg.cn/mw690/6941baebgw1eniih08w7hg20fk08977h.gif)

**用标签包裹行或选中项: CTRL + ? + W**

**********************（译者注：******************alt+shift+w****************************************）

使用标签包裹一行; 开始输入你想使用的标签, 你成功了.

![](http://ww2.sinaimg.cn/mw690/6941baebgw1eniigzytgkg20fk089q76.gif)

**移除未闭合的容器元素: ? + ’**

************************（译者注：********************ctrl+shift+;********************************************）这会移除与你的光标相关的父标签。对清除标记很有帮助。

![](http://ww4.sinaimg.cn/mw690/6941baebgw1eniigzdkybg20fk089mxw.gif)

**计算数学表达式: ? + ? + Y**

**************************（译者注：**********************ctrl+shift+y************************************************）我从未想过我会经常使用这个，但是确实很好用

![](http://ww4.sinaimg.cn/mw690/6941baebgw1eniigyz60zg20fk089js1.gif)

**递增和递减: ? + OPTION + ↑ or ↓, OPTION + ↑ or ↓**

**********************************（译者注：******************************alt+shift+****↑** 或 ******↓，**********ctrl+** **************↑** 或 ******↓**************************************************************************）

按住 **?** 将以 10 的步长改变数字, 不按住以 1 为步长. 同时注意到你不需要选择数字, Sublime Text 足够聪明到更新本行最近的数字.

![](http://ww4.sinaimg.cn/mw690/6941baebgw1eniigwnj1wg20fk089dha.gif)

**大写和小写: ? + K then U, ? + K then L**

**************************************（译者注：****************************ctrl+k+u,ctrl+k+l******************************************************************）

![](http://ww4.sinaimg.cn/mw690/6941baebgw1eniigw7rcqg20fk089t9z.gif)

**注释选中项 / 行: ? + /**

****************************************（译者注：******************************ctrl+/**********************************************************************）

这个在所有语言下都可用, 对行和选中项都可用.

![](http://ww1.sinaimg.cn/mw690/6941baebgw1eniigvpaw1g20fk0890ut.gif)

### 额外令人高兴的事情! 使用 AlignTab 自定义快捷键

上面的快捷键都是 Sublime Text 默认的快捷键, 但是你也可以添加你自己的自定义快捷键。以下示例应用 [AlignTab](https://github.com/randy3k/AlignTab) 插件使用 [三个自定义键绑定](https://gist.github.com/tommymarshall/9a1525bc79508ef9ec6e) 来基于 => ,=, 和: 进行内容垂直对齐。因为我工作中主要使用 JavaScript 和 PHP, 这些绑定对于几乎我需要的每一个场景都有用, 但是你可以用任何你想要的字符进行垂直对齐。

在你自己的编辑器实现下面 gif 的效果, 只需安装 [AlignTab](http://github.com/randy3k/AlignTab), , 添加[自定义绑定](http://gist.github.com/tommymarshall/9a1525bc79508ef9ec6e)到您的[自定义键绑定文件](http://cl.ly/image/0P3e2k1x131n)中, 选择一些代码, 并点击 **CTRL** + **?** + **.** 或 **;** 或 **=**.

![](http://ww2.sinaimg.cn/mw690/6941baebgw1eniigu56bhg20fk089mz4.gif)

### 结论

一旦你看到多行代码发生了一个改变, 通常有一个使用几个按键来实现改变的方法，而不是一个个地编辑它们。通过连续使用上面快捷键的组合去执行重复的或可预见的改变, 你可以大大提高你编码的速度。

这里是一个简短的 Gif, 包括选择所有匹配项, 复制链接的文本, 利用多行光标粘贴复制的文本, 并将该文本转换为小写。

![](http://ww4.sinaimg.cn/mw690/6941baebgw1eniigva9vlg20fk0fatae.gif)

**1 ：按住 shift+ctrl 然后按←或→可快速选中一行中的某一部分，相当于双击鼠标选中。**

当你想在代码末尾加注释的话，这个方法很好用

输入文字 -》光标移到文字末尾 -》按住 shift+ctrl+←便会选中文字 -》其他操作：删除、注释（ctrl+/）等等。

![](http://www.cr173.com/up/2014-4/13985204762782773.png)

![](http://www.cr173.com/up/2014-4/13985205125494474.png)

**2：shift+ctrl 键组合 +↑↓。可实现类似鼠标选中之后移动的效果。**

光标定位到某一行 -》ctrl+shift+↑↓，上下移动一行。

选中之后 -》ctrl+shift+↑↓，上下移动选中区域。

**3：ctrl+shift+d：快速复制光标所在的一整行，并复制到该行之前。**

![](http://www.cr173.com/up/2014-4/13985205446517164.png)

![](http://www.cr173.com/up/2014-4/13985205574639326.png)

**4：ctrl+shift+m：选中花括号里面的全部内容不包括 {}。**

![](http://www.cr173.com/up/2014-4/13985205944612684.png)

**5：ctrl+shift+A：选中标签内的内容不包括标签，继续按会继续往上一层选择。**

可利用这个功能实时结构预览。

![](http://www.cr173.com/up/2014-4/13985204421253751.png)

再按

![](http://www.cr173.com/up/2014-4/13985203933758634.png)

**6：Ctrl+Shift+Enter 光标前插入行。**

很好用，当因为某种原因需要插入新行的时候，使用它并且自带的缩进功能不需要使用 tap 键。

**6：Ctrl+Shift+[ 折叠代码**

**Ctrl+Shift+] 展开代码**

在 HTML 语法格式中，可实现标签的折叠，很方便的查看标签布局结构。

7：Ctrl+Shift+K  删除整行

8：ctrl+shift+p  打开命令面板

**Sublime Text 快捷键：**

Ctrl+Shift+P：打开命令面板

Ctrl+P：搜索项目中的文件

Ctrl+G：跳转到第几行

Ctrl+W：关闭当前打开文件

Ctrl+Shift+W：关闭所有打开文件

Ctrl+Shift+V：粘贴并格式化

Ctrl+D：选择单词，重复可增加选择下一个相同的单词

Ctrl+L：选择行，重复可依次增加选择下一行

Ctrl+Shift+L：选择多行

Ctrl+Shift+Enter：在当前行前插入新行

Ctrl+X：删除当前行

Ctrl+M：跳转到对应括号

Ctrl+U：软撤销，撤销光标位置

Ctrl+J：选择标签内容

Ctrl+F：查找内容

Ctrl+Shift+F：查找并替换

Ctrl+H：替换

Ctrl+R：前往 method

Ctrl+N：新建窗口

Ctrl+K+B：开关侧栏

Ctrl+Shift+M：选中当前括号内容，重复可选着括号本身

Ctrl+F2：设置 / 删除标记

Ctrl+/：注释当前行

Ctrl+Shift+/：当前位置插入注释

Ctrl+Alt+/：块注释，并 Focus 到首行，写注释说明用的

Ctrl+Shift+A：选择当前标签前后，修改标签用的

F11：全屏

Shift+F11：全屏免打扰模式，只编辑当前文件

Alt+F3：选择所有相同的词

Alt+.：闭合标签

Alt+Shift + 数字：分屏显示

Alt + 数字：切换打开第 N 个文件

Shift + 右键拖动：光标多不，用来更改或插入列内容

鼠标的前进后退键可切换 Tab 文件

按 Ctrl，依次点击或选取，可需要编辑的多个位置

按 Ctrl+Shift + 上下键，可替换行

[Sublime Text 常用的 16 个 Sublime Text 快捷键](http://www.mamicode.com/info-detail-651198.html "Sublime Text 常用的16 个 Sublime Text 快捷键,mamicode.com")

标签：

原文地址：http://www.cnblogs.com/fan-fan/p/4526817.html

踩 (5) 赞 (62)     举报 <script type="text/javascript">mamicode_adload('content_after');</script> 评论 一句话评论（0） 共 0 条  

<form method="post" action="/ajaxjs/info_detail_commentadd.aspx"><textarea width:="" 680px;="" height:="" 120px;"=""></textarea>登录后才能评论！ <input type="button" class="mbtn1" value="登录" onclick="location.href='http://member.mamicode.com/login.aspx?returnUrl='+document.URL.replace(new RegExp('&amp;', 'g'), '(_)')"></form>

<script type="text/javascript">mamicode_adload('content_bottom');</script> <sr-plugin-count>共计：5781 个字</sr-plugin-count>
