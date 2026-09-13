# Plan prompts

4 copy-paste prompts from Anthropic’s official Claude Code prompt library. Replace values in `{braces}` with your own context.

## 01 · Plan A Multi File

**Workflow stage:** `design` · **Useful for:** `pm`, `design`

**Prompt**

```text
plan how to refactor the {target} to {goal}. list the files you would change, but don't edit anything yet
```

**Example values**

| Placeholder | Example |
| --- | --- |
| `{goal}` | support multiple currencies |
| `{target}` | payment module |

*Source family: Common workflows*

---

## 02 · Draft A Spec By

**Workflow stage:** `design` · **Useful for:** `pm`

**Prompt**

```text
I want to build {feature}. interview me about implementation, UX, edge cases, and tradeoffs until we have covered everything, then write the spec to SPEC.md
```

**Example values**

| Placeholder | Example |
| --- | --- |
| `{feature}` | per-workspace rate limits |

*Source family: Best practices*

---

## 03 · Turn A Meeting Into

**Workflow stage:** `design` · **Useful for:** `pm`

**Prompt**

```text
read {input} and write up the action items, then create a {tracker} ticket for each with acceptance criteria
```

**Example values**

| Placeholder | Example |
| --- | --- |
| `{input}` | @meeting-notes.md |
| `{tracker}` | Linear |

**Requires:** `tracker`

*Source family: How Anthropic teams use Claude Code*

---

## 04 · Map Edge Cases Before

**Workflow stage:** `design` · **Useful for:** `design`, `pm`

**Prompt**

```text
list the error states, empty states, and edge cases for {feature} that the design needs to cover
```

**Example values**

| Placeholder | Example |
| --- | --- |
| `{feature}` | the file upload flow |

*Source family: How Anthropic teams use Claude Code*

---
