# Agent Playbook

个人 AI 编程规则、UI 设计规范、Skills 与提示词资料库。

这个仓库的目标是将日常开发中验证过的经验整理成可阅读、可复用、可持续改进的文档，适用于 Codex、Claude Code、Gemini CLI、DeepSeek Harness 等工具。

## 内容目录

| 目录 | 用途 |
| --- | --- |
| [rules](rules/) | Agent 通用规则、语言规范与开发流程 |
| [design](design/) | UI 设计原则与视觉风格 |
| [skills](skills/) | 可复用的 Agent 技能 |
| [prompts](prompts/) | 按任务使用的提示词 |
| [examples](examples/) | 规则和规范的实际应用示例 |

## 设计规范（第一批）

- [间距系统](design/principles/spacing.md)
- [字体与文字层级](design/principles/typography.md)
- [颜色与对比度](design/principles/colors.md)
- [对齐与视觉层级](design/principles/alignment-and-hierarchy.md)
- [组件一致性](design/principles/components.md)
- [界面设计检查清单](design/principles/ui-review-checklist.md)

## 使用方式

1. 从目录中挑选与当前项目相关的规范，而非要求 Agent 一次性读取全部文档。
2. 在项目的 `AGENTS.md` 或对应工具的说明文件中引用需要的文档。
3. 对有争议的规则保留来源、适用场景与例外，不把个人偏好写成绝对标准。
4. 新规则先在实际项目中验证，再合并到通用规范。

## 说明

- `rules/global/AGENTS.md` 等个人规则暂未写入，等待整理现有内容，避免使用随意生成的规则覆盖自己的实际规范。
- `skills/` 目前保留目录，后续加入可执行的 `SKILL.md`。
- 仓库中的数值建议不是所有项目的强制要求；已有设计系统和组件主题优先。

欢迎逐步完善。