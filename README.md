# BUPT-Phshing
北邮沙河10.3.8.216的wifi钓鱼页面，基于python的flask


系统要求：linux

我用的是Ubuntu18.04.2LTS

其他要求：iptables，python的flask
还要解决网卡驱动

首先使用系统自带的功能创建一个wifi热点

我用的是https://blog.csdn.net/u012491646/article/details/80219973

然后修改hello.py的相应的网络ip地址和网卡接口名称

最后用sudo python3 hello.py

可以通过运行deleteRules.py删除nat表的PREPOUTING的所有规则（sudo）

pureserver.py则是直接运行服务器，不设置任何转发
