# GenRank AI — GEO Platform

AI 驱动的生成式引擎优化（GEO）服务平台。

## 一键部署到 Vercel

### 方法一：Vercel CLI（推荐）

```bash
# 1. 安装 Vercel CLI
npm install -g vercel

# 2. 进入项目目录
cd genrank-ai-geo-platform

# 3. 登录 Vercel（浏览器授权）
vercel login

# 4. 部署！
vercel --prod
```

### 方法二：GitHub + Vercel 自动部署

1. 将项目推送到 GitHub：
```bash
git init
git add .
git commit -m "feat: initial GenRank AI GEO platform"
git remote add origin https://github.com/YOUR_USERNAME/genrank-ai.git
git push -u origin main
```

2. 访问 [vercel.com](https://vercel.com) → Import Project → 选择你的 GitHub 仓库
3. 点击 Deploy，30 秒内完成！

### 方法三：直接拖拽部署

访问 [vercel.com/new](https://vercel.com/new)，将整个项目文件夹拖拽到页面即可。

## 本地预览

```bash
npx serve . -p 3000
# 访问 http://localhost:3000
```

## 项目结构

```
aigeo-platform/
├── index.html      # 主页面（全部代码在此）
├── vercel.json     # Vercel 配置
├── package.json    # 项目配置
└── README.md       # 说明文档
```
