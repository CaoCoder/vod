项目名称：视频点播系统

项目功能：搭建一个共享点播系统，服务器支持用户通过前端浏览器访问服务器，获取展示与观看和操作的界面，最终实现视频的上传以及观看和删改查等基础管理功能。

开发环境：`ubuntu/vim、g++、gdb、makefile`

技术特点：`http`服务器搭建，`restful`风格接口设计，`json`序列化，线程池，`html+css`基础

项目模块：

+ 数据管理模块：基于`MYSQL`进行数据管理，封装数据管理类进行数据统一访问
+ 业务处理模块：基于`HTTPLIB`搭建`HTTP`服务器，使用`restful风格`进行接口设计处理客户端业务请求
+ 前端界面模块：基于基础的`HTML+CSS+JS`完成基于简单模板前端界面的修改与功能完成。
