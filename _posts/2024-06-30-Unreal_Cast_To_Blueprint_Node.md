---
title: Unreal Cast To 蓝图节点
categories: [Unreal,Blueprint Node]
tags: [Unreal,Unreal Blueprint Node]
description: Cast To 节点的使用
---

# Cast To 节点
`Cast To` 节点一般用于将一个对象“转换”为另一种特定的对象类型，这个过程成为“类型转换”

`Cast To` 节点通常用于确保需要访问的对象是某种特定类型，为之后对这个对象之星该类型特有的操作作保障。

一般 `Cast To` 节点拥有以下使用场景：

1. **类型检查**： `Cast To` 节点可以检查目标对象是否为指定类型，并提供成功和失败两种情况，程序可以根据具体情况采用相应的逻辑处理
2. **多态**： `Cast To` 节点允许将父类对象转换回实际的子类以便访问子类特有的功能
