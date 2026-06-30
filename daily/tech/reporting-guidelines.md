# 科技趋势日报与周报规范

本文件是 David Research Lab 总规则在科技趋势自动化场景下的专项补充。发生冲突时，以仓库根目录 `AGENTS.md`、`PROJECT_CONTEXT.md`、`RESEARCH_PHILOSOPHY.md` 和 `EDITORIAL_POLICY.md` 为准。

## 1. 定位

科技趋势日报负责记录过去 24 小时内经过筛选和核验的重要科技动态，并提炼初步趋势判断。

它不是科技新闻列表，也不是长期 Topic。它应回答：

1. 今天发生了什么重要科技变化？
2. 为什么值得关注？
3. 对普通人的工作、学习、消费和数字生活有什么影响？
4. 对企业、国企数字化、网络安全、数据治理和采购立项有什么启示？
5. 哪些内容只是短期事件，哪些内容可能成为长期趋势？
6. 是否需要进入周报、Topic 或 Dashboard？

核心原则：

> News → Trend → Knowledge → Judgment → Methodology

---

## 2. 执行频率

### 2.1 每日简报

- 执行时间：每日 08:30。
- 时区：Asia/Singapore。
- 覆盖窗口：默认过去 24 小时。
- 输出文件：`daily/tech/news-YYYY-MM-DD.md`。

### 2.2 每周沉淀

若执行日为周一，应同时生成科技趋势周报：

- 覆盖窗口：过去 7 天。
- 输出文件：`reports/YYYY/YYYY-MM-DD-weekXX.md`。
- 目标：将 daily reports 和外部信息源沉淀为 Dashboard 状态变化、Weekly Report、Topic 长期知识更新和下周 Watchlist。

---

## 3. 信息源策略

### 3.1 线索源

以下来源可作为每日科技动态线索入口：

- AI HOT：https://aihot.virxact.com/
- 少数派
- 爱范儿
- 36氪
- 晚点 LatePost
- 机器之心
- 量子位
- InfoQ 中文
- Solidot
- Hacker News
- The Verge
- TechCrunch
- Ars Technica
- MIT Technology Review

### 3.2 一级确认源

重要事实必须尽量回查一级来源：

- 公司官方博客、产品公告和开发者文档。
- 论文、arXiv、GitHub、技术文档和模型卡。
- 政府、监管部门、统计机构和国际组织。
- 公司财报、投资者关系材料和正式会议材料。

### 3.3 使用规则

1. 聚合站和媒体只作为线索入口，不能直接替代事实核验。
2. 未核实爆料只能标注为“待核实”或“待观察”，不得写成确定事实。
3. 不抓取登录、付费、反爬或明确不允许访问的内容。
4. 不伪装成人类绕过网站限制。
5. 来源冲突时，应写明差异和不确定性，不强行合并成确定结论。

---

## 4. 重点关注范围

每日筛选 5-8 条真正重要的科技动态，避免流水账。

优先关注：

- AI 模型、Agent、AI 搜索、AI 办公、企业 AI。
- 算力、GPU、HBM、数据中心、云厂商资本开支。
- 半导体、先进封装、出口管制、国产替代。
- 网络安全、数据安全、AI 安全、零信任。
- 企业数字化、国企数字化、OA / ERP / 知识库 / 流程自动化。
- 机器人、智能制造、自动驾驶。
- 低空经济、智慧交通、公共部门数字平台。
- 与科技相关的宏观、政策和地缘政治变化。

优先选择至少符合一项的内容：

- 影响长期科技方向。
- 影响企业数字化转型。
- 影响 AI 基础设施或半导体供应链。
- 影响网络安全、数据治理或合规。
- 影响国企数字化规划、采购、立项或治理。
- 影响普通人的工作、学习、消费或数字生活。
- 影响长期产业趋势观察。

---

## 5. 每日简报结构

```markdown
# YYYY-MM-DD 科技趋势每日简报

生成时间：
覆盖范围：

## 1. 今日摘要

用 3-5 条说明今天最重要的变化。

## 2. 今日重点动态

### 1. 事件标题

- 领域：
- 重要性：高 / 中 / 低
- 事实概述：
- 为什么重要：
- 长期知识：
- 是否影响 Dashboard：是 / 否
- 是否进入 Topic：是 / 否，原因
- 来源：

## 3. 今日趋势判断

| 领域 | 今日变化 | 趋势方向 | 说明 |
|---|---|---|---|
| AI | | Up / Stable / Watch / Down | |
| 半导体 | | Up / Stable / Watch / Down | |
| 网络安全 | | Up / Stable / Watch / Down | |
| 企业数字化 | | Up / Stable / Watch / Down | |
| 机器人/自动驾驶 | | Up / Stable / Watch / Down | |
| 低空经济 | | Up / Stable / Watch / Down | |
| 宏观与地缘 | | Up / Stable / Watch / Down | |

## 4. 对普通人的影响

说明 AI 工具与工作习惯、就业技能、消费电子价格、网络安全与隐私、出行和数字生活。

## 5. 对企业和国企数字化的启示

说明 AI 治理、数据治理、网络安全、国产化替代、采购和立项、智慧交通/低空经济等公共场景。

## 6. 投资观察

仅作为趋势观察，不构成投资建议。

## 7. 明日/本周继续观察

列出 5-8 个继续跟踪的线索。

## 8. Research Lab 趋势信号

如果没有达到晋级标准，写：

本期暂无需要晋级的趋势信号。
```

