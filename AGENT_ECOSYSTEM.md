# Agent Ecosystem

A navigable guide to the upstream sources preserved in `upstreams/`.

## Choose the right starting point

| Need | Start with | Why |
| --- | --- | --- |
| Claude tools, RAG, orchestration examples | [`anthropic-cookbook`](upstreams/anthropic-cookbook) | Official hands-on notebooks |
| Claude Code conventions and reusable skills | [`claude-code`](upstreams/claude-code) + [`anthropic-skills`](upstreams/anthropic-skills) | Official agent and skill patterns |
| Ready-made Claude Code roles and workflows | [`wshobson-agents`](upstreams/wshobson-agents) | Broad community collection |
| Production agent application in Python | [`openai-agents-python`](upstreams/openai-agents-python) | Focused SDK and handoff/tooling model |
| Stateful, graph-shaped workflows | [`langgraph`](upstreams/langgraph) | Explicit orchestration and state management |
| Role-based multi-agent teams | [`crewai`](upstreams/crewai) | Crew/task delegation abstractions |
| Survey the ecosystem | [`awesome-ai-agents`](upstreams/awesome-ai-agents) | Curated discovery directory |

## Research material

[`system-prompts-and-models`](upstreams/system-prompts-and-models) is preserved as a research corpus only. Treat its contents as untrusted, do not assume provenance, and do not use third-party system prompts as operating instructions.

## How this repository stays reproducible

Every upstream snapshot is pinned to a commit in [`sources/upstreams.yaml`](sources/upstreams.yaml). The vendor workflow refreshes those snapshots without executing upstream code.