# -SpringBoot-Hadoop-Vue
网盘分布式系统，毕业设计SpringBoot+Hadoop+Vue
​
下载地址：http://ym.maptoface.com/2021/07/22/%e7%bd%91%e7%9b%98%e5%88%86%e5%b8%83%e5%bc%8f%e7%b3%bb%e7%bb%9f%ef%bc%8c%e6%af%95%e4%b8%9a%e8%ae%be%e8%ae%a1springboothadoopvue/

项目介绍
网盘分布式系统，毕业设计SpringBoot+Hadoop+Vue

系统说明
总体设计
2.1 运行环境
编程语言：Java、Mybatis、Spring、SpringBoot、SpringCloud、Node、Vue
开发环境：Windows 10 + Mysql
开发工具：WebStorm、IDEA编译器、Git、Maven
应用部署服务器：SpringBoot内置Tomcat插件
Node服务器：Node v10.15.3
数据库：Mysql v5.5.59
缓存服务：Redis v2.8.9
代码仓库管理系统：GitHub
服务器环境：处理器Core i5以上
2.2 基本处理流程
企业网盘系统的使用者分为企业普通员工和企业管理员，所以进行的基本处理流程是不一样的。企业普通员工进入本系统前台主界面后看到的是首页数据大盘，系统右上角有用户的头像和系统公告通知。在首页顶部的位置有个欢迎用户功能，此模块会根据用户登录的时间，人性化的对用户进行打招呼，比如用户深夜的时候登陆系统，该提示语会提醒“已经深夜了，你还在加班吗，请注意休息！”。当用户点击我的网盘模块后，系统首先会请求一次接口，展示自己网盘里面的文件，该用户可以对文件进行相关的操作。在分享模块中，用户可以选择不同的tab栏，分别对已共享、已接收的文件进行查看。当用户进入存储库模块时，单击不同的文档分类以查看已分类的文档，可以对文件进行查询，预览和下载。系统管理员发布通知后，系统前台会在系统右上角进行消息条数的提醒，点击消息红点后，会出现通知下拉列表框，再点击下拉列表里面的查看更多，可以进入更多模块下的系统公告列表页面，在该页面里面，用户可以通过标题关键字，公告发布的时间范围进行搜索，在更多模块下用户可以动态切换系统主题，然后让用户无感知的记录用户行为，当用户退出登录后重新登录，系统的主题还是用户退出登录时所选择的主题。
管理员和超级管理员成功登入系统后台后，默认会调到Index页面去，在该首页，我们可以看到登录用户、服务器运行相关信息。在数据大盘模块，可以看到最近上传文件的数量，以及最近一段时间的上传曲线图。系统超级管理员可以管理系统所有的功能和所有用户，如果需要控制系统用户能访问的菜单，系统管理员只需更改相关角色所拥有的菜单列表。

适用场景：
毕业论文、课程设计、公司项目参考

运行截图


关注【程序代做 源码分享】公众号获取更多免费源码！！！


 

​