---

## 6. 周报结构

周报不是新闻列表，而是趋势沉淀。

```markdown
# YYYY-MM-DD 科技趋势周报

覆盖周期：

## 1. 本周摘要

## 2. 趋势雷达

| 领域 | 本周状态 | 趋势方向 | 重要性 | 说明 |
|---|---|---|---:|---|

## 3. 本周关键变化

按以下领域组织：

- AI
- 算力与半导体
- 网络安全与数据治理
- 企业数字化
- 机器人与智能制造
- 低空经济与智慧交通
- 宏观与地缘政治

每个领域至少回答：

- 本周发生了什么？
- 为什么重要？
- 长期知识是什么？
- 是否需要更新 Topic？

## 4. Topic 更新摘要

说明本周哪些 Topic 被更新，为什么更新。

只有 6-12 个月后仍有价值的知识才进入 Topic。

## 5. 对普通人的影响

## 6. 对企业和国企数字化的启示

## 7. 投资观察

仅作为趋势观察，不构成投资建议。

## 8. 下周 Watchlist

## 9. 本周结论
```

---

## 7. Topic 与 Dashboard 更新规则

### 7.1 Dashboard

只有趋势状态确实发生变化时，才更新 `dashboards/index.md`。

可使用状态：

- Up
- Stable
- Watch
- Down

不要因为单条新闻修改 Dashboard。

### 7.2 Topics

可更新的长期专题包括：

- `topics/ai.md`
- `topics/semiconductor.md`
- `topics/cybersecurity.md`
- `topics/digital-transformation.md`
- `topics/robotics.md`
- `topics/low-altitude-economy.md`
- `topics/macroeconomy.md`

不要把日报全文复制进 Topic。

只有符合以下条件之一，才进入 Topic：

- 6-12 个月后仍有解释价值。
- 多个事件共同指向同一结构性变化。
- 会影响企业、国企或产业长期决策。
- 会改变对某一技术路线、产业链或治理机制的理解。

---

## 8. 投资观察规则

投资相关内容必须保持克制。

允许：

- “值得继续观察”
- “适合进入观察池”
- “中长期逻辑较清晰”
- “短期风险较高”
- “趋势仍需验证”

禁止：

- “买入”
- “卖出”
- “满仓”
- “稳赚”
- “确定性机会”
- “抄底”
- 具体股票交易指令

必须包含：

> 仅作为趋势观察，不构成投资建议。

---

## 9. 发布规则

每次运行应：

1. 创建或更新 `daily/tech/news-YYYY-MM-DD.md`。
2. 更新 `daily/tech/README.md`，把最新日报放在 `Latest Reports` 首位。
3. 保留历史入口。
4. 有合格信号时创建 `daily/tech/trend-signals/YYYY-MM-DD.md`。
5. 若当天是周一，同时创建或更新 `reports/YYYY/YYYY-MM-DD-weekXX.md`。
6. 按需更新 `dashboards/index.md` 和相关 `topics/` 文件。
7. 更新 `CHANGELOG.md` 简短记录。
8. 推送后回读远端日报、栏目首页和被修改的长期文件，确认最终状态。

日常更新直接 commit 到 `main`，不创建 PR。

只有以下情况才创建 Draft PR：

- 仓库结构调整。
- 新增一级模块。
- 新增 Topic 或模板。
- 大规模重构。
- ChatGPT 战略评审或季度复盘后提出的系统性修改。

推荐 commit message：

```text
research: update tech daily YYYY-MM-DD
research: update tech weekly YYYY-MM-DD
research: update tech topic YYYY-MM-DD
```

---

## 10. 失败处理

如果搜索、来源访问、脚本或 GitHub 写入失败，必须说明：

- 失败原因。
- 已检查来源。
- 已完成部分。
- 日报是否部分生成。
- GitHub 是否同步成功。
- 趋势信号是否生成。

不得在未完成核验或未成功写入时声称已经发布。
