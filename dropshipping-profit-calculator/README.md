# 📦 Dropshipping Profit Calculator (Shopify) — 部署指南

面向 Shopify / WooCommerce / 一般电商卖家的利润计算器。蓝绿专业商务风格。

## 📁 文件

```
dropshipping-profit-calculator/
├── index.html
├── robots.txt
├── sitemap.xml
└── README.md
```

## 🚀 部署

1. **Cloudflare Pages**（推荐）：上传文件夹 → 绑定域名
2. **Vercel**：`npx vercel --prod`
3. **Netlify**：`npx netlify deploy --prod --dir=.`

## 🔍 SEO

- `WebApplication` + `FAQPage` JSON-LD
- 语义化 HTML / 响应式
- OG + Twitter Cards
- 约 800 字内容 + 6 FAQ

### 关键词
- dropshipping profit calculator shopify
- shopify profit calculator
- dropshipping margin calculator
- ecommerce profit calculator
- how to price dropshipping products

## 💰 变现

### AdSense
2 个内置广告位（右侧 300×250 + 中部 728×90）

### Affiliate
- Shopify 联盟计划
- AliExpress / CJ Dropshipping / Zendrop
- email/SMS 工具（Klaviyo / Postscript）
- 付费主题 / 插件（例：Debutify）
- Amazon Associates（设备推荐）

## 📝 可扩展内容页

- `/dropshipping-profit-calculator/what-is-good-margin/
- `/dropshipping-profit-calculator/cac-break-even/
- `/dropshipping-profit-calculator/shopify-fees/

## 🛠️ 本地预览

```bash
cd dropshipping-profit-calculator
python -m http.server 8080
# 打开 http://localhost:8080
```

## ✨ 功能

- 定价 / COGS / Shipping / CAC / Payment / Fixed 全变量
- 实时 margin 百分比 + 可视化条
- 月度收入 / 月度利润 / 保本订单数 / ROAS
- 5 个价格点对比表格
- FAQ + SEO schema
- 深蓝绿商务主题
