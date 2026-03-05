# 🧠 学习记录 (LEARNINGS.md)

记录纠正、知识缺口、最佳实践。

## 条目格式

```markdown
## [LRN-YYYYMMDD-XXX] category
**Logged**: ISO-8601 timestamp
**Priority**: low | medium | high | critical
**Status**: pending | in_progress | resolved | promoted | wont_fix
**Area**: frontend | backend | infra | tests | docs | config

### Summary
One-line description of what was learned

### Details
Full context: what happened, what was wrong, what's correct

### Suggested Action
Specific fix or improvement to make

### Metadata
- Source: conversation | error | user_feedback | knowledge_gap
- Related Files: path/to/file.ext
- Tags: tag1, tag2
- See Also: LRN-20250110-001 (if related to existing entry)
- Pattern-Key: simplify.dead_code | harden.input_validation (optional, for recurring-pattern tracking)
- Recurrence-Count: 1 (optional)
- First-Seen: 2025-01-15 (optional)
- Last-Seen: 2025-01-15 (optional)

---
```

## 优先级定义

| 优先级 | 使用场景 |
|--------|----------|
| `critical` | 阻塞核心功能、数据丢失风险、安全问题 |
| `high` | 显著影响、影响常用工作流、重复问题 |
| `medium` | 中等影响、存在变通方案 |
| `low` | 轻微不便、边缘情况、锦上添花 |

## 状态定义

| 状态 | 含义 |
|------|------|
| `pending` | 待处理 |
| `in_progress` | 正在处理 |
| `resolved` | 已解决 |
| `promoted` | 已提升到项目文件 |
| `wont_fix` | 决定不处理 (需在 Resolution 中说明原因) |

## 分类 (Category)

| 分类 | 说明 |
|------|------|
| `correction` | 用户纠正或自我纠正 |
| `knowledge_gap` | 知识缺口、信息过时 |
| `best_practice` | 发现更好的方法 |
| `gotcha` | 工具/平台陷阱 |
| `workflow` | 工作流改进 |

---

*暂无学习记录*
