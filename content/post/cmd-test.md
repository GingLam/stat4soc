---
date: "2020-08-04T21:05:05-05:00"
tags:
- issue
title: cmd Test
---


### 课前说明
#### 如何自助查阅语法？
* 访问IBM在线操作手册
  - 网址：http://dwz.win/agQD
  - 左侧目录依次点击：Reference -> Command Syntax Reference
* 巧用搜索引擎+关键词
  - 如检索回归分析语法，关键词应键入："spss"+"syntax"+"regression".
#### 如何养成良好的语法管理习惯？
* 每次分析时，创建并保存语法文档".sps"
* 对于关键操作部分，勤用注释"*"
* 使用带语法高亮的编辑器，如"Sublime"、"Notepad++" （安装后配置语法高亮定义文件）

```
get data
	/type = xls
	/file = "auto.xls"
	/sheet = name "domestic"
	/cellrange = full
	/readnames = on.
```



