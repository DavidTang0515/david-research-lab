# User Guide

本文件面向 David Research Lab 的日常使用者，说明如何阅读、更新和维护这个研究知识库。

---

## 1. 如何使用这个仓库

本仓库用于沉淀科技、经济、政治、产业和企业数字化趋势，不用于简单收集新闻。

使用时优先问三个问题：

1. What happened?
2. Why does it matter?
3. What long-term knowledge should be retained?

---

## 2. 推荐阅读顺序

第一次阅读：

1. `README.md`：了解仓库结构。
2. `PROJECT_CONTEXT.md`：了解项目定位和 AI 协作关系。
3. `daily/`：查看最新日报和趋势信号。
4. `dashboards/index.md`：快速查看当前趋势状态。
5. `reports/`：查看阶段性变化。
6. `topics/`：查看长期专题沉淀。

日常阅读：

1. 先看需要关注的 Daily。
2. 再看 Dashboard。
3. 再看最近一篇周报或月报。
4. 最后进入相关 Topic 深读。

---

## 3. Daily、Dashboard、Reports、Topics 的区别

| 模块 | 回答的问题 | 更新方式 |
|---|---|---|
| Daily | 今天发生了什么？ | 高频、可追溯、保留来源和初步判断 |
| Dashboard | 当前世界处于什么状态？ | 高频、简短、只保留摘要 |
| Reports | 最近发生了什么变化？ | 按周、月、年记录 |
| Topics | 长期怎么看这个领域？ | 持续更新，沉淀知识 |

不要在不同层级重复写同一段内容。Daily 是输入，长期内容需要重新提炼。

---

## 4. 典型工作流

### 更新游戏日报

1. 读取 `daily/game/reporting-guidelines.md`。
2. 按上次生成后至本次生成时的增量窗口收集信息。
3. 更新 `daily/game/news-YYYY-MM-DD.md`。
4. 更新 `daily/game/README.md` 最新入口。
5. 有结构性价值时，生成 `daily/game/trend-signals/YYYY-MM-DD.md`。
6. 不直接用单期日报修改 Topic 或 Dashboard。

### 更新本周周报

1. 收集本周重要变化。
2. 区分经济、科技、政治、产业和投资变量。
3. 写入 `reports/YYYY/YYYY-MM-DD-weekXX.md`。
4. 必要时同步更新 Dashboard。
5. 只有长期价值明确时，才更新 Topic。

### 更新 Dashboard

1. 检查各领域状态是否变化。
2. 更新趋势等级和一句话判断。
3. 保持简洁，不写成长文。

### 更新 Topic

1. 判断事件是否具备长期意义。
2. 更新已有专题文件。
3. 不因为单条新闻创建新 Topic。
4. 在 Update Log 记录更新原因。

---

## 5. 周维护流程

每周维护一次：

1. 更新本周周报。
2. 检查 Dashboard 是否需要调整。
3. 标记需要持续观察的指标。
4. 判断是否有内容值得沉淀到 Topic。

周报原则上写完后不反复修改。

---

## 6. 月维护流程

每月维护一次：

1. 回顾本月周报。
2. 提炼月度主线。
3. 检查 Topic 是否需要补充长期判断。
4. 清理重复、短期、情绪化内容。

月度维护重点是复盘趋势，不是罗列新闻。

### 阶段性复盘

周、月、季度、半年和年度复盘应按以下路径处理：

```text
新闻
↓
归纳
↓
趋势
↓
进入 Topic
↓
更新 Dashboard
```

复盘不是记录过去一段时间发生了什么，而是提炼这段时间留下了什么值得未来 5 年继续保留的知识。

执行时应先写阶段性 Report，再判断哪些内容需要沉淀到 Topic，最后检查 Dashboard 是否需要更新。

## 7. 信息收集与更新节奏

信息收集以长期研究主题为边界，不做全网新闻搬运。

| 节奏 | 主要任务 | 主要落点 |
|---|---|---|
| 周 | 收集重要事件，识别短期变化 | Reports |
| 月 | 归纳重复信号，提炼阶段主线 | Reports / Topics |
| 季度 | 检查结构性变化和长期判断 | Topics / Dashboard |
| 半年 | 复盘重要主题的方向是否变化 | Topics / Dashboard |
| 年度 | 总结年度主线和长期知识资产 | Topics / Reports |
| 重大事件 | 判断是否影响长期趋势 | Reports，必要时 Topics / Dashboard |

优先使用官方机构、国际组织、公司官方、主流媒体和研究机构。社交媒体、自媒体和市场传闻只能作为线索，不能作为核心事实。

---

## 8. Research Director 常用指令

David 可以直接提出：

- 更新本周周报
- 更新 Dashboard
- 更新 AI Topic
- 更新半导体 Topic
- 更新网络安全 Topic
- 更新本月月报
- 做季度复盘
- 做半年复盘
- 做年度复盘
- 根据以下 Editorial Plan 直接更新仓库

AI 应主动判断文件位置和最小修改范围。

---

## 9. GitHub 协作方式

默认直接更新 `main`。

标准流程：

```text
提出更新计划 → David 确认 → 修改文件 → Commit → Push 到 main → 汇报结果
```

每次更新只解决一个明确主题。

避免把用户手册、Dashboard、Topic 和周报混在同一次更新中。

### 什么时候直接提交

| 场景 | 默认方式 |
|---|---|
| 日报更新 | 直接 Commit |
| 每周更新 | 直接 Commit |
| Dashboard 更新 | 直接 Commit |
| Topic 更新 | 直接 Commit |
| 周报更新 | 直接 Commit |
| 月报更新 | 直接 Commit |

### 什么时候使用 PR

| 场景 | 默认方式 |
|---|---|
| 架构调整 | PR |
| 新模块 | PR |
| ChatGPT 参与重构 | PR |
| 大版本发布 | PR |

日常维护以效率为先，保留 Git History 和 `CHANGELOG.md` 即可。
