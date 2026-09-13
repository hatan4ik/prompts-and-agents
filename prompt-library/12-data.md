# Data prompts

2 copy-paste prompts from Anthropic’s official Claude Code prompt library. Replace values in `{braces}` with your own context.

## 01 · Analyze A Data File

**Workflow stage:** `operate` · **Useful for:** `data`, `pm`, `marketing`

**Prompt**

```text
read {file}, summarize the key patterns, and write the results to {output}
```

**Example values**

| Placeholder | Example |
| --- | --- |
| `{file}` | @reports/q1-signups.csv |
| `{output}` | an HTML page with charts, then open it in my browser |

**Bring with you:** `csv` output

*Source family: How Anthropic teams use Claude Code*

---

## 02 · Generate Variations From Performance

**Workflow stage:** `operate` · **Useful for:** `marketing`, `data`

**Prompt**

```text
read {file}, find the underperforming {items}, and generate {n} new variations that stay under {limit} characters
```

**Example values**

| Placeholder | Example |
| --- | --- |
| `{file}` | @ads-performance.csv |
| `{items}` | headlines |
| `{limit}` | 90 |
| `{n}` | 20 |

**Bring with you:** `csv` output

*Source family: How Anthropic teams use Claude Code*

---
