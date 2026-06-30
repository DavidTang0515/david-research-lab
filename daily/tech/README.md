# 科技趋势日报

本栏目用于承接 David Research Lab 的科技趋势每日输入层。

它不是科技新闻收藏夹，而是从每日科技动态中筛选值得长期观察的信号，并为后续 Weekly Report、Dashboard 和 Topics 提供材料。

## Latest Reports

- [2026-06-30 科技趋势每日简报](./news-2026-06-30.md)

## 自动化入口

- 执行频率：每日 08:30，Asia/Singapore。
- 日报窗口：过去 24 小时。
- 周报窗口：若执行日为周一，同时汇总过去 7 天。
- 日常更新：直接 commit 到 `main`，不创建 PR。
- 重大结构调整、新 Topic、新模板、大规模重构或 ChatGPT 战略评审时，才创建 Draft PR。

## 主要文件

| 文件 | 用途 |
|---|---|
| `reporting-guidelines.md` | 科技趋势日报、周报和自动化执行规则 |
| `news-YYYY-MM-DD.md` | 每日科技趋势简报 |
| `trend-signals/YYYY-MM-DD.md` | 需要晋级到 Report / Topic / Dashboard 的趋势信号 |

## 内容流转

```text
科技动态线索
↓
每日简报
↓
趋势信号
↓
周报
↓
Topics / Dashboard
```

日报可以记录短期事件，但不得直接替代长期结论。只有经过连续观察、再次核验并具备 6-12 个月保留价值的内容，才进入 Topics 或 Dashboard。
