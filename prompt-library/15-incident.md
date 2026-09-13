# Incident prompts

3 copy-paste prompts from Anthropic’s official Claude Code prompt library. Replace values in `{braces}` with your own context.

## 01 · Investigate A Production Incident

**Workflow stage:** `operate` · **Useful for:** `ops`, `security`

**Prompt**

```text
{symptom}. check the logs, recent deploys, and config changes, then tell me the most likely cause
```

**Example values**

| Placeholder | Example |
| --- | --- |
| `{symptom}` | the checkout endpoint started returning 500s an hour ago |

*Source family: Common workflows*

---

## 02 · Diagnose From A Console

**Workflow stage:** `operate` · **Useful for:** `ops`, `data`

**Prompt**

```text
here is a screenshot of {console}. walk me through why {resource} is failing and give me the exact commands to fix it
```

**Example values**

| Placeholder | Example |
| --- | --- |
| `{console}` | the GCP Kubernetes dashboard |
| `{resource}` | this pod |

**Bring with you:** `screenshot` output

*Source family: How Anthropic teams use Claude Code*

---

## 03 · Query Logs In Plain

**Workflow stage:** `operate` · **Useful for:** `security`, `ops`, `data`

**Prompt**

```text
show me all {events} for {scope} over {timeframe}. write the query, run it, and tell me what stands out
```

**Example values**

| Placeholder | Example |
| --- | --- |
| `{events}` | failed logins |
| `{scope}` | the auth service |
| `{timeframe}` | the past 24 hours |

**Requires:** `db`

*Source family: cybersecurity*

---
