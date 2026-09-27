# Claude Code agents

Two Claude Code agents:

- **fable-planner**: deep planning on Fable. Returns a step-by-step plan and doesn't edit files. Say "plan with fable" to use it.
- **web-scout**: broad web survey on Sonnet. Finds as many options as it can. Say "use web-scout" to use it.

Neither agent runs on its own. You have to ask for it by name.

## Install

In Claude Code:

```
/plugin marketplace add CreepteedLTD/claude-agents
/plugin install creepteed-agents@creepteed
```

Restart Claude Code after installing.

To get updates: `/plugin marketplace update creepteed`

## Manual install

Copy the files in `plugins/creepteed-agents/agents/` to `~/.claude/agents/`.
