---
title: RHEL的EPEL源地址及安装
date: '2015-01-13 00:00:00'
categories:
- Linux
layout: post
desc: RHEL的EPEL源地址及安装
keywords: rhel,epel,rpm,linux
tags:
- epel
icon: icon-centos
slug: linux-epel

---
RHEL6:

```
[root@test ~]# rpm -ivh http://download.fedoraproject.org/pub/epel/6/i386/epel-release-6-5.noarch.rpm
[root@test ~]# rpm -ivh http://download.fedoraproject.org/pub/epel/6/i386/epel-release-6-8.noarch.rpm
```

RHEL5:

```
[root@test ~]# rpm -ivh http://download.fedoraproject.org/pub/epel/5/i386/epel-release-5-4.noarch.rpm
[root@test ~]# rpm -ivh  http://download.fedoraproject.org/pub/epel/5/i386/epel-release-5-4.noarch.rpm
```

EPEL版本不同，根据不同系统请自行安装。