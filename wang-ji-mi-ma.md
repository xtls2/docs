# 忘记密码

**如果你忘记了当前机器人使用的激活码，可在服务器在命令行中使用以下方法进行查询**

### 方法一：

```
systemctl status bate
```

```
//可见输出：
//激活成功 到期时间： 1638288000000
//当前激活码： free_652307m0o6tu7t0wurwq5oukpyghci1n
```

### 方法二：

```
bate -pass=true
//可见输出：
//当前激活码： free_652307m0o6tu7t0wurwq5oukpyghci1n
```
