# SSM整合案例



### 简介

该案例是一个简单的Spring、SpringMVC、MyBatis整合，使用了如下内容

- MySQL
- Pagehelper
- 通用Mapper
- JSP OR Thymeleaf，可以通过配置文和依赖件切换
- logback日志
- lombok
- jackson
- tomcat7插件



使用了BaseController BaseService简化代码

从controller和service中提取了部分内容简化了代码

AOP如果不需要可以不在Spring-DAO.xml中引入。

sql语句在src/main中，日志文件的默认位置是项目的logs目录

