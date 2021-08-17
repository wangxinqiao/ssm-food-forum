# ssm美食论坛系统带论文

## 项目介绍
````
该项目主要分为前台与后台；
前台主要功能包括：
登录、注册；首页、我发表的贴子、意见建议；版块列表、帖子查看、发贴回贴等；
普通用户登录后，主要功能有：
我的主页、用户中心、基本设置、版主申请、我的关注、屏蔽用户、我的私信等；
后台主要功能包括：
会员管理：禁言、封号、删除等；
站内资讯：添加、编辑、删除等；
友情链接：添加、编辑、删除等；
版块管理：添加修改删除分类、撤销版主等；
帖子管理：迁移、精华、置顶、删除等；
版主审核：通过、拒绝等；
意见建议：回复、删除；
敏感字符：添加、编辑、删除敏感字符；
举报信息：查看被举报人、举报人、举报原因等；
````

源码获取：[ **点此获取** ](http://www.shuyue.fun/index.php?type=productinfo&id=231)

## 环境需要
````
1.运行环境：最好是java jdk 1.8，我们在这个平台上运行的。其他版本理论上也可以。
2.IDE环境：IDEA，Eclipse,Myeclipse都可以。推荐IDEA;
3.tomcat环境：Tomcat 7.x,8.x,9.x版本均可
4.硬件环境：windows 7/8/10 1G内存以上；或者 Mac OS；
5.是否Maven项目: 否；查看源码目录中是否包含pom.xml；若包含，则为maven项目，否则为非maven项目
6.数据库：MySql 5.7版本；
````

## 技术栈
````
1. 后端：Spring SpringMVC MyBatis
2. 前端：JSP+jQuery+LayUI
````

## 使用说明
````
1. 使用Navicat或者其它工具，在mysql中创建对应名称的数据库，并导入项目的sql文件；
2. 使用IDEA/Eclipse/MyEclipse导入项目，Eclipse/MyEclipse导入时，若为maven项目请选择maven;
若为maven项目，导入成功后请执行maven clean;maven install命令，配置tomcat，然后运行；
3. 将项目中db.properties配置文件中的数据库配置改为自己的配置;
4. 运行项目，输入http://localhost:8080/cateforumssm 登录 注：tomcat中配置路径必须为/cateforumssm
````

## 运行截图
![输入图片说明](https://images.gitee.com/uploads/images/2021/0817/224227_89195c83_9600035.jpeg "WechatIMG2074.jpeg")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0817/224246_80cf5030_9600035.jpeg "WechatIMG2075.jpeg")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0817/224255_2e62ee6e_9600035.jpeg "WechatIMG2076.jpeg")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0817/224306_4a1a1b4d_9600035.jpeg "WechatIMG2077.jpeg")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0817/224318_1859961e_9600035.jpeg "WechatIMG2078.jpeg")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0817/224327_0b106a51_9600035.jpeg "WechatIMG2079.jpeg")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0817/224334_055b10d9_9600035.jpeg "WechatIMG2080.jpeg")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0817/224344_70ba7a82_9600035.jpeg "WechatIMG2081.jpeg")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0817/224351_a1b04636_9600035.jpeg "WechatIMG2082.jpeg")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0817/224400_1cb2dce2_9600035.jpeg "WechatIMG2083.jpeg")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0817/224409_a5d0059b_9600035.jpeg "WechatIMG2084.jpeg")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0817/224422_70cdb5b5_9600035.jpeg "WechatIMG2085.jpeg")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0817/224431_3362c648_9600035.jpeg "WechatIMG2086.jpeg")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0817/224440_c2ff911c_9600035.jpeg "WechatIMG2087.jpeg")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0817/224451_ff5c311b_9600035.jpeg "WechatIMG2088.jpeg")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0817/224459_2015ec18_9600035.jpeg "WechatIMG2089.jpeg")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0817/224512_ccc485cd_9600035.jpeg "WechatIMG2090.jpeg")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0817/224520_b0002d81_9600035.jpeg "WechatIMG2091.jpeg")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0817/224528_7f0e6582_9600035.jpeg "WechatIMG2092.jpeg")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0817/224541_517d5bc8_9600035.jpeg "WechatIMG2095.jpeg")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0817/224558_ab9d71ee_9600035.jpeg "WechatIMG2097.jpeg")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0817/224606_a9c5a068_9600035.jpeg "WechatIMG2098.jpeg")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0817/224614_bef03e7a_9600035.jpeg "WechatIMG2099.jpeg")
