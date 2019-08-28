# horizon-cloud-seed
基于Spring Cloud实现的前后端分离的后台管理信息系统，后台管理系统的脚手架

运行步骤
运行数据库脚本：依次运行数据库：ace-admin/db/init.sql
修改配置数据库配置：ace-admin/src/main/resources/application.yml、ace-gate/src/main/resources/application.yml
依次运行main类：CenterBootstrap（ace-center）、ConfigServerBootstrap（ace-config）、GateBootstrap（ace-gate）、AdminBootstrap（ace-admin）、UIBootstrap（ace-ui）
访问地址: http://localhost:8765/admin/index 账号/密码：admin/admin
