# Linux

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



tmux不生效时，`tmux kill-server`，然后`tmux source ~/.tmux.conf   `

配置文件都放在`~/`下

`apt 和 apt-get 区别不大`

`apt update`是更新软件源

`apt upgrade`是更新软件包
