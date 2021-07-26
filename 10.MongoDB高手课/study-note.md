# MongoDB学习笔记

## 1. 基础知识

**MongoDB是什么类型的数据库？MongoDB的特点？**

> 1.MongoDB是基于JSON模型，鼓励更多的文档嵌套方式，来减少多表关联的设计
> 2.MongoDB是通过分片来支持横向扩张，分片的设计和调优相对比较复杂
>
> MongoDB是以JSON为数据模型的文档数据库，JSON Document。MongoDB有很强的横向扩展能力，可以支撑很大数据量和并发。

**OLTP与OLAP的区别？**

> 联机事务处理OLTP（on-line transaction processing）、联机分析处理OLAP（On-Line Analytical Processing）。OLTP是传统的关系型数据库的主要应用，主要是基本的、日常的事务处理，例如银行交易。OLAP是数据仓库系统的主要应用，支持复杂的分析操作，侧重决策支持，并且提供直观易懂的查询结果。

**MongoDB与关系型数据库的区别？**

![](./img/differences.png)

