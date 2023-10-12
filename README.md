# XmThinkORM 
>* 修改背景:将TP的项目移植到Laravel
>* 遇到问题:tp和Laravel的全局函数冲突，导致无法调用。
>* 修改方案：重命名tp相关的ORM函数名称，不改变其内容。
> 
* 本项目代码代码来着ThinkPHP
* https://github.com/top-think/think-orm

基于PHP8.0+ 和PDO实现的ORM，支持多数据  库，3.0版本主要特性包括：

* 基于PDO和PHP强类型实现
* 支持原生查询和查询构造器
* 自动参数绑定和预查询
* 简洁易用的查询功能
* 强大灵活的模型用法
* 支持预载入关联查询和延迟关联查询
* 支持多数据库及动态切换
* 支持`MongoDb`
* 支持分布式及事务
* 支持断点重连
* 支持`JSON`查询
* 支持数据库日志
* 支持`PSR-16`缓存及`PSR-3`日志规范


## 安装
~~~
composer require yukaige/xm-think-orm
~~~

## 文档

详细参考 [ThinkORM开发指南](https://www.kancloud.cn/manual/think-orm/content)
