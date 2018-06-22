Public DNS List
============

- [Chinese readme (this)](https://github.com/neargle/public-dns-list/blob/master/readme-cn.md)
- [English readme](https://github.com/neargle/public-dns-list/blob/master/readme.md)

## 介绍

收集"公开可用"的DNS服务器列表。

目前有两个列表：

1. 收集到的世界上所有的DNS服务器列表 : [all.txt](https://github.com/neargle/public-dns-list/blob/master/all.txt)
2. 中国境内(除中国台湾以外)的DNS服务器列表(感觉不太全...) : [china.txt](https://github.com/neargle/public-dns-list/blob/master/china.txt)


## 更新

两个列表会不定时更新，因为是用在另一个安全扫描器相关的项目中，所以只有那个项目的定时任务启动时需要DNS列表时才会更新。

更新频率：大概平均每一到两天更新一次。

## 什么时候会用到这个项目

- 当爆破探测子域名时，如果同一时间内发起的DNS请求过多，会导致误报漏报严重的情况。同得带宽的条件下，可以使用请求不同的DNS服务器来缓解这个问题。
- 一个域名在不同DNS上解析可能会有不同的结果。依照结果而定，可能可以绕过CDN找到真实IP。
- 配合 massdns 用处很大
- and so on

