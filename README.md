# Readme.md

## Tars

Tars这个名字取自于电影"星际穿越"中的机器人，它是基于名字服务使用Tars协议的高性能RPC开发框架，配套一体化的运营管理平台，并通过伸缩调度，实现运维半托管服务。

Tars是腾讯从2008年到今天一直在使用的后台逻辑层的统一应用框架TAF（Total Application Framework），目前支持C++,Java,PHP,Nodejs,Go语言。该框架为用户提供了涉及到开发、运维、以及测试的一整套解决方案，帮助一个产品或者服务快速开发、部署、测试、上线。 它集可扩展协议编解码、高性能RPC通信框架、名字路由与发现、发布监控、日志统计、配置管理等于一体，通过它可以快速用微服务的方式构建自己的稳定可靠的分布式应用，并实现完整有效的服务治理。

目前该框架在腾讯内部，各大核心业务都在使用，颇受欢迎，基于该框架部署运行的服务节点规模达到上万个。

Tars详细介绍参见 [简介](rumen/jian-jie.md)。

### 支持平台

目前运行的操作系统平台如下：

* Linux

### 支持语言

目前支持的开发语言如下：

* C++
* Java
* Nodejs
* PHP
* Go

### 安装说明

1. 初次接触时，建议按照 [手动安装](rumen/an-zhuang/shou-dong-an-zhuang.md) 一步一步进行安装；
2. 或者，可以利用 [脚本](rumen/an-zhuang/yi-jian-bu-shu.md) 进行安装（必要时需要修改）。
3. 也可以选择采用 [Docker镜像安装 ](rumen/an-zhuang/docker.md)的方式进行快捷安装。

**注意：安装后为了提供更好的安全防护，强烈建议开启[用户体系鉴权登陆模块](https://github.com/TarsCloud/TarsWeb/blob/master/docs/TARS%20%E7%94%A8%E6%88%B7%E4%BD%93%E7%B3%BB%E6%A8%A1%E5%9D%97%2B%E8%B5%84%E6%BA%90%E6%A8%A1%E5%9D%97%E4%BD%BF%E7%94%A8%E6%8C%87%E5%BC%95.md)。**

### License

Tars的开源协议为BSD-3-Clause，详情参见 [LICENSE](license.md)。

### 联系方式

qq技术交流群群：579079160、669339903。

微信公众号：TARS星球

推特地址：[@TarsCLoud](https://twitter.com/TarsCloud)

