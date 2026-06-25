# 造物池

个人创意作品管理工具，支持作品上传、AI生图展示、AI应用收藏。

## 功能

- **个人作品** — 上传、分类、搜索你的创意作品
- **AI生图** — 展示 AI 工具生成的视觉作品，记录提示词
- **AI应用** — 收藏常用 AI 应用链接，一键打开

## 部署

### GitHub Pages（推荐）

1. Fork 本仓库
2. 进入 Settings → Pages
3. Source 选择 `main` 分支，根目录 `/ (root)`
4. 保存后等待部署完成，访问 `https://<username>.github.io/<repo>/`

### 本地运行

1. 克隆仓库
2. 用浏览器直接打开 `index.html` 即可使用
3. 或启动本地服务器：`python -m http.server 8080`，访问 `http://localhost:8080`

## 数据说明

- 初始数据存储在 `data.json` 中
- 手动添加的作品保存在浏览器 localStorage 中
- 可通过右上角菜单导出/导入 JSON 数据备份

## 技术栈

纯前端 HTML/CSS/JS，零依赖，无需构建。