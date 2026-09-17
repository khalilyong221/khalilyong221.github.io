# khalilzheng.cn

khalilzheng 的个人站点。

- **线上地址**：https://khalilzheng.cn
- **托管**：GitHub Pages（`main` 分支根目录，静态托管，无构建步骤）
- **DNS**：腾讯云 DNSPod（NS `pollux.dnspod.net` / `money.dnspod.net`）

## 目录结构

```
index.html    首页
404.html      自定义 404 页
CNAME         GitHub Pages 自定义域名（内容只写域名本身）
.nojekyll     关掉 Jekyll 处理，静态文件按原样发布
```

## 改内容怎么改

直接编辑 `index.html` 提交到 `main`，GitHub Pages 会在一分钟左右自动重新部署。
没有构建流程、没有依赖、没有打包——就是要"改完就生效"。

## 配色

`#121212` 底色 + `#1ed760` 点缀，暗色极简。改色改 `<style>` 里的 `:root` 变量即可。
