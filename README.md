---
### 👉作者QQ ：1556708905 微信：zheng0123Long (支持修改、部署调试、定制毕设)

### 👉接网站建设、小程序、H5、APP、各种系统等

### 👉选题+开题报告+任务书+程序定制+安装调试+ppt 都可以做
---

**博客地址：
[https://blog.csdn.net/2303_76227485/article/details/140664556](https://blog.csdn.net/2303_76227485/article/details/140664556)**

**视频演示：
[https://www.bilibili.com/video/BV1bM4m117KB/](https://www.bilibili.com/video/BV1bM4m117KB/)**

**毕业设计所有选题地址：
[https://github.com/zhengjianzhong0107/allProject](https://github.com/zhengjianzhong0107/allProject)**

## 基于Java+Springboot+小程序的校园维修管理系统小程序(源代码+数据库)153

## 一、系统介绍
本项目分为用户、维修员、管理员三种角色
### 1、用户：
- 注册、登录、报修申报、报修记录、催单、催单记录、个人信息、密码修改
### 2、维修员：
- 登录、报修管理、导出报修列表、催单记录、个人信息、密码修改
### 2、管理员：
- 用户管理、维修员管理、工种管理、报修记录管理、催单管理、个人信息

## 二、所用技术

后端技术栈：

- Springboot
- mybatisPlus
- mybatis
- Mysql
- Maven

前端技术栈：
 
- html
- thymeleaf
- jquery
- layui
- 微信小程序

## 三、环境介绍

基础环境 :IDEA/eclipse, JDK1.8, Mysql5.7及以上, Maven3.6, 微信开发者工具

所有项目以及源代码本人均调试运行无问题 可支持远程调试运行

## 四、页面截图
### 1、用户网页：
![contents](./picture/picture1.png)
![contents](./picture/picture2.png)
![contents](./picture/picture3.png)
![contents](./picture/picture4.png)
![contents](./picture/picture5.png)
![contents](./picture/picture6.png)
### 2、用户小程序：
![contents](./picture/picture20.png)
![contents](./picture/picture21.png)
![contents](./picture/picture22.png)
![contents](./picture/picture23.png)
![contents](./picture/picture24.png)
![contents](./picture/picture25.png)
### 3、维修员：
![contents](./picture/picture7.png)
![contents](./picture/picture8.png)
![contents](./picture/picture9.png)
![contents](./picture/picture10.png)
### 4、管理员：
![contents](./picture/picture11.png)
![contents](./picture/picture12.png)
![contents](./picture/picture13.png)
![contents](./picture/picture14.png)
![contents](./picture/picture15.png)
![contents](./picture/picture16.png)
![contents](./picture/picture17.png)
![contents](./picture/picture18.png)
![contents](./picture/picture19.png)

## 五、浏览地址
前台地址：http://localhost:9999/login

用户账号密码：1/123456

用户账号密码：xiaofei/123456

后台地址：http://localhost:8081

管理员账户密码：admin/admin

## 六、部署教程
1. 使用Navicat或者其它工具，在mysql中创建对应名称的数据库，并执行项目的sql文件

2. 使用IDEA/Eclipse导入schoolRepair项目，若为maven项目请选择maven，等待依赖下载完成

3. 修改application-dev.yml里面的数据库配置,启动后端项目

4. 微信小程序打开src/main/resources/repair-wx_front项目，编译好之后就运行成功了
