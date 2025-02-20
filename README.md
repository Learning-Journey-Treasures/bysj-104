# 1.项目介绍
- 系统角色：管理员、普通用户
- 功能模块：用户管理、菜品分类管理、菜品管理、食材信息、收藏管理、资讯、笔记点赞、趣味答题等
- 技术选型：SpringBoot，thymeleaf等
- 测试环境：idea2024，jdk1.8，mysql5.7，maven3
# 2.项目部署
- 创建数据库，导入sql文件
- idea打开目录deliciousFoods-main，根据本地数据库环境修改 src/main/resources/application.yml  6-9行 （如果你本地数据库是8.0的，注意替换pom里依赖的版本、以及第三行配置serverTimezone，这都是基础，百度遍地都是。）
- 启动项目：src/main/java/com/example/Application.java
- 前端：http://localhost:8080/front/index.html   用户登录自行查表
- 后端管理web：http://localhost:8080/ssmdmkas/admin/dist/login.html   管理员账号密码：admin/123456
# 3.项目部分截图
![输入图片说明](1.png)
![输入图片说明](2.jpg)
![输入图片说明](3.jpg)
![输入图片说明](4.jpg)
![输入图片说明](5.jpg)
![输入图片说明](6.jpg)
![输入图片说明](7.jpg)
![输入图片说明](8.jpg)
![输入图片说明](9.jpg)

# 4.获取方式
[戳我查看](https://gitee.com/aven999/mall)
