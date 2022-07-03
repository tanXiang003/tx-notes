# Linux装telnet服务

1、需要安装openbsd-inetd

命令：sudo apt-get install openbsd-inetd -y

2、安装telnetd
命令：sudo apt-get install telnetd -y

3、重启openbsd-inetd
命令：sudo /etc/init.d/openbsd-inetd restart

4、查看telnet运行状态
命令：sudo netstat -a | grep telnet

5、登录

telnet IP address
