# XbotGo 用户调研洞察

Falcon 买家问卷（Zigpoll，2026 年 9–10 月）× Shopify 订单的可筛选仪表盘。纯静态页面：`index.html` + `data.json`，图表用 d3（jsDelivr CDN）。

## 部署到 GitHub Pages
1. 新建仓库，把本目录全部文件（含 `.nojekyll`）放到仓库根目录并推送。
2. 仓库 Settings → Pages → Source 选 “Deploy from a branch”，Branch 选 `main` / `(root)`，保存。
3. 约 1 分钟后访问 `https://<用户名>.github.io/<仓库名>/`。可加 `#insights`、`#explore`、`#compare` 直接打开对应标签页。

## 更新数据
替换 `data.json`（同样的字段）后推送即可。

## 隐私
`data.json` 已去除姓名、邮箱、电话、地址，但包含每位受访者的回答、原话和订单配件。GitHub Pages 站点对所有人公开（即使仓库是私有的，除非使用 GitHub Enterprise 的私有 Pages）。
