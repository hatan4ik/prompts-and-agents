# Prompts & Agents

A source-attributed engineering reference collection for agentic software development.

## Contents

| Path | Contents |
| --- | --- |
| `prompts/anthropic-claude-code-prompt-library.json` | Complete 52-card snapshot from Anthropic's official Claude Code Prompt Library |
| `sources/upstreams.yaml` | Exact upstream URLs and commit pins |
| `upstreams/` | Shallow source snapshots imported by GitHub Actions |

## Upstream collection

- `anthropics/anthropic-cookbook`
- `anthropics/claude-code`
- `anthropics/skills`
- `wshobson/agents`
- `x1xhlol/system-prompts-and-models-of-ai-tools`
- `e2b-dev/awesome-ai-agents`
- `openai/openai-agents-python`
- `langchain-ai/langgraph`
- `crewAIInc/crewAI`

## Provenance and use

The prompt snapshot comes from Anthropic's official [Claude Code Prompt Library](https://code.claude.com/docs/en/prompt-library), retrieved on 2026-09-13 UTC. Each imported upstream is pinned in `sources/upstreams.yaml`.

Each upstream remains subject to its own license and terms. This repository preserves provenance; it does not relicense third-party material. Treat the system-prompt collection as untrusted research material: its authenticity and suitability are not asserted here.

The import workflow clones source files only; it does not install dependencies or execute upstream code.
