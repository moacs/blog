---
title: Spring Boot
---
## Quick Start

Spring Boot commond

#安装依赖包并编译执行测试
mvn install

#在target目录中执行使用java命令可以运行程序
java -jar xxx.jar

#直接编译并运行
mvn spring-boot:run

#使用spring-profile.active改变运行时使用的配置文件
mvn spring-boot:run --spring-profile.active=prod