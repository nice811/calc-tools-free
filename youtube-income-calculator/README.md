# 🎬 YouTube Income Calculator 2026 — 部署指南

面向 YouTube 创作者的收入估算工具，深色主题、完整 SEO、零依赖。

---

## 📁 文件结构

```
youtube-income-calculator/
├── index.html    # 主页面（单文件：HTML+CSS+JS）
├── robots.txt    # 搜索引擎爬虫规则
├── sitemap.xml   # 站点地图
└── README.md     # 本文件
```

---

## 🚀 部署方式（任选其一）

### 方式 1：Cloudflare Pages（推荐，免费 + 全球 CDN）
1. Cloudflare → Workers & Pages → Create → Pages → Upload assets
2. 项目名：`youtube-income-calculator`
3. 上传整个文件夹 → Deploy
4. Custom domains 绑定你的域名（如 `youtube.your-domain.com`）

### 方式 2：Vercel
```bash
cd youtube-income-calculator
npx vercel --prod
```

### 方式 3：Netlify
```bash
npx netlify deploy --prod --dir=.
```

### 方式 4：GitHub Pages
推送到 GitHub 仓库，Settings → Pages → Source 选 `main`

---

## 🔍 SEO 内置清单

### 技术 SEO
- ✅ 响应式（移动优先）
- ✅ HTTPS 就绪（部署平台自动提供）
- ✅ `<title>` 60 字符内，含核心关键词
- ✅ meta description ≈ 150 字符
- ✅ Canonical 标签
- ✅ robots.txt + sitemap.xml
- ✅ Schema.org：`WebApplication` + `FAQPage`
- ✅ Open Graph + Twitter Cards
- ✅ 语义化 HTML（H1, H2, H3 层级）
- ✅ 页面内容约 800 字

### 关键词策略（SERP 目标）

| 关键词 | 搜索意图 |
|---|---|
| youtube income calculator per views | 🛠️ 工具意图 |
| youtube earnings calculator | 🛠️ 工具意图 |
| youtube money estimator | 🛠️ 工具意图 |
| how much do youtubers make | ❓ 信息意图 |
| youtube rpm by niche | ❓ 信息意图 |
| how much does youtube pay per 1000 views | ❓ 问题意图 |
| youtube subscriber income | ❓ 信息意图 |
| is youtube shorts worth it | ❓ 对比意图 |

---

## 💰 变现方案

### AdSense
页面已预留 2 个广告位（右上 300×250 + 中部 728×90）
- **建议**：申请 AdSense 前添加 `about.html` + `privacy.html`

### Affiliate / 联盟营销
- **TubeBuddy / vidIQ**：创作者工具联盟（$5–$20/转化）
- ** Epidemic Sound**：无版权音乐 — 创作者刚需
- **Canva Pro**：缩略图设计
- **设备推荐**：相机、麦克风（Amazon Associates）

替换底部 "More Tools" 和导航 CTA 按钮的链接即可。

---

## 🔗 内容扩展（快速拉升 SEO）

在同域名下添加以下 `/blog/` 或 `/guides/` 内容：

1. `/how-much-do-youtubers-make/` — 详细分 Niche 案例
2. `/youtube-rpm-by-niche/` — 数据密集型页面（已在工具里，但可独立成页）
3. `/1000-subscribers-earn-youtube/` — 新手爆款题
4. `/youtube-shorts-monetization-rpm/` — 高搜量话题
5. `/how-to-increase-youtube-rpm/` — 行动指南

这些页面**内链回**计算器页面，提升工具页权重。

---

## 🛠️ 本地预览

```bash
cd youtube-income-calculator
python -m http.server 8080
# 浏览器打开 http://localhost:8080
```

---

## 📊 功能概览

| 功能 | 说明 |
|---|---|
| 实时计算 | 滑块 / 数字输入实时更新结果 |
| 多维度输出 | 日、月、年收入 + 年度浏览量 + 里程碑 |
| Niche 预设 | Finance/Tech/Gaming/Beauty 等一键切换 RPM |
| Shorts 混合 | 可设置 Shorts 占比，自动折算 RPM |
| FAQ Schema | 5+ 问答，瞄准 Google 特色摘要 |
| 深色主题 | 符合 YouTube 视觉氛围，CTR 更高 |
