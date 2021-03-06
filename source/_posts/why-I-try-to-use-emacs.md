---
title: "为什么我开始尝试使用 Emacs"
date: 2017-03-04 22:46:54
tags: Emacs
---

作为使用了四年多, 装了超过一百个插件的"资深" vim 用户, 最近开始尝试使用 Emacs. 做出这个决定主要是出于以下几个方面的考虑:

<!--more-->

## Emacs 可以更方便地输入中文

打算以后都定期地写一些博客, 目前英文还太烂, 为了不打消写博客的积极性, 开始时还是写中文博客比较好. 但在 vim 里写中文的体验实在是太糟糕:

- 在 `Insert` 模式下你需要使用中文输入法.
- 要执行 vim 的一些跳转等操作时你需要进入到 `Normal` 模式, 而这时你的按键会先被输入法获取, 没法直接执行 vim 的命令, 需要先把输入法切换到英文模式.
- 当执行完 vim 的操作, 重新进行编辑时, 你还需要把输入法再切换成中文.

综上, 每次执行 vim 的操作你都需要切换两次输入法! 当然也有一些 vim 的插件, 如 OSX 下的 [SmartIM](https://github.com/ybian/smartim.git),
可以帮助自动切换输入法, 但使用起来会经常有一些奇怪的问题, 例如会导致插件 VisIncr 变得极其缓慢.

相比于 vim, Emacs 就完全不会有这个问题, 因为它的命令操作都是和控制键绑定的, 而这些按键并不会被输入法截获, 所以就不会有 vim 的问题.

## 使用 Orgmod

早就听闻这个插件的大名, 一直想尝试下. Vim 下虽然也有类似的插件, 但目前都还只是半成品, 功能完全不能同日而语.

## 传说中无所不能的 Emacs

 传说 Emacs 无所不能, 比如直接浏览网页, 比如直接浏览 pdf 文件...
 
 本来是想能在 Emacs 里变编辑 Markdown 文件, 变在另外一个窗口预览, 实现类似专业 Markdown 编辑器的功能,
 但搜遍了 github 也没能找到这样一款称心如意的 Markdown 预览插件.  用 Emacs 自带窗口的预览效果奇丑无比, 不能忍!
 推而求其次, 可以接受在第三方软件里显示效果, 然后把 Emacs 的编辑窗口设置成半透明来看实际效果.
 但竟然都没能找到一款可以跟随 Emacs 编辑窗口里的光标自动 scroll 预览窗口内容的插件!!!
 而我却找到了可以实现这样功能的 Vim 插件.
 
 Emacs 也没有我最开始预想的那么无所不能...

##  Elisp

 作为一名程序员, 现在如果没捣鼓过函数式编程语言, 就不好意思和别人说是科班出身的. Lisp 语言是最经典的函数式编程语言了,
 而 Emacs 是用 lisp 作为它的插件编写语言, 学习 Emacs 也就可以顺便学习下 Lisp 了.
 
以上就是我开始学习 Emacs 的目的了. 学习 Emacs 这种和 Vim 完全不同操作模式、 不同设计理念的编辑器也可以开拓自己的视野，
或许将来可以进一步帮助自己提高 Vim 的使用效率。

最近的一段时间就会这样来使用 Vim 和 Emacs 了：
- Vim：依旧是主力编辑器，看代码，写代码；
- Emacs：写博客，用 Orgmod 来记笔记和 Task 管理；

这就是是我的第一篇正式博客了，晚安！
