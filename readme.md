# 掌握技术
+ vue+django rest framework 前后端分离
+ restful api
+ sentry错误日志和告警
+ xadmin
+ Serializer


# 开发中常见问题
+ 本地不能重现bug
+ api出错难找到错误栈 
+ api文档管理问题
+ url增多难维护
+ 接口更新而文档不更新，不知道怎么测试
+ 反爬限制频率
+ 缓存加速访问
+ 调试支付 
+ 调试第三方登录


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

