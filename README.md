# 软件安装

安装/升级/重装

常用命令

```
curl https://oss.goant.xyz/install.sh | bash #安装/升级/重装（默认开机自启）
systemctl start bate #启动
systemctl restart bate #重启
systemctl stop bate #停止
systemctl status bate #状态
systemctl disable bate #取消开机自启
systemctl enable bate #设置开机自启（安装脚本默认会设定）


#默认日志查看（若已自定义日志地址则自行更换）
cat /var/local/bate/log.log


```

