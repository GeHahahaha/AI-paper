# AI 研发工作流金融征文项目

本仓库用于准备 2026 年上海金融系统职工“人工智能+”金融科技创新应用大赛征文。

## 先看这四份

1. [征文要求解析](docs/planning/征文要求解析.md)：活动要求和评审重点。
2. [征文大纲](docs/planning/征文大纲.md)：当前唯一有效的正文结构。
3. [AI 全流程工作流设计](docs/design/AI全流程工作流设计.md)：Pi + MCP 总体技术方案。
4. [Harness 材料评估](docs/research/Harness材料评估与吸收建议.md)：机构投票案例的吸收与取舍。
5. [征文正文](docs/report/从单点辅助到可信协同_金融科技AI研发工作流设计与实践.md)：按大纲形成的 Markdown 参赛稿。

更完整的文件职责、事实边界和维护规则见 [AGENTS.md](AGENTS.md)。

## 当前文章主线

- 总体方案：Pi 自主执行 + MCP 受控连接 + 人工关键决策。
- 案例一：某存量金融业务系统的需求逆向与整系统重构，已经验收上线并正常运行。
- 案例二：开源组件漏洞的全机构项目排查与试点整改，已经完成真实任务闭环。
- 公共质量节点：每次提交触发 AI 代码审核。

## 目录

```text
docs/
  planning/      活动解析、征文思路、正文大纲
  design/        AI 全流程工作流技术设计
  research/      案例筛选和材料评估
  report/        Markdown 格式参赛正文
materials/
  competition/   活动原始 PDF
  internal/      内部报告和案例原始材料
diagrams/
  current/       当前正文图 1—图 4 的 Draw.io 工程源文件
  rendered/      供 Markdown 正文引用的高清 PNG
  reference/     早期或参考图
archive/         已弃用方案
```

当前已形成 Markdown 格式正文初稿和四张配套工程图。提交前仍需补齐可公开的平台运行指标、两个案例的准确统计口径和脱敏证据，并完成内部业务与合规审核。
