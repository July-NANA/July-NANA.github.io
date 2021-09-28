---
title: JAVA基础知识之FileOutputStream流
date: 2021-09-28 
tags: Java
description: my first blog
---
FileOutputStream流是指文件字节输出流，专用于输出原始字节流如图像数据等，其继承OutputStream类，拥有输出流的基本特性。  
构造函数：
  ```
  public FileOutputStream(File file,boolean append) throws FileNotFoundException{}
  ```
当**append**为true时，从文件末尾写入数据。  
当**append**为false时，从文件头部写入，就是覆盖，默认为false。  

参考文档：
1. https://blog.csdn.net/ai_bao_zi/article/details/81110405
2. https://blog.csdn.net/QPC908694753/article/details/70159436/
