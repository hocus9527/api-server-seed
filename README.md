# api-server-seed
API服务基础脚手架搭建，采用spring-boot\spring-session\mybatis\redis\quartz等，支持集群部署



## 更新纪录：

20160407
--------
1. 升级mapper到最新版本3.3.8，重新适配，调整原有代码，由于扫描相关性，将mybatis相关代码统一放到了包orm下
2. 调整包名，按功能做一定区分
3. mybatis分页插件，采用mapper作者提供的插件
