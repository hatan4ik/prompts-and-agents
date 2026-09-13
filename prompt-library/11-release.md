# Release prompts

2 copy-paste prompts from Anthropic’s official Claude Code prompt library. Replace values in `{braces}` with your own context.

## 01 · Draft Release Notes From

**Workflow stage:** `ship` · **Useful for:** `pm`, `docs`, `marketing`

**Prompt**

```text
compare {from} to {to} and draft release notes grouped by feature, fix, and breaking change
```

**Example values**

| Placeholder | Example |
| --- | --- |
| `{from}` | v2.3.0 |
| `{to}` | v2.4.0 |

*Source family: Common workflows*

---

## 02 · Write A Ci Workflow

**Workflow stage:** `ship` · **Useful for:** `ops`

**Prompt**

```text
write a GitHub Actions workflow that {steps} on every push to {branch}
```

**Example values**

| Placeholder | Example |
| --- | --- |
| `{branch}` | main |
| `{steps}` | runs the tests and deploys to staging |

*Source family: Common workflows*

---
