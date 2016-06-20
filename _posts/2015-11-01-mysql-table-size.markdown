---
title: MySQL查看表大小
date: '2015-11-01 00:00:00'
categories:
- Database
layout: post
desc: MySQL查看表大小
keywords: Linux,MySQL,table,size
tags:
- MySQL
- table
- "大小"
icon: fa-database
slug: mysql-table-size

---
方法一：

在MySQL的data目录下查看，前提是my.cnf中配置了innodb_file_per_table

方法二：

在MySQL查询中执行以下操作：

``` sql
select table_name,concat(round(data_length/1000/1000/1000,2),'GB') as data_length_GB 
from information_schema.tables ORDER BY data_length_GB;
```
