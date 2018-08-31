Push_Module : 小程序推送功能模块
===============

> 模块基于ThinkPHP5.1目录开发，以项目开发基础目录为标准

## 说明：

### push_v1_sql.php 数据库迁移运行文件
### push_route_v1_api.php 路由文件
### wx_config.php 模板需要的配置文件，可以修改到全局配置中
### v1_tableName.php  模板需要的数据库表配置文件，可以修改到全局配置中

## 接口：
~~~
// +------------------------------------------------------
// : 功能：收集formId保存到数据库
// : 传值：POST
// : 路由：v1/push_module/push_route
// : 输入 : (String) $userToken => '用户标识';
// : 输入 : (String) $formId    => '表单ID';
// : 输出 : {"errNum":0,"retMsg":"收集成功","retData":true}
// +------------------------------------------------------
~~~