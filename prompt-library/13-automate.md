# Automate prompts

4 copy-paste prompts from Anthropic’s official Claude Code prompt library. Replace values in `{braces}` with your own context.

## 01 · Turn A Recurring Task

**Workflow stage:** `operate`

**Prompt**

```text
create a /{name} skill for this project that {steps}
```

**Example values**

| Placeholder | Example |
| --- | --- |
| `{name}` | ship |
| `{steps}` | runs the linter and tests, then drafts a commit message |

*Source family: Common workflows*

---

## 02 · Add A Hook For

**Workflow stage:** `operate`

**Prompt**

```text
write a hook that {action} after every {event}
```

**Example values**

| Placeholder | Example |
| --- | --- |
| `{action}` | runs prettier |
| `{event}` | edit to a .ts or .tsx file |

*Source family: Best practices*

---

## 03 · Connect A Tool With

**Workflow stage:** `operate`

**Prompt**

```text
set up the {server} MCP server so you can read my {data} directly
```

**Example values**

| Placeholder | Example |
| --- | --- |
| `{data}` | error reports |
| `{server}` | Sentry |

*Source family: Common workflows*

---

## 04 · Capture What To Remember

**Workflow stage:** `operate` · **Useful for:** `pm`, `docs`

**Prompt**

```text
summarize what we did this session and suggest what to add to CLAUDE.md
```

*Source family: How Anthropic teams use Claude Code*

---
