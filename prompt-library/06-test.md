# Test prompts

3 copy-paste prompts from Anthropic’s official Claude Code prompt library. Replace values in `{braces}` with your own context.

## 01 · Write Tests Run Them

**Workflow stage:** `build`

**Prompt**

```text
write tests for {path}, run them, and fix any failures
```

**Example values**

| Placeholder | Example |
| --- | --- |
| `{path}` | app/parsers/feed.py |

*Source family: Common workflows*

---

## 02 · Drive Implementation From Tests

**Workflow stage:** `build`

**Prompt**

```text
write tests for {feature} first, then implement it until they pass
```

**Example values**

| Placeholder | Example |
| --- | --- |
| `{feature}` | the password reset flow |

*Source family: ebook*

---

## 03 · Fill Gaps From A

**Workflow stage:** `build`

**Prompt**

```text
read {report} and add tests for the lowest-covered files until each is above {target}%
```

**Example values**

| Placeholder | Example |
| --- | --- |
| `{report}` | coverage/coverage-summary.json |
| `{target}` | 80 |

*Source family: Common workflows*

---
