# 掌握技术
+ vue+django rest framework 前后端分离
+ restful api
+ sentry错误日志和告警
+ xadmin
+ Serializer
+ jwt登录


# 开发中常见问题
+ 本地不能重现bug
+ api出错难找到错误栈 
+ api文档管理问题
+ url增多难维护
+ 接口更新而文档不更新，不知道怎么测试
+ 反爬限制频率 ： 
+ 缓存加速访问
+ 调试支付 
+ 调试第三方登录： social django


# Vue开发环境
+ webstorm
+ nodejs
+ cnpm

# 外键
> 为什么要用外键啊，害处太多了
> 浪费性能
> 增加开发时的思考
> 不易维护
+ 相当于是对另一个表的主键进行依赖
+ 那么要插入数据进一个含外键的表，就必须含主键的那个表中有相应的值
+ 那么相当于直接删含主键的表是删不掉了，必须先清除依赖他的外键的表上的值
+ 或者先关闭约束检查，两边操作好以后再开回去约束检查


# migration是什么
+ makemigration 是建立数据库修改计划，并且将计划写到py脚本
+ migirate 是执行这些计划的py脚本 (他有个元数据存了上次执行到哪个版本的py)
+ 如果删除了元数据、并且删除了相应的表，那么makemigration就是建表语句，而不是修改表的语句了
+ 也可以手动建表，不用migration功能。这功能看起来在版本过多的时候会导致混乱

# 前后端分离优缺点
+ 多端适应：pc、app、pad
+ SPA开发模型：单页面
+ 前后端职责
+ 前后端相互等待
+ 开发语言耦合
+ 文档重要性增加
+ SEO难度增大
+ 依赖倒置的成本 

# Restful API
+ Restful api是现在的前后端分离的最佳实践
+ 轻量，http
+ post/get/put/delete操作
+ 面向资源
+ 数据描述简单，用json 


# vue
+ 前端工程化 :webpack
+ 数据双向绑定 :mvvm
+ 组件化开发
+ vue,vuex, vue-router, axios 
+ ES6, babel 



