# Day 4 Deliverables (v1)

## 已完成
- 评分字段固化为 7 维：
  - `quality/speed/freeValue/automation/ease/batch/reliability`
- 权重预设固化为 7 组：
  - `balanced/free-first/quality-first/automation-first/speed-first/ease-first/batch-first`
- 评分注释规范文档完成：
  - `day4-scoring-notes-spec.md`

## 代码落地
- `index.html`
  - 数据集新增 `reliability`
  - 权重预设新增 `reliability` 权重
  - 图表维度新增 `Reliability`
- `route-view.html`
  - 数据模型与权重同步升级到 7 维
  - 结果表格新增 `Reliability` 列
- `vertical-template.html`
  - 数据模型与权重同步升级到 7 维
  - 增加按 `Reliability` 排序
  - 结果表格新增 `Reliability` 列
- `taxonomy-v1.json`
  - 默认评分维度补充 `reliability`

## 新增文件
- `day4-scoring-model-v1.json`
- `day4-scoring-notes-spec.md`
- `day4-v1-deliverables.md`

## Day 5 建议承接
- 按路线图上线 3 个核心垂类的“多图表可切换”页：
  - Background Remover
  - Text to Video
  - AI Keyword Research
