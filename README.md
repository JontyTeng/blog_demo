# springboot+vue个人博客系统
需要部署联系 qq：616342388
#### 介绍
基于springboot+vue个人博客系统

#### 在线地址

项目链接：http://www.yruochen.xyz/

         http://www.admin.yruochen.xyz/login


#### 目录结构

1.前端项目位于blog-vue下，blog为前台，admin为后台。

2.后端项目位于blog-springboot下。

3.SQL文件位于根目录下的blog-mysql8.sql，需要MYSQL8以上版本。

4.可直接导入该项目于本地，修改后端配置文件中的数据库等连接信息，项目中使用到的关于阿里云功能和第三方授权登录等需要自行开通。

ps：请先运行后端项目，再启动前端项目，前端项目配置由后端动态加载。
blog-springboot
├── annotation    --  自定义注解
├── aspect        --  aop模块
├── config        --  配置模块
├── constant      --  常量模块
├── consumer      --  MQ消费者模块
├── controller    --  控制器模块
├── dao           --  框架核心模块
├── dto           --  dto模块
├── enums         --  枚举模块
├── exception     --  自定义异常模块
├── handler       --  处理器模块（扩展Security过滤器，自定义Security提示信息等）
├── service       --  服务模块
├── strategy      --  策略模块（用于扩展第三方登录，搜索模式，上传文件模式等策略）
├── util          --  工具类模块
└── vo            --  vo模块
#### 项目特点

前台参考"Hexo"的"Butterfly"设计，美观简洁，响应式体验好。
后台参考"element-admin"设计，侧边栏，历史标签，面包屑自动生成。
采用Markdown编辑器，写法简单。
评论支持表情输入回复等，样式参考Valine。
添加音乐播放器，支持在线搜索歌曲。
前后端分离部署，适应当前潮流。
接入第三方登录，减少注册成本。
支持发布说说，随时分享趣事。
留言采用弹幕墙，更加炫酷。
支持代码高亮和复制，图片预览，深色模式等功能，提升用户体验。
搜索文章支持高亮分词，响应速度快。
新增文章目录、推荐文章等功能，优化用户体验。
新增在线聊天室，支持撤回、语音输入、统计未读数量等功能。
新增aop注解实现日志管理。
支持动态权限修改，采用RBAC模型，前端菜单和后台权限实时更新。
后台管理支持修改背景图片，博客配置等信息，操作简单，支持上传相册。
代码支持多种搜索模式（Elasticsearch或MYSQL），支持多种上传模式（OSS或本地），可支持配置。
代码遵循阿里巴巴开发规范，利于开发者学习。
![输入图片说明](image.png)
#### 技术介绍

前端   vue + vuex + vue-router + axios + vuetify + element + echarts

后端   SpringBoot + nginx + docker + SpringSecurity + Swagger2 + MyBatisPlus + Mysql + Redis + elasticsearch + RabbitMQ + MaxWell + Websocket

其他：  接入QQ，微博第三方登录，接入腾讯云人机验证、websocket
#### 开发环境
开发工具	说明
IDEA	Java开发工具IDE
VSCode	Vue开发工具IDE
Navicat	MySQL远程连接工具
Another Redis Desktop Manager	Redis远程连接工具
X-shell	Linux远程连接工具
Xftp	Linux文件上传工具
开发环境	版本
JDK	1.8
MySQL	8.0.20
Redis	6.0.5
Elasticsearch	7.9.2
RabbitMQ	3.8.5

1.  使用 Readme\_XXX.md 来支持不同的语言，例如 Readme\_en.md, Readme\_zh.md
2.  Gitee 官方博客 [blog.gitee.com](https://blog.gitee.com)
3.  你可以 [https://gitee.com/explore](https://gitee.com/explore) 这个地址来了解 Gitee 上的优秀开源项目
4.  [GVP](https://gitee.com/gvp) 全称是 Gitee 最有价值开源项目，是综合评定出的优秀开源项目
5.  Gitee 官方提供的使用手册 [https://gitee.com/help](https://gitee.com/help)
6.  Gitee 封面人物是一档用来展示 Gitee 会员风采的栏目 [https://gitee.com/gitee-stars/](https://gitee.com/gitee-stars/)
