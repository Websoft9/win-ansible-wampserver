# 账号密码

<<<<<<< HEAD
使用Metabase，可能会用到的几组账号密码如下：

## Metabase

在初始化安装的时候由用户自行设置

## MySQL

* 管理员账号：*`root`*
* 管理员密码：存储在您的服务器指定文件中：*/credentials/password.txt*。建议通过云控制台直接连接服务器，进入命令终端，运行`cat /credentials/password.txt` 命令获取数据库密码：
   ![运行cat命令](https://libs.websoft9.com/Websoft9/DocsPicture/zh/common/catdbpassword-websoft9.png)

> 需要登录MySQL，请参考 [MySQL可视化管理](/zh/admin-mysql.md)
=======
使用WampServer，可能会用到的几组账号密码如下：

## WampServer

默认数据库登录账户及密码：root,密码请远程连接到服务器，查看桌面上的 password.txt 文件,当第一次登录系统时，请注意修改密码。
>>>>>>> ff6d63b8e7b270626d0e270dfea934781b6a043a

## Linux

* 主机地址：服务公网IP地址
<<<<<<< HEAD
* 连接方式：云控制台在线SSH 或 SFTP客户端工具 或 SSH客户端工具
=======
* 连接方式：云控制台终端 或 SFTP工具 或 SSH工具
>>>>>>> ff6d63b8e7b270626d0e270dfea934781b6a043a
* 管理员密码：创建服务器的时候自行设置，若不记得密码需要通过云控制台重置。
* 管理员账号：不同的云平台有一定的差异
   |  云平台   |  管理员账号   |
   | --- | --- |
   |  Azure   |  创建服务器的时候自行设置   |
   |  AWS   |  ubuntu   |
   |  阿里云，华为云，腾讯云   |  root   |