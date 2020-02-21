## V2Ray一键安装脚本 记录

V2Ray底层 伪造的https协议

要求：Ubuntu 16+ / Debian 8+ / CentOS 7+ 系统
推荐使用 Debian 9 系统，脚本会自动启用 BBR 优化。


使用 root 用户输入下面命令安装或卸载

bash <(curl -s -L https://git.io/v2ray.sh)

端口必须使用 443 端口.
走 SSL通道, 



备注：安装完成后，输入 v2ray 即可管理 V2Ray


#### 配置文件路径
V2Ray 配置文件路径：/etc/v2ray/config.json
Caddy 配置文件路径：/etc/caddy/Caddyfile
脚本配置文件路径: /etc/v2ray/233blog_v2ray_backup.conf

#### 及时更新脚本

为确保你能愉快使用，请留意使用 v2ray update.sh 命令来更新管理脚本。
脚本难免会有 BUG，所以建议有空就检查一下更新情况。
