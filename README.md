# rrshareweb
debian9一键安装人人影视WEB
简单的写了个debian9能通过的一键脚本

wget -N --no-check-certificate "https://github.com/GodOnlyKnowsXZY/-/blob/master/rrclc.sh" && chmod +x rrclc.sh && ./rrclc.sh

修改端口路径/home/rrshareweb/conf/rrshare.json 更改port

systemctl restart rr 重启服务
systemctl stop rr 停止服务
systemctl start rr 开启服务
systemctl disable/enable rr 停止/允许开机自启
