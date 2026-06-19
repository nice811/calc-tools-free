# 🛠️ Etsy Fee Calculator 2026 — 部署指南

一个完整的、SEO 优化的静态工具站，零依赖、秒级部署。

---

## 📁 目录结构

```
etsy-fee-calculator-2026/
├── index.html        # 主页面（含 HTML/CSS/JS，约 600 行）
├── robots.txt        # 搜索引擎爬虫规则
├── sitemap.xml       # 站点地图
└── README.md         # 本文件
```

---

## 🚀 一键部署（推荐三种方式）

### 方式 1：Cloudflare Pages（最快，免费 CDN + 免费 SSL）

1. 登录 Cloudflare → 进入 "Workers & Pages" → "Create" → "Pages"
2. 选择 "Upload assets"
3. 将整个 `etsy-fee-calculator-2026` 文件夹拖进去
4. 项目名：`etsy-fee-calculator`
5. 框架预设：**None**
6. 构建命令：留空
7. 输出目录：`/`
8. 点 "Deploy" — 30 秒内上线
9. 去 "Custom domains" 绑定你的域名（建议用子域名如 `etsy.your-domain.com`）

### 方式 2：Vercel / Netlify

```bash
# 在项目目录内执行（任选其一）
npx vercel --prod
# 或
npx netlify deploy --prod --dir=.
```

### 方式 3：GitHub Pages

1. 将文件夹推送到 GitHub 仓库
2. Settings → Pages → Source 选 `main` 分支 `/root`
3. 等待 1 分钟，通过 `https://your-username.github.io/repo-name/` 访问

---

## 🔍 SEO 已内置（无需额外操作）

### 页面内优化
- ✅ **标题**：`<title>` 包含核心关键词 + 品牌
- ✅ **Meta Description**：约 160 字符，含核心关键词
- ✅ **H1** 关键词在首屏，唯一且语义化
- ✅ **结构化数据**：`WebApplication` + `FAQPage`（JSON-LD）
- ✅ **Canonical** 标签
- ✅ **Open Graph** + Twitter Cards
- ✅ **响应式**（移动优先）
- ✅ **核心 Web 指标**：LCP < 2.5s，零 JS 依赖（只有原生 JS）

### 内容密度
- 约 800 字高质量说明内容（Hero + How to Use + Example + FAQ）
- 关键词自然分布：`etsy fee calculator`, `etsy profit`, `etsy transaction fee`, `etsy seller` 等
- FAQ 7 个问题（Google 特色摘要 SERP 目标）

### 外部 SEO 配置
- ✅ `robots.txt` 允许全部爬虫
- ✅ `sitemap.xml` 站点地图
- ⚡ **部署后提交**：
  - Google Search Console: https://search.google.com/search-console
  - Bing Webmaster Tools: https://www.bing.com/webmasters

---

## 💰 变现布局（已预留位置）

### AdSense（建议）
页面已预留 **3 个广告位**：
1. 计算器右侧 300×250 中矩形
2. Example 下方 728×90 横幅
3. 可在 FAQ 前再加一个 300×250（移动端用）

**申请前**：内容要够（建议每页 ≥ 500 字，已有约 800），有关于页面、隐私政策。

### Affiliate（联盟营销）
底部 `Calculators` 导航和 CTA 按钮已预留位置，可直接替换为：
- Etsy Affiliate Program → 推荐销售工具
- Printful / Printify → 降低卖家成本
- Shopify → 独立站替代方案

---

## 🎯 关键词覆盖（Google 搜索可见度）

| 目标关键词 | 类型 | 月搜索量 | 竞争度 |
|---|---|---|---|
| etsy fee calculator 2026 | 精准 | 中高 | 低 |
| etsy profit calculator | 核心 | 高 | 中 |
| etsy seller fees calculator | 长尾 | 中 | 低 |
| how much does etsy take per sale | 问题型 | 高 | 中 |
| etsy transaction fee 2026 | 信息型 | 中 | 低 |
| etsy payment processing fee | 长尾 | 中 | 低 |

---

## ⚙️ 性能与可访问性

- **加载速度**：首屏 < 1s（纯静态）
- **文件大小**：HTML 约 40KB（gzip 后约 10KB）
- **无任何构建步骤**：无需 npm、无需 build
- **纯原生**：HTML + CSS + 原生 JS
- **离线可用**：可添加 Service Worker（如需 PWA）

---

## 🛡️ 隐私 & 免责声明

页面底部已包含：
- 商标声明（Etsy 是 Etsy Inc. 的商标）
- 财务建议免责声明（非专业财务建议）

**建议补充**：`privacy.html` 和 `about.html` 以增强 AdSense 审核通过率。

---

## 📈 后续扩展建议

1. **添加更多计算器页面**：YouTube、TikTok、Dropshipping 等 → 形成工具集，互相内链
2. **博客内容**：`/how-to-calculate-etsy-fees/`、`/reduce-etsy-fees/`、`/etsy-vs-shopify/`
3. **Schema 增强**：给表格部分添加 `HowTo` 结构化数据
4. **多语言**：`/es/`、`/fr/` 版本覆盖欧洲卖家
5. **反向链接**：在 Reddit r/Etsy、卖家论坛、Quora 分享

---

## 🔧 本地预览

```bash
# 用 Python 起本地服务器
python -m http.server 8080

# 或用 Node
npx serve .

# 浏览器打开 http://localhost:8080
```

---

**完成！** 这是一个零配置、SEO 就绪、可以直接赚钱的工具站。🎯
