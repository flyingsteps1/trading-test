# strategy-lab

This repository is for strategy research, notes, workflow docs, and prompt templates.

TradingView MCP can be useful for chart-aware work such as:
- reviewing current chart context
- drafting or checking Pine ideas
- replay-based review
- capturing screenshots for analysis

TradingView MCP is not required for routine repository work. Many tasks should be done without it.

## When not to use TradingView MCP

Do not use TradingView MCP for note cleanup, file organization, documentation editing, prompt writing, or other generic writing tasks that do not need live chart context.

If the task can be completed from the repository contents alone, continue without MCP.

## Session start checklist

1. Is this a chart task?
2. Do I actually need TradingView context?
3. Is TradingView connected?
4. If not a chart task, continue without MCP.

## Pine naming rules

Keep Pine files in one of these two folders:
- `pine/indicators/`
- `pine/strategies/`

Use simple lowercase names with hyphens and a version number:
- `pine/indicators/<idea-name>-v1.pine`
- `pine/strategies/<idea-name>-v1.pine`

When you revise the same idea, increase the version number:
- `v2` for the next iteration
- `v3` for the one after that

Use a new idea name only when the concept has materially changed. Small edits should stay under the same idea name and move from `v1` to `v2`, `v3`, and so on.
