# 使用GitBook 制作在线文档

markdown + git + gitbook 制作在线文档。

***

## 为什么用GitBook

> gitbook 是通过git的方式构建电子书的一种工具，可以有效的利用了git在版本控制方面的优势和markdown在编写文档方面的优势，再结合github进行在线托管，简直完美。

优点 ：
* 支持markdown语法
* 版本控制
* 可以转换成pdf epub格式


## 安装步骤

* 1、安装node

* 2、安装gitbook客户端


```
npm install gitbook-cli -g
```

* 3、进入https://calibre-ebook.com/download 下载calibre，添加配置calibre安装路径（如C:\Program Files\Calibre2）到 path。该工具用来导出pdf epub格式文档。


* 4、打开 gitbook

![](/assets/2018-11-25_222019.jpg)

选择library path为 文档目录

![](/assets/2018-11-25_222225.jpg)

新建一本book

![](/assets/2018-11-25_222428.jpg)

## 将gitboot与github关联

* 1、 在github中新建空白的仓库

![](/assets/2018-11-25_222746.jpg)

* 2、将仓库的url与gitbook publish 关联

![](/assets/2018-11-25_222929.jpg)

![](/assets/2018-11-25_223102.jpg)

在gitbook中点击public

![](/assets/2018-11-25_223413.jpg)

![](/assets/2018-11-25_223157.jpg)

## 转成在线文档

生成在线文档

```
gitbook serve
```

* 导出pdf

```
gitbook pdf
```



