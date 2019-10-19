---
title: antd design自定义组件
date: 2018-01-16 17:36:09
tags:
categories:
- 经验
---

### 序言
在本文，笔者将使用常规思维的方式，引导大家自定义一个自己需要的组件。

### 一、组件结构
组件有大小之分，这里小组件笔者就不说了，这里主要针对具备交互能力、以及能被父级组件引用和传参的组件。

### 二、编写组件页面内容
在做这件事的时候要确定几点：
1. 该组件具有什么功能
2. 该组件跟父组件的关系
3. 该组件的使用情景
我先说我的组件，在rbac的菜单管理页面，因为出现两个form表单，导致出现了不可控的情况，所以我这边的组件

es6 import, 花括号跟无花括号的区别在于，花括号是引用模块中的某些属性或函数，而无花括号就是引入整个模块