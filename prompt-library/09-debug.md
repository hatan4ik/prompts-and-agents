# Debug prompts

3 copy-paste prompts from Anthropic’s official Claude Code prompt library. Replace values in `{braces}` with your own context.

## 01 · Find And Fix A

**Workflow stage:** `operate`

**Prompt**

```text
the {test} test is failing, find out why and fix it
```

**Example values**

| Placeholder | Example |
| --- | --- |
| `{test}` | UserAuth |

*Source family: Common workflows*

---

## 02 · Investigate A Reported Error

**Workflow stage:** `operate` · **Useful for:** `ops`

**Prompt**

```text
users are seeing {symptom} on {where}. investigate and tell me what is going on
```

**Example values**

| Placeholder | Example |
| --- | --- |
| `{symptom}` | 500 errors |
| `{where}` | /api/settings |

*Source family: Common workflows*

---

## 03 · Fix A Build Error

**Workflow stage:** `operate` · **Useful for:** `ops`

**Prompt**

```text
here is a build error. fix the root cause and verify the build succeeds
```

**Bring with you:** `error` output

*Source family: Best practices*

---
