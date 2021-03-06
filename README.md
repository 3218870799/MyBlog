# 博客Blog

本项目是基于微服务架构的前后端分离的博客系统。以最流行最新的技术写博客。

# 项目启动

详细知识以及搭建环境操作步骤，可以参考我的另一个项目  [-NOTE](https://github.com/3218870799/-Note) 

注册中心由Euraka换成Nacos

1：数据库导入sql

```cmd
mysqld --console
```

启动，导入sql语句

3：单机模式启动Nacos

```cmd
.\startup.cmd -m standalone
```

访问：http://localhost:8848/nacos验证

4：启动Sentinel

```cmd
start java -jar sentinel-dashboard-1.8.1.jar --server.port=8070
```

访问：http://localhost:8070/

5：启动Zipkin

```cmd
java -jar zipkin-server-2.12.5-exec.jar
```

访问：http://localhost:9411/zipkin/

6：运行` nginx ` 访问浏览器 `http://localhost:8600/01.png` 验证是否启动

注意：`nginx ` 配置本地映射

7：启动` redis ` ，双击安装目录下 ` redis-server ` ,验证，点击 ` redis-cli ` 能正常启动即可。

8：启动 ` RabbitMQ `  ,双击 ` RabbitMQ Service - start ` 即可，验证访问 ` http://localhost:15672 ` 登录即可。

9：下载代码，导入本地，按顺序启动

启动 `myblog_picture ` 

启动 `myblog_sms `

10：前端项目启动

项目工程下package.json是项目的一些依赖，cd 到vue_mogu_admin下，然后运行安装依赖

```cmd
# 指定node-sass的国内镜像源
npm i node-sass --sass_binary_site=https://npm.taobao.org/mirrors/node-sass

# 使用淘宝镜像源进行依赖安装，解决国内下载缓慢的问题(出现警告可以忽略)
npm install --registry=https://registry.npm.taobao.org

# 启动项目
npm run dev

#打包项目（在部署的时候才需要使用）
npm run build
```

其中有一些脚本

很多配置是写在Nacos中的

配置Nacos，添加配置





# 问题：

1：不显示多模块运行窗口Services：

解决：https://www.cnblogs.com/chuyuan/p/11775120.html

2：Command line is too long. Shorten command line for ServiceStarter or also for Application：

解决：https://blog.csdn.net/qq_38425719/article/details/100012533



## 后端设计选型

架构图



### 

# 

