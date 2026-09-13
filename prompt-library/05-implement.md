# Implement prompts

7 copy-paste prompts from Anthropic’s official Claude Code prompt library. Replace values in `{braces}` with your own context.

## 01 · Follow An Existing Pattern

**Workflow stage:** `build`

**Prompt**

```text
look at how {example} is implemented to understand the pattern, then build {new} the same way
```

**Example values**

| Placeholder | Example |
| --- | --- |
| `{example}` | the GitHub webhook handler |
| `{new}` | a Stripe webhook handler |

*Source family: Best practices*

---

## 02 · Generate Docs For Code

**Workflow stage:** `build` · **Useful for:** `docs`

**Prompt**

```text
find {scope} without {format} comments and add them, matching the style already used in the file
```

**Example values**

| Placeholder | Example |
| --- | --- |
| `{format}` | JSDoc |
| `{scope}` | the public functions in src/auth/ |

*Source family: Common workflows*

---

## 03 · Add A Small Well

**Workflow stage:** `build`

**Prompt**

```text
add a {endpoint} endpoint that returns {payload}
```

**Example values**

| Placeholder | Example |
| --- | --- |
| `{endpoint}` | /health |
| `{payload}` | the app version and uptime |

*Source family: Common workflows*

---

## 04 · Build A Small Internal

**Workflow stage:** `build` · **Useful for:** `pm`, `design`, `marketing`, `docs`

**Prompt**

```text
create a {tool} using HTML, CSS, and vanilla JavaScript, then open it in my browser
```

**Example values**

| Placeholder | Example |
| --- | --- |
| `{tool}` | drag-and-drop Kanban board with three columns |

*Source family: How Anthropic teams use Claude Code*

---

## 05 · Work An Issue End

**Workflow stage:** `build`

**Prompt**

```text
read issue #{issue}, implement the fix, and run the tests
```

**Example values**

| Placeholder | Example |
| --- | --- |
| `{issue}` | 312 |

**Requires:** `gh`

*Source family: Common workflows*

---

## 06 · Find And Update Copy

**Workflow stage:** `build` · **Useful for:** `design`, `docs`, `marketing`

**Prompt**

```text
find every place we say "{copy}" or a close variant, show me each one in context, then update them all to "{new}". leave tests and the changelog alone
```

**Example values**

| Placeholder | Example |
| --- | --- |
| `{copy}` | Sign up free |
| `{new}` | Start free trial |

*Source family: How Anthropic teams use Claude Code*

---

## 07 · Draft From Past Examples

**Workflow stage:** `build` · **Useful for:** `docs`, `marketing`, `pm`

**Prompt**

```text
read the {examples} in {folder} to learn the structure and voice, then draft a new one for {topic}
```

**Example values**

| Placeholder | Example |
| --- | --- |
| `{examples}` | privacy impact assessments |
| `{folder}` | legal/pia/ |
| `{topic}` | the new analytics integration |

*Source family: How Anthropic teams use Claude Code — Legal*

---
