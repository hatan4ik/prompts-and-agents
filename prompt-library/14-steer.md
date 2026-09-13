# Steer prompts

3 copy-paste prompts from Anthropic’s official Claude Code prompt library. Replace values in `{braces}` with your own context.

## 01 · Course Correct A Wrong

**Workflow stage:** `build`

**Prompt**

```text
that is not right: {feedback}. try a different approach
```

**Example values**

| Placeholder | Example |
| --- | --- |
| `{feedback}` | the function signature needs to stay backward-compatible |

*Source family: Best practices*

---

## 02 · Narrow The Scope Of

**Workflow stage:** `build`

**Prompt**

```text
that is too much. keep only the changes to {scope} and undo your other edits
```

**Example values**

| Placeholder | Example |
| --- | --- |
| `{scope}` | the validation logic in src/forms/ |

*Source family: Best practices*

---

## 03 · Turn A Correction Into

**Workflow stage:** `build`

**Prompt**

```text
you keep {mistake}. add a rule to CLAUDE.md so this stops happening
```

**Example values**

| Placeholder | Example |
| --- | --- |
| `{mistake}` | using default exports when this project uses named exports |

*Source family: Best practices*

---
