---
Author: suhan
---

# Nocturne

> A quiet dark theme for focused Markdown writing, technical notes, and long-form reading.

Nocturne is designed around a deep violet-gray background, soft accent colors, and carefully balanced Markdown elements. It keeps everyday writing calm while making structure, code, tables, quotes, and highlights easy to scan.

Nocturne 使用深紫灰色背景、柔和的紫色强调色、清晰的代码样式，以及针对 Markdown 阅读和写作细节优化过的排版。它适合专注写作、技术笔记、知识库整理和长时间阅读。

---

## Writing Experience

A good Markdown theme should disappear while you write, but still make structure visible when you need it. **Nocturne emphasizes clarity** with readable spacing, calm colors, and a wider GitHub-like writing area.

You can use it for [technical documentation](https://typora.io), personal knowledge bases, project notes, or long essays. It also supports ==highlighted text==, inline code like `nocturne.css`, superscript x^2^, and subscript H~2~O.

### Design Goals

- Comfortable dark-mode reading
- Clear heading hierarchy
- Distinct code and inline styles
- Balanced contrast for long writing sessions
- Clean tables, quotes, and task lists

### Theme Checklist

- [x] Dark violet-gray palette
- [x] Source mode readability
- [x] Code block cursor visibility
- [x] Full table borders
- [x] System font stack
- [ ] More preview screenshots

---

## Code Preview

Inline code uses a warm accent, while code blocks use a deeper panel background and syntax colors tuned for readability.

```python
from dataclasses import dataclass

@dataclass
class Theme:
    name: str
    background: str
    accent: str

theme = Theme(
    name="Nocturne",
    background="#211d25",
    accent="#b080ff",
)

def describe(theme: Theme) -> str:
    return f"{theme.name} is calm, readable, and quietly polished."

print(describe(theme))
```