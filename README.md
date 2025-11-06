# v2ray socks5脚本

这个 Bash 脚本可以帮助你快速部署 v2ray socks5 代理服务器。

### 一键脚本自定义
自定义端口参数如：PORT=61031 USER=yyds01 PASS=b346e6ff-cad9-4cdd-b621-8b3bc51a0ca7 (此为reality协议证书地址)，使用时请自行定义此参数！
```bash
PORT=61031 USER=yyds01 PASS=b346e6ff-cad9-4cdd-b621-8b3bc51a0ca7 bash <(curl -fsSL https://raw.githubusercontent.com/hide3110/sb-debian/main/install.sh)
```
### 指定版本号
可以脚本最后添加v2ray版本号，如1.11.4
```
PORT=61031 USER=yyds01 PASS=b346e6ff-cad9-4cdd-b621-8b3bc51a0ca7 bash <(curl -fsSL https://raw.githubusercontent.com/hide3110/sb-debian/main/install.sh)
```

## 详细说明

- 脚本使用的自签 TLS 证书（用于 Trojan）
- 此脚本仅安装了Trojan和reality两个协议


