# 参数

<<<<<<< HEAD
Metabase 预装包包含 Metabase 运行所需一序列支撑软件（简称为“组件”），下面列出主要组件名称、安装路径、配置文件地址、端口、版本等重要的信息。

## 路径

### Metabase

Metabase 安装目录： */data/wwwroot/metabase*  
Metabase 配置文件： */data/wwwroot/metabase/metabase.conf*  

> Metabase 配置文件中包含数据库连接信息，更改了 MySQL 数据库账号密码，此处也需要对应修改

### Java

Java Directory: */usr/lib/jvm*

### Nginx

Nginx 虚拟主机配置文件：*/etc/nginx/sites-available/default.conf*  
Nginx 主配置文件： */etc/nginx/nginx.conf*  
Nginx 日志文件： */var/log/nginx/*

### MYSQL

MySQL 安装路径: */usr/local/mysql*  
MySQL 数据文件 */data/mysql*  
MySQL 配置文件: */etc/my.cnf*    
MySQL 可视化管理地址: *http://服务器公网IP:9090*，用户名和密码请见 [账号密码](/zh/stack-accounts.md) 章节。


## 端口号

系统所用到的端口号，请通过官方文档 [Package defaults](https://docs.gitlab.com/omnibus/package-information/defaults.html) 查阅。在云服务器中，通过 **[安全组设置](https://support.websoft9.com/docs/faq/zh/tech-instance.html)** 来控制（开启或关闭）端口是否可以被外部访问。 

本应用建议开启的端口如下：

| 名称 | 端口号 | 用途 |  必要性 |
| --- | --- | --- | --- |
| HTTP | 80 | 通过http访问GitLab | 必须 |
| HTTPS | 443 | 通过https访问GitLab | 可选 |
| MySQL | 3306 | 远程连接MySQL | 可选 |
| phpMyAdmin on Docker | 9090 | 可视化管理MySQL | 可选 |

## 版本号

组件版本号可以通过云市场商品页面查看。但部署到您的服务器之后，组件会自动进行更新导致版本号有一定的变化，故精准的版本号请通过在服务器上运行命令查看：

```shell
# Linux Version
lsb_release -a

# Java Version
java --version

# Nginx version:
nginx -v

# MySQL version:
mysql -V

# Dokcer:
docker --version
```
=======
## 组件及路径

WampServer部署包中包含了一系列网站运行所需的其他软件（这里称之为组件），下面列出主要组件名称、安装路径、配置文件地址等重要的信息：

### WampServer

WampServer安装目录: C:\websoft9\wampserver

### Apache

Apache 虚拟主机配置文件：C:\websoft9\wampserver\bin\apache\apache2.4.39\conf\extra\httpd-vhosts.conf

Apache 主配置文件： C:\websoft9\wampserver\bin\apache\apache2.4.39\conf\httpd.conf 

Apache 日志文件： C:\websoft9\wampserver\logs\

### MySQL

MySQL 存储目录：C:\websoft9\wampserver\bin\mysql\mysql5.7.26\data

MySQL 配置文件：C:\websoft9\wampserver\bin\mysql\mysql5.7.26\my.ini   

MySQL 日志目录：C:/websoft9/wampserver/logs/mysql.log 

MySQL 可视化管理地址: http://服务器公网IP/phpmyadmin

### MariaDB

### PHP
配置文件路径：C:\websoft9\wampserver\bin\php\php5.6.40\php.ini
             C:\websoft9\wampserver\bin\php\php7.0.33\php.ini
             C:\websoft9\wampserver\bin\php\php7.1.29\php.ini
             C:\websoft9\wampserver\bin\php\php7.2.18\php.ini
             C:\websoft9\wampserver\bin\php\php7.3.5\php.ini

## 端口号

下面是您在使用本镜像过程中，需要用到的端口号，请通过云控制台安全组进行设置

| 名称 | 端口号 | 用途 |  必要性 |
| --- | --- | --- | --- |
| HTTP | 80 | http访问端口 | 必须 |
| HTTPS | 443 | https访问端口 | 可选 |
| MySQL | 3306 | MySQL远程连接端口 | 可选 |

## 版本号

组件对应的基本版本号可以通过云市场商品页面查看，但部署到您的服务器之后，版本会有一定的升级，故更为精准的版本请通过在服务器上运行命令查看：

查看安装目录
>>>>>>> ff6d63b8e7b270626d0e270dfea934781b6a043a
