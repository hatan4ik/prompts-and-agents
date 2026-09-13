# Refactor prompts

4 copy-paste prompts from Anthropic’s official Claude Code prompt library. Replace values in `{braces}` with your own context.

## 01 · Migrate A Pattern Across

**Workflow stage:** `build`

**Prompt**

```text
migrate everything from {from} to {to}: identify every place that needs to change, then make the changes
```

**Example values**

| Placeholder | Example |
| --- | --- |
| `{from}` | the old logging API |
| `{to}` | the structured logger |

*Source family: Common workflows*

---

## 02 · Port Code Between Languages

**Workflow stage:** `build`

**Prompt**

```text
port {source} to {target}, keeping the same {keep}
```

**Example values**

| Placeholder | Example |
| --- | --- |
| `{keep}` | public API and test behavior |
| `{source}` | this Python module |
| `{target}` | Rust |

*Source family: How Anthropic teams use Claude Code*

---

## 03 · Optimize Against A Measurable

**Workflow stage:** `build` · **Useful for:** `data`

**Prompt**

```text
optimize {target} to bring {metric} from {current} down to under {goal}
```

**Example values**

| Placeholder | Example |
| --- | --- |
| `{current}` | 2s |
| `{goal}` | 500ms |
| `{metric}` | p95 latency |
| `{target}` | the search query |

*Source family: ebook*

---

## 04 · Fix A Precise Visual

**Workflow stage:** `build` · **Useful for:** `design`

**Prompt**

```text
the {element} extends {amount} beyond the {container} on {viewport}. fix it.
```

**Example values**

| Placeholder | Example |
| --- | --- |
| `{amount}` | 20px |
| `{container}` | card border |
| `{element}` | login button |
| `{viewport}` | mobile |

*Source family: ebook*

---
