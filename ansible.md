# ansible 

## 程序发布

1、预发布验证

2、程序发布：

​			不能导致系统故障或者系统完全不可用

​			不能影响用户体验

3、灰度发布：

4、发布路径：

​				/webapp/tiangou-1.1

​				/webapp/tiangou  （软连接）

​				/webapp/tiangou-1.2

5、发布流程：

​		在调度器上下线一批主机（标记为maintanance状态） --> 关闭服务 -->  部署新版本 的应用程序 -->  

​		启用服务   -->   在调度器上启用服务器

6、自动化灰度发布：

​		脚本、发布平台



## 常用自动化运维工具

ansible （python，angentless  中小型应用环境）

saltstac  （python，一般需部署agent ，执行速度快）

puppet（ruby  功能强大配置复杂   重型  适合大型环境）



## ansible工作架构及原理

