# 软件产品设计与体验工程 Skill

`product-design-engineering` 是一套面向 Codex 的软件产品设计 Skill，帮助 Agent 在开发过程中理解用户任务、借鉴优秀产品的设计逻辑、规划交互、协助实现并审查体验。

Skill 正文使用中文编写，目录名保留英文，便于作为 Skill 标识使用。

## 能力范围

- 覆盖 Web、桌面、移动端和开发者工具。
- 按任务复杂度决定是否研究 1–3 个参考产品。
- 重要功能先整理轻量设计简报；简单任务直接推进。
- 实现相关体验时检查关键流程、状态、一致性和平台习惯。
- 将有长期价值的设计决策沉淀到当前项目文档。

## 目录结构

```text
product-design-engineering/
├── SKILL.md
├── references/
│   ├── web.md
│   ├── desktop.md
│   ├── mobile.md
│   └── developer-tools.md
└── templates/
    ├── design-brief.md
    └── experience-review.md
```

## 安装

将整个 `product-design-engineering` 目录复制到 Codex 的 Skills 目录，例如：

```text
~/.codex/skills/product-design-engineering/
```

之后可在涉及产品流程、界面、交互或重要用户行为的软件任务中调用。
