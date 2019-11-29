
# 一键安装Trojan

[Trojan released 最新发布版本](https://github.com/trojan-gfw/trojan/releases/)

在 Debian 10 安装成功

```shell
    wget https://raw.githubusercontent.com/st286/st286.github.io/master/Trojan/trojan-first-install-debain.sh
    
    bash trojan-first-install-debain.sh
    
    # 按提示操作
```

**配置文件和证书、密钥文件在目录： /usr/local/etc/trojan/**

**修改 服务器、客户端配置文件：config.json、client.json ( 密码和证书、密钥 )**

**运行启动Trojan**

    systemctl start trojan

**设置开机启动**

    systemctl enable trojan

**查看运行状态**

    systemctl status trojan


### 详细安装参考[这里](./install.md)
    
    