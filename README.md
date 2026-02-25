# Agent Dashboard - Cloudflare 部署指南

## 第一步：你在本地执行（需要浏览器授权）

```bash
# 1. 进入项目目录
cd /path/to/agent-dashboard

# 2. 登录 Cloudflare（会打开浏览器，你点一下授权）
npx wrangler login

# 登录成功后终端显示：Successfully logged in.
```

## 第二步：部署

```bash
# 3. 部署到 Cloudflare
npx wrangler pages deploy . --project-name agent-dashboard --branch main

# 部署完成后会给出地址：https://xxx.agent-dashboard.pages.dev
```

## 完整流程（复制粘贴）

```bash
# 1. 下载看板文件
curl -o index.html https://raw.githubusercontent.com/wyonliu/godrise/main/dashboard-web/index.html

# 2. 创建 wrangler.toml
cat > wrangler.toml << 'EOF'
name = "agent-dashboard"
compatibility_date = "2024-01-01"
EOF

# 3. 登录（浏览器操作）
npx wrangler login

# 4. 部署
npx wrangler pages deploy . --project-name agent-dashboard --branch main
```

## 部署后

告诉我部署地址（如 https://agent-dashboard-xxx.pages.dev），我配置 Mirror 每10分钟自动更新数据。

---

## Seer 分析报告位置

`/root/.openclaw/workspace/agent-7-seer/analysis/角色塑造评估报告_v1.md`

### 核心结论

| 维度 | 当前 | 目标 | 差距 |
|------|------|------|------|
| 角色塑造 | 7.5 | 9.5 | -2.0 |
| 情感共鸣 | 7.0 | 9.5 | -2.5 |
| 哲学深度 | 9.0 | 9.5 | -0.5 |
| 文学性 | 9.0 | 9.5 | -0.5 |
| 名场面 | 8.0 | 9.5 | -1.5 |
| **综合** | **8.1** | **9.5** | **-1.4** |

### 关键优化点

1. **增加父女闪回**（3-5处）- 船长目前出场太少
2. **强化麦洛独白** - 对"虚拟/真实"的思考
3. **维塔记忆碎片** - 铺垫 Cycle-6 身份
4. **新增"父女重逢"名场面** - 目前缺失

### 已验证名场面质量

- 第1章·入画：⭐⭐⭐⭐⭐（色彩、意境极佳）
- 第24章·山海谣：⭐⭐⭐⭐⭐（千人合奏史诗级）

---

**等你部署完看板，Seer 立即开始执行改写！**