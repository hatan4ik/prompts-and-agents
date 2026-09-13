# Git prompts

3 copy-paste prompts from Anthropic’s official Claude Code prompt library. Replace values in `{braces}` with your own context.

## 01 · Resolve Merge Conflicts

**Workflow stage:** `ship`

**Prompt**

```text
resolve the merge conflicts in this branch and explain what you kept from each side
```

*Source family: Common workflows*

---

## 02 · Commit With A Generated

**Workflow stage:** `ship`

**Prompt**

```text
commit these changes with a message that summarizes what I did
```

*Source family: Common workflows*

---

## 03 · Open A Pull Request

**Workflow stage:** `ship`

**Prompt**

```text
find the {tracker} ticket about {topic} and open a PR that implements it
```

**Example values**

| Placeholder | Example |
| --- | --- |
| `{topic}` | the login timeout |
| `{tracker}` | Linear |

**Requires:** `tracker`

*Source family: Common workflows*

---
