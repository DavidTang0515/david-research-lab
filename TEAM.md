# Team

本文件定义 David Research Lab（DRL）的协作角色和运行方式。

本仓库不是普通资料夹，而是一个长期维护的科技、经济、政治、企业数字化与产业趋势研究知识库。

> The mission is not to collect news, but to transform news into long-term knowledge.  
> 我们的使命不是收集新闻，而是把新闻沉淀为长期知识。

---

## 组织架构

```text
David（Research Director）
        │
        ├── Codex（Chief Research Editor）
        │
        └── ChatGPT（External Editorial Board）

GitHub = Knowledge Base
```

---

## Research Director：David

David 是研究总监，负责方向和最终判断。

职责：

- 提出研究需求。
- 决定重点关注方向。
- 审核最终成果。
- 判断哪些内容值得长期沉淀。
- 决定仓库是否进入下一阶段建设。

典型需求：

```text
更新本周周报
更新 AI 专题
复盘过去半年趋势
分析低空经济对国企数字化的影响
```

David 不需要维护目录，不需要写 Markdown，也不需要处理 Git。

---

## Chief Research Editor：Codex

Codex 是日常主编，负责仓库的日常运营、研究内容维护和 GitHub 发布流程。

职责：

- 收集重要事件和趋势线索。
- 判断内容应该进入 Dashboard、Reports 或 Topics。
- 撰写、更新和重构研究内容。
- 维护 Dashboard。
- 维护 Topic。
- 维护 Report。
- 执行 Git 操作。
- 直接提交并推送到 main。
- 保持仓库风格统一。
- 避免仓库变成新闻堆砌。
- 维护长期趋势判断。

核心目标：

> 让仓库越来越像一本持续更新的研究书，而不是越来越像新闻网站。

---

## External Editorial Board：ChatGPT

ChatGPT 是外部编辑委员会，不参与日常维护，只在 David 邀请时参与战略性评审和重大方向建议。

职责：

- 战略评审。
- 架构评审。
- 长期趋势分析。
- 季度复盘。
- 重大 Topic 建议。
- 仓库质量评估。

ChatGPT 不负责例行周报、月报、Dashboard 和 Topic 的日常维护。

Codex 的原则：

1. 围绕 David 的研究方向开展日常维护。
2. 不擅自增加新模块。
3. 不删除已有有效内容。
4. 保持 Markdown 结构清晰。
5. 修改后检查链接和目录。
6. 每次更新直接推送到 main，并向 David 汇报结果。

---

## GitHub：Knowledge Base

GitHub 是最终知识库，负责保存所有研究成果。

内容分为三层：

| 层级 | 目录 | 作用 |
|---|---|---|
| Dashboard | `dashboards/` | 当前世界状态 |
| Reports | `reports/` | 阶段性变化记录 |
| Topics | `topics/` | 长期专题知识沉淀 |

---

## 标准工作流

```text
Research Director 提需求
        ↓
Chief Research Editor 执行仓库更新
        ↓
Codex 提交并推送到 main
        ↓
GitHub 发布并沉淀
```

示例：

```text
David：更新本周周报

Codex：判断本周重点，决定更新 reports、dashboards 和必要的 topic

Codex：按照计划修改文件、提交并推送

David：查看最终结果并提出下一步要求
```

---

## 三个核心原则

### 1. 不为复杂而复杂

仓库只围绕三类内容运行：

```text
Dashboard：现在怎么看
Reports：最近发生了什么
Topics：长期怎么看
```

除此之外，不轻易新增模块。

### 2. 新闻不是终点

新闻只是入口。

真正的价值链是：

```text
新闻 → 趋势 → 知识 → 判断 → 方法论
```

### 3. 每次更新都要有归属

任何内容进入仓库前，先判断它属于哪里：

| 内容类型 | 放在哪里 |
|---|---|
| 当前状态 | Dashboard |
| 最近变化 | Reports |
| 长期知识 | Topics |
| 协作规范 | AGENTS / TEAM |
| 研究方法 | RESEARCH_PHILOSOPHY |

---

## 常用角色指令

David 对 Codex：

```text
更新本周周报
更新 Dashboard
更新 AI Topic
复盘过去 60 天趋势
根据以下 Editorial Plan 直接更新仓库
```

David 邀请 ChatGPT：

```text
请对当前仓库做季度编辑评审。
请评估 Topic 结构是否合理。
请提出未来一个季度的研究重点建议。
```

---

## 项目目标

将 `tech-economy-trend-analysis` 建设为 David Research Lab 的核心知识库。

长期服务于：

- 科技趋势观察。
- 经济与政治环境判断。
- 企业数字化转型研究。
- 网络安全与数据治理研究。
- 产业长期趋势沉淀。

最终目标：

> 形成一套可长期维护、可复盘、可扩展、可交给 AI 协作的个人研究操作系统。
