# Day 2 映射表：关键词意图 -> 页面类型 -> 图表类型

## 使用说明
- 先判断关键词意图，再匹配页面模板和图表模板。
- 每个二级目录建议至少覆盖 3 类意图：`工具型`、`对比型`、`场景型`。

## A. 工具型关键词（Best/Top/Tools）
- 关键词特征：
  - `best ... tools`
  - `top ... tools`
  - `... software comparison`
- 页面类型：
  - `Vertical Category Hub`（二级目录主页面）
- 图表类型建议：
  - 主图：`Rank Bar`
  - 辅图：`Radar`
- 目标：
  - 快速给出 Top 推荐，承接高意图点击。

## B. 对比型关键词（A vs B / alternatives）
- 关键词特征：
  - `X vs Y`
  - `X alternatives`
  - `X vs Y vs Z`
- 页面类型：
  - `Comparison Page`
- 图表类型建议：
  - 主图：`Radar`
  - 辅图：`Bubble`
- 目标：
  - 展示差异和场景建议，提高停留与转化。

## C. 场景型关键词（for ecommerce/for beginners）
- 关键词特征：
  - `... for beginners`
  - `... for ecommerce`
  - `... for youtube/tiktok`
- 页面类型：
  - `Use-case Landing Page`
- 图表类型建议：
  - 主图：`Bubble`（场景维度）
  - 辅图：`Rank Bar`（推荐结果）
- 目标：
  - 场景匹配，降低决策成本。

## D. 免费导向关键词（free/free online）
- 关键词特征：
  - `free ...`
  - `... free online`
- 页面类型：
  - `Free-first Collection Page`
- 图表类型建议：
  - 主图：`Rank Bar`（free-first 权重）
  - 辅图：`Rose`（工具份额展示）
- 目标：
  - 承接大流量词，保证“免费可用性”解释清晰。

## E. 自动化导向关键词（api/batch/automation）
- 关键词特征：
  - `... api`
  - `bulk ...`
  - `automation ...`
- 页面类型：
  - `Automation-focused Page`
- 图表类型建议：
  - 主图：`Parallel`（多维强弱一眼看）
  - 辅图：`Rank Bar`（automation-first 权重）
- 目标：
  - 连接 B 端或进阶用户意图。

---

## 二级目录优先模板建议（Tier 1）

### 1) background-remover
- 推荐意图优先级：工具型 > 场景型 > 免费导向
- 默认图表：
  - `Bubble`（Quality vs Speed）
  - `Rank Bar`（Balanced / Free-first 可切换）

### 2) text-to-video
- 推荐意图优先级：工具型 > 对比型 > 场景型
- 默认图表：
  - `Radar`（能力面）
  - `Rank Bar`

### 3) keyword-research
- 推荐意图优先级：工具型 > 自动化导向 > 对比型
- 默认图表：
  - `Parallel`
  - `Rank Bar`（automation-first）

---

## 页面模板命名建议
- `hub-{level2}.html`：二级目录主页
- `compare-{toolA}-vs-{toolB}.html`：对比页
- `usecase-{level2}-{scenario}.html`：场景页
- `free-{level2}.html`：免费向页面
