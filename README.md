#CFBlog-pro
本项目**CFBlog-pro**是由基于[Arronlong/cfblog-plus](https://github.com/Arronlong/cfblog-plus/)二次开发而来，主要是按照我自己的想法做了很多完善。

## 与cfblog-plus相比，有哪些变更：

### 一些功能已实现

1. 修正404页面状态码

2. 删除default主题

3. 去除otherCode参数

4. robots.txt中不再自动添加sitemap,改为手动配置

5. sitemap.xml和search.xml不再支持从github action生成,全部改为实时生成

6. 若主题路径结尾处缺少斜线,不再自动补全

7. 少量注释修改

8. 默认图片留空,默认永久链接改为index.并将永久链接设为必填

### 一些功能已想好但未实现

1. 从theme中的404.html文件中获取404页面,并使404页面风格与主题一致

2. 整理静态资源,以便于一键迁移

3. 新增一些主题,其中大多来自群友

4. 去除代码中我觉得没有必要的部分

5. 主题简单优化

### 一些功能还在规划中


1.内置jsdelivr反代

2.前台与后台分离

3.修复"000NAN"错误


## 部署教程请看cfblog-plus作者arrontg大佬的文章:  [CFBlog-Plus搭建教程](https://blog.arrontg.cf/article/000004/.html)

> 他的版本和我的略有不同,先将就着看吧.以后我应该会写


## 原CFBlog-TG 讨论群: [@CloudflareBlog](https://t.me/cloudflareblog )
