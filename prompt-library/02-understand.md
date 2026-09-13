# Understand prompts

6 copy-paste prompts from Anthropic’s official Claude Code prompt library. Replace values in `{braces}` with your own context.

## 01 · Explain Unfamiliar Code

**Workflow stage:** `discover`

**Prompt**

```text
explain what {path} does and how data flows through it. write it up as {format}
```

**Example values**

| Placeholder | Example |
| --- | --- |
| `{format}` | an HTML page with a diagram, then open it in my browser |
| `{path}` | src/scheduler/queue.ts |

*Source family: Common workflows*

---

## 02 · Find Where Something Happens

**Workflow stage:** `discover`

**Prompt**

```text
where do we {behavior}?
```

**Example values**

| Placeholder | Example |
| --- | --- |
| `{behavior}` | validate uploaded file types |

*Source family: Common workflows*

---

## 03 · See What Depends On

**Workflow stage:** `discover`

**Prompt**

```text
what would break if I deleted {target}?
```

**Example values**

| Placeholder | Example |
| --- | --- |
| `{target}` | the retryWithBackoff helper |

*Source family: Common workflows*

---

## 04 · Trace How Code Evolved

**Workflow stage:** `discover`

**Prompt**

```text
look through the commit history of {path} and summarize how it evolved and why
```

**Example values**

| Placeholder | Example |
| --- | --- |
| `{path}` | internal/auth/session.go |

*Source family: Best practices*

---

## 05 · Scope A Change Before

**Workflow stage:** `discover` · **Useful for:** `pm`, `design`

**Prompt**

```text
which files would I need to touch to {change}?
```

**Example values**

| Placeholder | Example |
| --- | --- |
| `{change}` | add a dark mode toggle to settings |

*Source family: How Anthropic teams use Claude Code*

---

## 06 · Ask The Codebase A

**Workflow stage:** `discover` · **Useful for:** `pm`

**Prompt**

```text
I am a {role}. walk me through what happens when a user {action}, from the UI down to the result
```

**Example values**

| Placeholder | Example |
| --- | --- |
| `{action}` | clicks Export to PDF |
| `{role}` | PM |

*Source family: How Anthropic teams use Claude Code*

---
