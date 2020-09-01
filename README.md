# 旅游网API

### 介绍
旅游网是一个基于SpringBoot框架设计的一个毕业设计，主要类似于一个电商系统。此项目是本人亲自开发，
唯一博客：https://blog.csdn.net/Ares_song/article/details/104163473
唯一B站演示视频：https://www.bilibili.com/video/BV1t7411p7Aw
其他均为盗卖，此项目开源，伙伴们别被骗哦
需要此项目的部署和讲解答辩视频可以加群：671408308

###群说明
由于群人数目前过多，扩充群人数需要额外费用，故此群现为收费群，望理解。
群资源很多，有各种资料和软件还有其他项目，你不会吃亏

### **主要功能介绍**

有用户登录注册，景点列表，相册墙，购买景点，评论，酒店管理和一整套后台管理系统。使用到SMS短信注册验证，JMail进行找回密码邮箱验证，OSS阿里云图片存储服务器，RabbitMQ消息队列以及redis缓存等小技术。整个系统采用Restful风格。以json进行数据的传输。前端页面采用BootStrap以及Layui。

### 软件架构

1.数据库：MySql5.7

2.前端：Layui，BootStrap，Echars等技术

3.后台：SpringBoot、SpringDataJpa等

4.架构模式：半前后分离架构模式

5.模板引擎：thymeleaf

6.项目管理：Maven

7、JDK版本：1.8

8、额外功能：阿里云短信服务SMS、阿里云图片存储OSS、QQ邮箱验证服务

9、主要算法：Twitter雪花算法（ID生成策略）、Bcrypt（密码加密）、JPA排序

### 使用说明

完成以上安装，导入数据库后，即可运行Application，需要此项目的部署和讲解答辩视频可以加群：671408308

##### **前台访问路径：**

```
http://localhost:8080/dist/view
```

##### **后台访问路径：**

```
http://localhost:8080/admin/adminlogin
```





