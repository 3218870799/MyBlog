# 博客Blog

本项目是基于微服务架构的前后端分离的博客系统。以最流行最新的技术写博客。

# 技术选型

架构图

![server](media/server.jpg)



## 后端选型：

|      技术      |          说明           |                             官网                             |
| :------------: | :---------------------: | :----------------------------------------------------------: |
|   SpringBoot   |         MVC框架         | [ https://spring.io/projects/spring-boot](https://spring.io/projects/spring-boot) |
|  SpringCloud   |       微服务框架        |           https://spring.io/projects/spring-cloud/           |
| SpringSecurity |     认证和授权框架      |          https://spring.io/projects/spring-security          |
|  MyBatis-Plus  |         ORM框架         |                   https://mp.baomidou.com/                   |
|   Swagger-UI   |      文档生产工具       | [ https://github.com/swagger-api/swagger-ui](https://github.com/swagger-api/swagger-ui) |
|    RabbitMQ    |        消息队列         |   [ https://www.rabbitmq.com/](https://www.rabbitmq.com/)    |
|     Redis      |       分布式缓存        |                      https://redis.io/                       |
|     Kibana     |    分析和可视化平台     |               https://www.elastic.co/cn/kibana               |
| Elasticsearch  |        搜索引擎         | [ https://github.com/elastic/elasticsearch](https://github.com/elastic/elasticsearch) |
|      Solr      |        搜索引擎         |                http://lucene.apache.org/solr/                |
|     Docker     |       容器化部署        |      [ https://www.docker.com](https://www.docker.com/)      |
|     Druid      |      数据库连接池       | [ https://github.com/alibaba/druid](https://github.com/alibaba/druid) |
|     七牛云     |    七牛云 - 对象储存    |         https://developer.qiniu.com/sdk#official-sdk         |
|      JWT       |       JWT登录支持       |                 https://github.com/jwtk/jjwt                 |
|     SLF4J      |        日志框架         |                    http://www.slf4j.org/                     |
|     Lombok     |    简化对象封装工具     | [ https://github.com/rzwitserloot/lombok](https://github.com/rzwitserloot/lombok) |
|     Nginx      | HTTP和反向代理web服务器 |                      http://nginx.org/                       |
|    JustAuth    |    第三方登录的工具     |             https://github.com/justauth/JustAuth             |
|     Hutool     |     Java工具包类库      |                  https://hutool.cn/docs/#/                   |
|    阿里大于    |      短信发送平台       |            https://doc.alidayu.com/doc2/index.htm            |
| Github Actions |       自动化部署        |              https://help.github.com/en/actions              |
|     Zipkin     |        链路追踪         |             https://github.com/openzipkin/zipkin             |
| Flexmark-java  |    Markdown转换Html     |            https://github.com/vsch/flexmark-java             |
|   Ip2region    |    离线IP地址定位库     |          https://github.com/lionsoul2014/ip2region           |

## 开发工具

### 开发工具

|     工具     |       说明        |                             官网                             |
| :----------: | :---------------: | :----------------------------------------------------------: |
|     IDEA     |    Java开发IDE    |           https://www.jetbrains.com/idea/download            |
|   WebStorm   |    前端开发IDE    |             https://www.jetbrains.com/webstorm/              |
| RedisDesktop |  Redis可视化工具  | [ https://redisdesktop.com/download](https://redisdesktop.com/download) |
| SwitchHosts  |   本地Host管理    |             https://oldj.github.io/SwitchHosts/              |
|   X-shell    | Linux远程连接工具 |               https://xshell.en.softonic.com/                |
|    X-ftp     | Linux文件传输工具 |         https://www.netsarang.com/zh/all-downloads/          |
|    SQLyog    |  数据库连接工具   |               https://sqlyog.en.softonic.com/                |
| ScreenToGif  |    Gif录制工具    | [ https://www.screentogif.com/](https://www.screentogif.com/) |

### 开发环境

|     工具      | 版本号 |                             下载                             |
| :-----------: | :----: | :----------------------------------------------------------: |
|      JDK      |  1.8   | https://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html |
|     Maven     | 3.3.0+ |                   http://maven.apache.org/                   |
| Elasticsearch | 6.3.0  |               https://www.elastic.co/downloads               |
|     Solr      |  7.0   |                http://lucene.apache.org/solr/                |
|     MySQL     |  5.6   |                    https://www.mysql.com/                    |
|    Erlang     |  20.3  |                   https://www.erlang.org/                    |
|   RabbitMQ    | 3.7.4  |            http://www.rabbitmq.com/download.html             |
|     Nginx     |  1.10  |              http://nginx.org/en/download.html               |
|     Redis     | 3.3.0  |                  https://redis.io/download                   |

## 前端选型

### 

|         技术          |           说明            |                             官网                             |
| :-------------------: | :-----------------------: | :----------------------------------------------------------: |
|        Vue.js         |         前端框架          |                      https://vuejs.org/                      |
|      Vue-router       |         路由框架          |                  https://router.vuejs.org/                   |
|         Vuex          |     全局状态管理框架      |                   https://vuex.vuejs.org/                    |
|        Nuxt.js        | 创建服务端渲染 (SSR) 应用 |                    https://zh.nuxtjs.org/                    |
|        Element        |        前端ui框架         |    [ https://element.eleme.io](https://element.eleme.io/)    |
|         Axios         |       前端HTTP框架        | [ https://github.com/axios/axios](https://github.com/axios/axios) |
|        Echarts        |         图表框架          |                      www.echartsjs.com                       |
|       CKEditor        |       富文本编辑器        |                    https://ckeditor.com/                     |
|     Highlight.js      |     代码语法高亮插件      |         https://github.com/highlightjs/highlight.js          |
|      Tui-editor       |      Markdown编辑器       |              https://github.com/nhn/tui.editor               |
|      vue-cropper      |       图片裁剪组件        |           https://github.com/xyxiao001/vue-cropper           |
| vue-image-crop-upload |    vue图片剪裁上传组件    |      https://github.com/dai-siki/vue-image-crop-upload       |
|   vue-emoji-comment   |   Vue Emoji表情评论组件   |       https://github.com/pppercyWang/vue-emoji-comment       |
|     clipboard.js      |     现代化的拷贝文字      |                  http://www.clipboardjs.cn/                  |
|      js-beautify      |    美化JavaScript代码     |         https://github.com/beautify-web/js-beautify          |
|     FileSaver.js      |     保存文件在客户端      |           https://github.com/eligrey/FileSaver.js            |
|   vue-side-catalog    |        目录导航栏         |        https://github.com/yaowei9363/vue-side-catalog        |
|        uniapp         |     移动端跨平台语言      |                  https://uniapp.dcloud.io/                   |
|        colorUi        |  专注视觉的小程序组件库   |             https://github.com/weilanwl/ColorUI              |

# Window搭建开发环境

详细知识以及搭建环境操作步骤，可以参考我的另一个项目  [-NOTE](https://github.com/3218870799/-Note) 

1：运行` nginx ` 访问浏览器 `http://localhost:8600/01.png` 验证是否启动

2：启动` redis ` ，双击安装目录下 ` redis-server ` ,验证，点击 ` redis-cli ` 能正常启动即可。

3：启动 ` RabbitMQ `  ,双击 ` RabbitMQ Service - start ` 即可，验证访问 ` http://localhost:15672 ` 登录即可。

4：启动 ` mysql ` ,打开 ` cmd ` 窗口，输入 ` mysqld --console ` ,然后打开 ` Navicat  ` 连接即可。