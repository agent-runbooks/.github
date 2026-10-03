# Agent Runbooks

A runbook is a procedure that a coding agent session executes step by step through subagents. The steps are prompt files, the transitions are a few lines of Python, and the run leaves a record you can read.

- **[skills](https://github.com/agent-runbooks/skills)**: the tools. `agent-runbook-authoring` writes and reviews runbooks, `runbook-viewer` shows the progress of a run.
- **[gallery](https://github.com/agent-runbooks/gallery)**: ready-made runbooks to install and adapt. Start with `runbook-task-cycle`: one coding task from brief to reviewed changes.
- **[throng-mcp](https://github.com/agent-runbooks/throng-mcp)**: an MCP server that runs Claude Code, Codex, OpenCode and other harnesses as subagents of each other, so a runbook step can go to any model.

New here? Install the skills, then run `runbook-task-cycle` from the gallery on a small task.
