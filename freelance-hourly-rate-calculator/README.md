# 💼 Freelance Hourly Rate Pricing Calculator — 部署指南

面向自由职业者、顾问和独立创作者的费率计算工具。现代绿色极简设计。

## 📁 文件

```
freelance-hourly-rate-calculator/
├── index.html
├── robots.txt
├── sitemap.xml
└── README.md
```

## 🚀 部署

1. **Cloudflare Pages**（推荐）：上传文件夹 → 绑定域名
2. **Vercel**：`cd freelance-hourly-rate-calculator && npx vercel --prod`
3. **Netlify**：`npx netlify deploy --prod --dir=.`

## 🔍 SEO

- `WebApplication` + `FAQPage` JSON-LD
- H1 / H2 / H3 语义层级清晰
- OG + Twitter Cards
- 约 800 字内容 + 5 FAQ

### 关键词
- freelance pricing calculator
- freelance hourly rate calculator
- how much should i charge freelance
- consultant hourly rate
- freelance pricing formula

## 💰 变现

### AdSense
2 个广告位（右侧 300×250 + 中部 728×90）

### Affiliate
- Upwork / Fiverr Pro / Toptal（推荐平台）
- 工具/软件（Notion, Figma, QuickBooks）
- 课程/教育（Skillshare, Udemy affiliate）
- 账户/法务服务（LLC 推荐）

## 📝 内容扩展

- `/freelance-hourly-rate-calculator/value-based-pricing-guide/`
- `/freelance-hourly-rate-calculator/how-often-raise-rates/`
- `/freelance-hourly-rate-calculator/freelance-taxes-self-employed/`

## 🛠️ 本地预览

```bash
cd freelance-hourly-rate-calculator
python -m http.server 8080
# 浏览器 → http://localhost:8080
```

## ✨ 功能

- 收入目标 + 营业支出 + 税 + 账单小时数
- 利润缓冲（dry spell margin）
- 实时小时费率 + 月度/周度/日度收入目标
- 9 个行业的基准费率表（入门/中级/专家）
- 6 FAQ
- 现代绿色极简主题（Fraunces 衬线标题）
