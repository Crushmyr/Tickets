## Overview

该程序是使用 Python3 抓取 12306 网站信息提供一个命令行的火车票查询工具

借鉴了[Python3 实现火车票查询工具](https://www.shiyanlou.com/courses/623)，不过由于 12306 的接口发生了变化，导致该网址所提供的程序无法正常使用，所以我就按着现在的12306新写了一个，学习学习。



## Requirements

- Python 3.x
- Works on Linux, Windows, Mac OSX...



## Installation

点击 [这里](https://github.com/Crushmyr/Tickets/archive/master.zip) 下载，

或者使用命令：

``` bash
$ git clone https://github.com/Crushmyr/Tickets
```



## Help

```
命令行火车票查看器

Usage:
  tickets.py [-gdtkz] <from> <to> <date>

Options:
  -h,--help   显示帮助菜单
  -g          高铁
  -d          动车
  -t          特快
  -k          快速
  -z          直达

Example:
  python tickets.py 北京 上海 2017-11-10
  python tickets.py -dg 成都 南京 2017-11-10
```
