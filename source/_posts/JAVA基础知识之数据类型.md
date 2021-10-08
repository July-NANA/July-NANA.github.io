---
title: JAVA基础知识之数据类型
date: 2021-10-08 
tags: Java
description: Java中的数据类型基础知识
---

Java中规定整数默认是int，浮点数默认是double。  
如果要把一个浮点数赋值给一个float的变量，float f=10.0f。  

- Java字符中‘\u’的含义  
  ‘\u’是转义字符，表示后面跟一个十六进制数，通过这个十六进制数来指定一个字符

- List<String>不能转换为List<Object>  
虽然 String 是 Object 的子类型，但是 List<String> 不是 List<Object> 的子类型。如果 List<String> 是 List<Object> 的子类型的话，在面向抽象编程的时候，就可能向 String List 中加入其它类型的对象，显然编译不通过。
