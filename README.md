# YankeeBBR
来自Loc大佬Yankee魔改的BBR的Debian一键安装包


### 下载安装:
``` bash
wget -N --no-check-certificate https://raw.githubusercontent.com/ouba1/BBR/master/bbr.sh && bash bbr.sh install

然后根据提示重启系统。

重启完成后，运行

bash bbr.sh start
启动魔改版BBR

查看魔改BBR状态

sysctl net.ipv4.tcp_available_congestion_control
如果看到有 tsunami 或bbr 就表示开启成功！
如果都没有就用逗比的bbr
