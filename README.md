#Transmission | Debian 安装


wget --no-check-certificate https://github.com/red1412/tr/raw/master/debian-transmission.sh

sh debian-transmission.sh
要最新版本输入lestest
要稳定版本输入stable
然后用户名密码还有登录端口输入
任意键继续完成安装

账号密码默认都是qnmlgdsb
默认下载路径/mnt/transmission/Downloads
可以将硬盘挂载在这个路径下

Installing qBittorrent

https://www.qbittorrent.org/download.php


sudo apt-get install qbittorrent-nox
qbittorrent-nox --webui-port=8081 -d
