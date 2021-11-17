# 软件安装

安装/升级命令

```
curl https://oss.goant.xyz/install.sh | bash
```

默认配置文件位置：

```
/var/local/bate/config.json
```

默认配置：

```
{
    "data":"/var/local/bate/data.db",    //数据库存储位置
    "listen":"127.0.0.1:80",    //前端绑定地址
    "tls":false,        //是否启用HTTPS
    "cert":"",        //Https证书内容路径
    "key":"",        //https证书私钥路径
    "log":"log.log"    //日志输出储存位置
}
```
