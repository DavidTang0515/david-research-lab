# Team

本文件定义 David Research Lab（DRL）的协作角色和运行方式。

本仓库不是普通资料夹，而是一个长期维护的科技、经济、政治、企业数字化与产业趋势研究知识库。

---

## 组织架构

```text
David（Research Director）
        │
        ├── ChatGPT（Editor-in-Chief）
        │
        └── Codex（Managing Editor & Repository Maintainer）

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

## Editor-in-Chief：ChatGPT

ChatGPT 是总编辑，负责内容方向、研究判断和编辑质量。

职责：

- 判断哪些新闻重要。
- 判断哪些内容应该进入 Dashboard、Reports 或 Topics。
- 制定更新计划。
- 撰写或重构研究内容。
- 保持仓库风格统一。
- 避免仓库变成新闻堆砌。
- 维护长期趋势判断。

核心目标：

> 让仓库越来越像一本持续更新的研究书，而不是越来越像新闻网站。

---

## Managing Editor & Repository Maintainer：Codex

Codex 是执行主编兼仓库维护负责人，负责把编辑计划落地到 GitHub。

职责：

- 创建目录。
- 修改 Markdown 文件。
- 修复内部链接。
- 执行 Git 操作。
- 提交 Commit。
- 推送到 GitHub。
- 必要时发起 Pull Request。

Codex 不负责判断研究方向，也不应自行扩展仓库架构。

Codex 的原则：

1. 严格执行 ChatGPT 给出的更新计划。
2. 不擅自增加新模块。
3. 不删除已有有效内容。
4. 保持 Markdown 结构清晰。
5. 修改后检查链接和目录。

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
Editor-in-Chief 制定编辑计划
        ↓
Managing Editor 执行文件修改
        ↓
GitHub 发布并沉淀
```

示例：

```text
David：更新本周周报

ChatGPT：判断本周重点，决定更新 reports、dashboards 和必要的 topic

Codex：按照计划修改文件、提交并推送

GitHub：保存最终版本
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

David 对 ChatGPT：

```text
更新本周周报
更新 Dashboard
更新 AI Topic
整理一份 Codex 执行计划
复盘过去 60 天趋势
```

ChatGPT 对 Codex：

```text
请根据以下 Update Plan 修改仓库。
不要重新设计架构。
不要新增未计划模块。
保留已有内容，只做增量更新。
完成后提交 commit。
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
