# MySQL命令

```shell
#开启
service mysql start

#关闭
service mysql stop

#重启
service mysql restart
```

```shell
#登录进入
mysql -u root -p 
```

```mysql
#显示数据库
show databases; # 注意分号

#创建数据库
create database serverdb;

#删除数据库
drop database 数据库名;

#使用数据库
use serverdb;

#创建表
CREATE TABLE user(
    username char(50) NULL,
    passwd char(50) NULL
)ENGINE=InnoDB;

#添加数据
INSERT INTO user(username, passwd) VALUES('name', 'passwd');

#显示表
show tables;

#显示数据表结构
describe 数据表名;
```

向表中添加数据

![image-20210206161430580](img/MySQL.img/image-20210206161430580.png)

# MySQL索引

索引：为了更快地查找到数据

MySQL的索引用的是B+树





# MySQL的存储引擎

存储引擎：用来存储组织数据的格式

 <img align='left' src="img/MySQL.img/image-20210506174012219.png" alt="image-20210506174012219" style="zoom:30%;" />



InnoDB

MyISAM







我的