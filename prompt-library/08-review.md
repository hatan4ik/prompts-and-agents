# Review prompts

5 copy-paste prompts from Anthropic’s official Claude Code prompt library. Replace values in `{braces}` with your own context.

## 01 · Review Your Changes Before

**Workflow stage:** `build`

**Prompt**

```text
review my uncommitted changes and flag anything that looks risky before I commit
```

*Source family: Common workflows*

---

## 02 · Review A Pull Request

**Workflow stage:** `build`

**Prompt**

```text
review PR #{pr} and summarize what changed, then list any concerns
```

**Example values**

| Placeholder | Example |
| --- | --- |
| `{pr}` | 247 |

**Requires:** `gh`

*Source family: Common workflows*

---

## 03 · Review Infrastructure Changes Before

**Workflow stage:** `build` · **Useful for:** `security`, `ops`

**Prompt**

```text
here is my Terraform plan output. what is this going to do, and is anything here going to cause problems?
```

**Bring with you:** `plan` output

*Source family: How Anthropic teams use Claude Code*

---

## 04 · Run A Security Review

**Workflow stage:** `build` · **Useful for:** `security`

**Prompt**

```text
use a subagent to review {path} for security issues and report what it finds
```

**Example values**

| Placeholder | Example |
| --- | --- |
| `{path}` | src/api/ |

*Source family: Best practices*

---

## 05 · Review Content Before Sending

**Workflow stage:** `build` · **Useful for:** `marketing`, `docs`

**Prompt**

```text
review {file} for {concerns} and list anything I should fix before it goes to {reviewer}
```

**Example values**

| Placeholder | Example |
| --- | --- |
| `{concerns}` | unsupported claims, missing attributions, and brand-guideline issues |
| `{file}` | launch-post.md |
| `{reviewer}` | legal |

*Source family: How Anthropic teams use Claude Code — Legal*

---
