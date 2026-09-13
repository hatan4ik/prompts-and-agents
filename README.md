# Prompts & Agents

> A human-first reference library for prompts, agent patterns, and production agent frameworks.

**Start here:** [Practical operating path](START_HERE.md) · [Prompt library](PROMPT_LIBRARY.md) · [Agent ecosystem](AGENT_ECOSYSTEM.md) · [Repository guide](REPOSITORY_GUIDE.md)

## What you can do here

| Goal | Go to |
| --- | --- |
| Learn a disciplined agent workflow from discovery to release | [Start Here](START_HERE.md) |
| Copy, adapt, and use 52 Claude Code prompts | [Prompt Library](PROMPT_LIBRARY.md) |
| Choose between OpenAI Agents SDK, LangGraph, CrewAI, Claude Code skills, and more | [Agent Ecosystem](AGENT_ECOSYSTEM.md) |
| Inspect real upstream implementations | [`upstreams/`](upstreams/) |
| Verify where every source came from and its exact pin | [`sources/upstreams.yaml`](sources/upstreams.yaml) |

## Prompt Library

The Anthropic Claude Code collection is presented as direct Markdown—organized by work type, with placeholders, example values, roles, and operational requirements.

- [Onboard & Understand](prompt-library/01-onboard.md)
- [Plan, Prototype & Implement](prompt-library/03-plan.md)
- [Test, Refactor & Review](prompt-library/06-test.md)
- [Debug, Git & Release](prompt-library/09-debug.md)
- [Data, Automate, Steer & Incident](prompt-library/12-data.md)

## Agent Sources

Nine pinned upstream collections are preserved under [`upstreams/`](upstreams/), covering official Anthropic resources, Claude Code workflows, community subagents, and the leading Python agent frameworks.

Every snapshot is recorded in [`sources/upstreams.yaml`](sources/upstreams.yaml) and can be refreshed through the repository’s vendor workflow.

## Repository shape

```text
START_HERE.md          practical learning path
PROMPT_LIBRARY.md      direct, readable index for all prompts
prompt-library/        15 Markdown collections; 52 copy-paste prompts
AGENT_ECOSYSTEM.md     framework selection guide
upstreams/             pinned source snapshots
sources/               provenance and exact commit pins
```

## Attribution

The prompt collections are based on Anthropic’s official [Claude Code Prompt Library](https://code.claude.com/docs/en/prompt-library), captured on 2026-09-13. Each third-party upstream remains subject to its own license and terms.
