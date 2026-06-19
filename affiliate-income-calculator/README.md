# 🌱 Affiliate Income Calculator 2026 — 部署指南

面向联盟营销、Niche Site、博客作者的收入预测工具。绿色户外衬线风格。

## 📁 文件

```
affiliate-income-calculator/
├── index.html
├── robots.txt
├── sitemap.xml
└── README.md
```

## 🚀 部署

1. **Cloudflare Pages**：上传文件夹 → 绑定自定义域名
2. **Vercel**：`cd affiliate-income-calculator && npx vercel --prod`
3. **Netlify**：`npx netlify deploy --prod --dir=.`

## 🔍 SEO

- `WebApplication` + `FAQPage` JSON-LD
- H1 / H2 / H3 语义层级
- OG + Twitter Cards
- 约 800 字内容 + 6 FAQ

### 目标关键词
- affiliate income calculator
- affiliate marketing earnings estimator
- how much do affiliate marketers make
- affiliate commission calculator
- blog revenue calculator

## 💰 变现

### AdSense
2 个预配置广告位（侧栏 300×250 + 中部 728×90）

### Affiliate
- **Amazon Associates** — 1–10% 产品佣金
- **ShareASale / CJ / Awin** — 零售商联盟
- **Web hosting (Bluehost, SiteGround, WP Engine)** — 高佣金 $50–$200
- **SaaS (ConvertKit, Notion, Airtable, ClickUp)** — 经常是 recurring revenue
- **课程 / 教育** — $50–$200 单次

## 📝 内容扩展

- `/affiliate-income-calculator/highest-commission-niches/`
- `/affiliate-income-calculator/good-affiliate-conversion-rate/`
- `/affiliate-income-calculator/traffic-to-make-1000-month/`

## 🛠️ 本地预览

```bash
cd affiliate-income-calculator
python -m http.server 8080
# 浏览器 → http://localhost:8080
```

## ✨ 功能

- 访客 × CTR × 转化率 × 佣金 + LTV factor 完整模型
- 月度/年度收入预测
- 每 1K visits 的平均收入 / Effective CPC
- Niche 表格（10 个领域）
- 3 步式收入公式解释
- 6 个 FAQ 针对 SERP
- 绿色森林/自然风格主题（衬线字体）
