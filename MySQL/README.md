#### 连接数据库
mysql -h 主机名 -u 用户名 -p
本机主机名可忽略
没有密码不用-p

#### 数据库列表
show databases;

#### 创建数据库
create database asdf;

#### 选择数据库
use asdf;

#### 创建表
create table table1(
column1 integer);

#### 删除表
drop table table1;

#### 数据表列表
show tables;

#### 数据表属性
show columns from table1;

#### 数据表索引
show index from table1;

#### 数据库管理系统
show table status from asdf like 'table1';
like 表名以tanle1开头的表的信息

#### 退出MySQL
exit;
quit;

#### 修改表名
alter table old_name rename to new_name
rename table old_name to new_name

#### 增加字段
alter table table1 add column_name column_type;

#### 删除字段
alter table table_name drop column_name;

#### 修改字段名
alter table table_name change column_name new_column_name new_column_name_type;
