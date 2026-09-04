# Server Service Navigator

`139.196.115.78` 的静态服务导航页，部署在 `81` 端口。页面不依赖外部字体或脚本。

## 部署

```bash
cd /srv/server-service-navigator
git pull --ff-only
nginx -t && systemctl reload nginx
```

Nginx 配置示例见 `server-service-navigator.conf`。
