# 最简单git使用教程

网上关于git的教程一大把，可是对于大多数人而言，并不友好，要学的东西太多，实在没有时间仔细阅读。

本文提供一个最简单的教程，节约时间，节省精力。

如果只是提供给自己记录日志和简单的代码，不考虑合作和版本控制方面的细节，其实只需要简单三步即可。

前提：已经安装好了最新的git工具和vscode编辑器（并非必须，但是强烈推荐），可以到官网下载安装，无需赘述。

* 第一步：在本地创建一个文件夹，使用cmd工具进入该文件夹，运行

```shell
git init
```

* 第二步：在git网站创建一个repo，名称自选，假设为： https://github.com/sean-xia/tmp201907.git

* 第三部：在本地文件夹中执行
```shell
git remote add origin https://github.com/sean-xia/tmp201907.git
```
然后在本地文件夹中使用vscode撰写文件，通过vscode的右侧工具栏中的源代码管理工具进行commit和push，或者pull等等操作。

这样就完成了一个简单的repo。希望有帮助，Have Fun！