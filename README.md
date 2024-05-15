# mbzj

#### 介绍
mbzj cms,一个很简单的java内容管理系统，没有用什么复杂的框架，所有依赖jar包不足10M

#### 软件架构
软件架构说明
java+dbutils+mysql+jsp+nginx+tomcat10

java用的是最新JDK，不支持jdk8以下版本
dbutils简单的ORM
mysql5.7以上
nginx最新版
tomcat必须是tomcat10以上，不支持tomcat9
前端用的是jsp，这个很是古老的东西，有人喜欢就用吧，没人喜欢就算了
总之一切保持最新就好了

#### 安装教程

1.  下载源代码直接导入eclipse
2.  eclipse配置好tomcat直接运行
3.  数据库配置文件jdbc.properties

#### 使用说明

1. 后台配置也很简单
站点管理，修改网站基本信息
栏目管理，对应网站的前端栏目
文章管理，编辑修改文章内容
2.  模板标签
采用古老的自定义标签，前端jsp可以调用栏目内容、文章内容、单页面内容
3.  自定义标签请参考具体的文档


#### 参与贡献

演示地址：https://www.mbzj.net
1.  Fork 本仓库
2.  新建 Feat_xxx 分支
3.  提交代码
4.  新建 Pull Request


#### 特技

1.  使用 Readme\_XXX.md 来支持不同的语言，例如 Readme\_en.md, Readme\_zh.md
