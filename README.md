# AI Tools Directory（项目100）纯导航版

## 1. 项目定位
- 站点类型：AI 工具导航站（仅工具卡片 + 外链跳转）。
- 内容策略：不写文章，不做对比长文，不做教程页。
- 核心目标：用户 `3` 秒内找到工具并点击跳转。

## 2. 当前交付
- `index.html`：主导航页（分类、搜索、卡片、外跳）。
- `about.html` / `contact.html` / `privacy-policy.html` / `disclaimer.html` / `terms.html`：合规页面。
- `robots.txt` / `sitemap.xml` / `ads.txt`：SEO 与广告基础文件。
- `vercel.json`：Vercel 部署与路由配置。
- `tools-catalog.md`：工具清单母表（用于增删工具）。
- `site-design.md`：页面结构与交互规则。
- `roadmap.md`：7天上线与维护节奏。

## 3. 使用方式
- 本地直接打开 `index.html` 即可使用。
- 每新增工具时，同步更新：
  - `tools-catalog.md`
  - `index.html` 中的工具卡片

## 4. 维护规则（极简）
- 只保留可访问、可用、更新频率正常的工具。
- 每个工具最多 2 行描述，避免内容膨胀。
- 外链统一新窗口打开：`target="_blank"`。

## 5. 下一步
- 先补齐你常用的 30-50 个 AI 工具。
- 如果需要，再做第二版功能：收藏、点击统计、置顶推荐。

## 6. Vercel 上线（一次性）
- 在该目录执行：`npx vercel`
- 当前生产域名：`https://100-ai-tools-directory.vercel.app`
- 如果开通 AdSense，更新 `ads.txt` 为你的 `pub` 号。
- 合规页联系邮箱已设置为：`pqiswin1@gmail.com`。
