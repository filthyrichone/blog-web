---
title: java类
date: 2020-09-15 23:14:47
tags:
categories:
---

## 简介
day6，upup~
<!-- more -->

## Date类的简单实用
> SimpleDateFormat+Date类

## 内部类
> 内部类就是类里面嵌套了类

|普通内部类|静态内部类|
|---|---|
|异|普通内部类只能由具体的外部类对象生成内部内对象，静态内部类则可以直接生成对象|
|同|在类的里面定义，引入有导入包+外部类名.内部类名两种方式|
|同|在内部类和其外部类中可以相互引用私有变量/方法，部手限制关键字影响|

> 局部内部类

1、使用场景，只出现一次，需要不确定的类型实现对象引用接口/父类方法
2、使用方式new +父类/接口名（）{}即可。
**限制**：
+ 使用局部变量需要final关键字（jdk1.8后可省略）
+ 声明只在定义的局部代码块中有效/可用，但对象地址可以传递出去——>用对象实现方法调用（传递出去时返回类型使用父类声明即可）
**应用**
+ sort方法总的comparator接口对象