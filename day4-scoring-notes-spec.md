# Day 4 评分注释规范（Scoring Notes Spec）

## 目标
- 避免“拍脑袋分数”。
- 让每个工具分数具备可解释性和可复查性。

## 维度定义（0-10）
- `quality`：输出质量与结果稳定度。
- `speed`：首结果产出速度与交互响应。
- `freeValue`：免费层可用性与性价比。
- `automation`：API/自动化能力与可编排程度。
- `ease`：新手上手难度与学习成本。
- `batch`：批量任务支持与吞吐表现。
- `reliability`：稳定性、可用性、异常失败率表现。

## 注释格式（每个工具至少 1 条）
- 建议结构：`结论 + 场景 + 限制`
- 示例：
  - `Most reliable for product cutouts, especially in batch workflows; free credits are limited.`
  - `Strong quality for social creatives; automation depth is moderate for teams.`

## 评分过程建议
1. 先按 7 维给原始分（0-10，可小数）。
2. 选择权重预设（balanced / free-first / quality-first ...）。
3. 用统一公式算综合分。
4. 记录 1 句评分依据，便于下次更新对比。

## 更新与复查
- 建议每月复查 1 次高流量垂类。
- 工具重大改版或价格变化时，优先更新 `freeValue / reliability / automation`。
