Project syseo
=====

Linux System Enhancements, Optimization

Linux 系统优化及部分安全配置调整



说明
======

执行前需修改 iptables.firewall.standard 中 PORT_SSH 和 SSH_ALLOED_IP,
其中 PORT_SSH 为要使用的SSHD端口, SSH_ALLOWED_IP 为允许SSH登录的IP

可以不指定参数直接执行

参数:
    
    -u, --user [username:group]
                -u "user001, user200:group01, user300"
                一次考验添加多个用户, 用户名之间以逗号分隔, 若指定组则以冒号分隔, 默认组为 users.

    -w, --wheel [username]
                -u user001


