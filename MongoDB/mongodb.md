# MongoDB简介

### MongoDB

MongoDB 是由C++语言编写的，是一个基于分布式文件存储的开源数据库系统。

在高负载的情况下，添加更多的节点，可以保证服务器性能。

MongoDB 旨在为WEB应用提供可扩展的高性能数据存储解决方案。

MongoDB提供数据库的社区版和企业版：

- MongoDB社区版是MongoDB的可用源和免费版本。
- MongoDB企业版作为MongoDB高级企业版订阅的一部分提供，并且包括对MongoDB部署的全面支持。MongoDB企业版还添加了以企业为中心的功能，例如LDAP和Kerberos支持，磁盘加密和审核。

MongoDB中的记录是一个文档，它是由字段和值对组成的数据结构。MongoDB文档类似于JSON对象。字段的值可以包括其他文档，数组和文档数组。

![A MongoDB document.](../images/crud-annotated-document.svg)

### 特点

- 在MongoDB中，可以通过字段，范围查询进行搜索，并且还支持正则表达式搜索。
- 在MongoDB中，可以索引文档中的任何字段。
- MongoDB支持主从复制。主机可以执行读写操作，从机从主机复制数据，只能用于读取或备份(不写入)
- MongoDB可以在多台服务器上运行。 复制数据以保持系统正常运行，并在硬件故障的情况下保持其运行状态。
- 由于数据放在分片中，因此具有自动负载平衡配置。
- 支持Map-Reduce和聚合工具
- 使用JavaScript而不使用Procedure
- MongoDB是一个使用C++编写的无模式数据库
- MongoDB可以提供更高的性能
- 轻松存储任何大小的文件，不会使您的存储模型复杂化
- MongoDB可以更好的处理和管理故障
- 具有动态的JSON数据模型
- 使用分片可以自动扩展
- 内置复制高可用行

### 优点

* MongoDB 的架构较少。它是一个文档数据库，它的一个集合持有不同的文档。
* MongoDB 中单个对象的结构很清淅。
* MongoDB 中没有复杂的连接。
* MongoDB 提供深度查询的功能，因为它支持对文档的强大的动态查询。
* MongoDB 很容易扩展。
* 它使用内部存储器来存储工作集，这是其快速访问的原因。

### MongoDB历史

* 2007年10月，2009年2月首度推出。
* 2012年05月23日，MongoDB2.1 开发分支发布了! 该版本采用全新架构，包含诸多增强。

* 2012年06月06日，MongoDB 2.0.6 发布，分布式文档数据库。

* 2013年04月23日，MongoDB 2.4.3 发布，此版本包括了一些性能优化，功能增强以及bug修复。

* 2013年08月20日，MongoDB 2.4.6 发布。

* 2013年11月01日，MongoDB 2.4.8 发布。

* 2017年03月17日，MongoDB 3.0.1发布。

* 2018年08月06日，MongoDB 4.0.2发布，支持多文档事务。

* 2019年08月13日，MongoDB 4.2.0 发布，引入分布式事务。
* 2020年07月30日，MongoDB 4.4 发布。

### MongoDB下载

可以通过MongoDB官网下载安装包，地址为：https://www.mongodb.com/try/download/community。

MongoDB支持以下系统：

- MacOS 32-bit
- MacOS 64-bit
- Linux 32-bit
- Linux 64-bit
- Windows 32-bit
- Windows 64-bit
- Solaris i86pc
- Solaris 64

### 语言支持

MongoDB有官方的驱动如下：

- C
- C++
- C# / .NET
- Erlang
- Haskell
- Java
- JavaScript
- Lisp
- node.JS
- Perl
- PHP
- Python
- Ruby
- Scala

### 适用场景

* 大而复杂的数据
* 移动和社会基础设施数据
* 内容管理和交付
* 用户数据管理
* 数据中心