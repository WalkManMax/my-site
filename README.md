# my-site

我的第一个网站，多平台部署：

- **Cloudflare Workers**: https://my-site.1475744319.workers.dev （海外线路）
- **EdgeOne Pages**: 部署中（国内线路）

## 项目结构

```
public/index.html   网站页面
wrangler.jsonc      Cloudflare Workers 配置
package.json        依赖（wrangler）
```

## 本地开发与部署

```bash
npm install        # 安装 wrangler
npx wrangler dev   # 本地预览
npx wrangler deploy  # 部署到 Cloudflare Workers
```
