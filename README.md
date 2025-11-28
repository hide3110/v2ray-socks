# v2ray socks5脚本

这个 Bash 脚本可以帮助你快速部署 v2ray socks5 代理服务器。

### 一键脚本自定义
自定义端口参数如：PORT=61031 USER=yyds01 PASS=b346e6ff-cad9-4cdd-b621-8b3bc51a0ca7，使用时请自行定义此参数！
```bash
PORT=61031 USER=yyds01 PASS=b346e6ff-cad9-4cdd-b621-8b3bc51a0ca7 sh <(curl -fsSL https://raw.githubusercontent.com/hide3110/v2ray-socks/main/install.sh)
```
### 指定版本号
可以脚本前添加v2ray版本号变量，如VER=v5.38.0
```
VER=v5.38.0 PORT=61031 USER=yyds01 PASS=b346e6ff-cad9-4cdd-b621-8b3bc51a0ca7 sh <(curl -fsSL https://raw.githubusercontent.com/hide3110/v2ray-socks/main/install.sh)
```
### 缷载
```bash
sh <(curl -fsSL https://raw.githubusercontent.com/hide3110/v2ray-socks/main/uninstall.sh)
```

## 详细说明

- 此脚本仅安装了socks5协议


