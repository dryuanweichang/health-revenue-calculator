# Health Revenue Calculator

医美机构大健康业务营收潜力测算器。

## 页面

- `index.html`：大健康营收潜力测算器
- `assessment.html`：大健康业务自建潜力评估预留页

## 部署到 Cloudflare Pages

1. 登录 Cloudflare。
2. 进入 Workers & Pages。
3. 选择 Create application。
4. 选择 Pages，再选择 Connect to Git。
5. 授权并选择 GitHub 仓库 `dryuanweichang/health-revenue-calculator`。
6. 构建设置保持静态站点：
   - Framework preset: None
   - Build command: 留空
   - Build output directory: `/`
7. 点击 Deploy。

后续只要更新 GitHub 仓库，Cloudflare Pages 会自动重新发布。
