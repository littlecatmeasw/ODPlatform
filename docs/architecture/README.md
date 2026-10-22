# docs/architecture — 架构决策记录(ADR)

这里存放 **ADR(Architecture Decision Record)**——把"为什么这么设计"写下来。

## 为什么要写 ADR

代码回答"怎么做",ADR 回答"**为什么**这么做"以及"**当时排除了什么**"。
半年后有人问"为什么非得是 Monorepo",答案在这里,而不是在某个人的记忆里。

## 格式

每份 ADR 一个文件,命名 `ADR-<编号>-<短横线主题>.md`,包含:

| 字段 | 说明 |
|---|---|
| 状态 | Proposed / Accepted / Superseded |
| 决策日期 | 哪天定的 |
| 背景 | 当时面对什么问题 |
| 备选方案 | 考虑过哪些,为什么没选 |
| 决定 | 最终选了哪个 |
| 理由 | 为什么是它 |
| 后果 | 正面 / 负面 / 中性 |
| 撤销条件 | 什么情况下该重新评估 |

## 索引

- [ADR-001: 采用 Monorepo + apps/ 布局](./ADR-001-monorepo.md) — ✅ Accepted
