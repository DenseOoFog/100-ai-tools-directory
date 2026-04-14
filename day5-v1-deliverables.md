# Day 5 Deliverables (v1)

## 已完成
- 上线第一批 3 个核心垂类页面（通过统一实验页承载）：
  - Background Remover
  - Text-to-Video
  - AI Keyword Research
- 每个垂类均满足：
  - 4-6 个工具数据
  - 多图表切换可用（Bubble / Rank Bar / Radar / Parallel）
  - 参数权重切换可用（Balanced / Free-first / Quality-first / Automation-first）
  - Top 推荐卡片可用

## 代码交付
- 新增：`vertical-lab.html`
  - 支持 3 个核心垂类切换与独立 URL 参数进入
- 更新：`vercel.json`
  - 新增 SEO 友好路由：
    - `/background-remover`
    - `/text-to-video`
    - `/keyword-research`
- 更新：`sitemap.xml`
  - 新增上述核心垂类 URL 收录

## 访问方式
- `/background-remover`
- `/text-to-video`
- `/keyword-research`

## Day 6 建议承接
- 默认图表改为每类最直观图（例如 bgremove 默认 bubble、keywordresearch 默认 parallel）。
- 增加“参数解释”轻弹层，说明每个权重档位适合谁。
