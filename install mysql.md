#安装mysql:

> brew install mysql

设置mysql为开机启动项目:

> ln -sfv /usr/local/opt/mysql/*.plist ~/Library/LaunchAgents

启动mysql

> mysql.server start

设置密码：

> mysql_secure_installation



运行mysql_secure_installation会执行几个设置：

a)为root用户设置密码

b)删除匿名账号

c)取消root用户远程登录

d)删除test库和对test库的访问权限

e)刷新授权表使修改生效