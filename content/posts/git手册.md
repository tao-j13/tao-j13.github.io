---
title: "Git手册"
date: 2023-03-19T00:44:08+08:00
draft: false
---

记录git日常相关命令使用，以及可能遇到的一些问题



### git常用命令





### git子模块的添加和删除

+ 添加模块

```shell
git submodule add git地址 targetUrl
```

+ 删除模块

```shell
git submodule deinit moduleName # 删除模块目录
git rm moduleName # 删除文件夹，并且.gitmodule 去除引用
```



>  参考文章 
