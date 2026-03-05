# ⚠️ 错误记录 (ERRORS.md)

记录命令失败、异常、意外行为。

## 条目格式

```markdown
## [ERR-YYYYMMDD-XXX] skill_or_command_name
**Logged**: ISO-8601 timestamp
**Priority**: high | critical
**Status**: pending | in_progress | resolved | wont_fix
**Area**: frontend | backend | infra | tests | docs | config

### Summary
Brief description of what failed

### Error
Actual error message or output

### Context
- Command/operation attempted
- Input or parameters used
- Environment details if relevant

### Suggested Fix
If identifiable, what might resolve this

### Metadata
- Reproducible: yes | no | unknown
- Related Files: path/to/file.ext
- See Also: ERR-20250110-001 (if recurring)

---
```

---

*暂无错误记录*
