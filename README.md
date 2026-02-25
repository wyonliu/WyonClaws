# WyonClaws Dashboard

怀洋超级智能体军团 · 指挥看板

## 部署说明

这是一个纯静态 HTML 页面，无需构建。

### Cloudflare Pages 部署步骤：

1. 打开 https://dash.cloudflare.com
2. 进入 Pages → Create a project
3. 选择 **Upload assets**（不是 Connect to Git）
4. 上传 `index.html` 文件
5. 完成部署

### 或者 Git 部署：

1. Pages → Connect to Git
2. 选择 `wyonliu/WyonClaws` 仓库
3. **Build settings:**
   - Build command: （留空，不填）
   - Build output directory: `/` 或 `.`
4. Deploy

## 文件说明

- `index.html` - 主页面（纯静态，无需构建）
- `package.json` - 占位文件（Cloudflare 要求）