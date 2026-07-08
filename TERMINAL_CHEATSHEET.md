# Terminal Cheatsheet

A beginner reference for working in WezTerm, zsh, tmux, Git, and agentic engineering workflows.

## Mental model

- WezTerm: the terminal app/window
- zsh: the shell that reads and runs commands
- tmux: a persistent terminal workspace with panes and windows
- Git: local version control
- GitHub: remote hosting for repositories, branches, pull requests, and collaboration
- Codex/OpenCode: AI coding agents launched from the terminal
- Firstmate: a coordinator for multi-agent workflows

## Core navigation

Print current folder:

```bash
pwd
```

Review your current Git changes:

```bash
git diff
```

## no-mistakes basics

no-mistakes is a local validation gate.

Normal push:

```bash
git push origin branch-name
```

## Current Agentic Workflow

The captain's agentic engineering stack. Each tool has a job; reach for it when its job is the blocker.

- **OpenCode**: the orchestration harness that launches and runs agents from the terminal. Use it to start a coding session and drive work interactively.
- **Firstmate**: the coordinator that manages many agents across branches and tasks like this one. Use it when you need multi-agent dispatch, status, or review.
- **Codex**: a direct coding agent and the engine behind no-mistakes review. Use it for hands-on coding and for the validation pass.
- **Treehouse**: gives each task an isolated worktree so work never touches the primary checkout. Use it whenever a task needs a safe, disposable space.
- **no-mistakes**: the validation gate that runs review, tests, lint, and CI before shipping. Use it after changes are written to confirm they are safe to merge.
- **Lavish**: turns plans and results into rich, reviewable HTML artifacts. Use it when you want a visual plan, comparison, or diff to share for feedback.
- **gnhf**: a fast, cheap helper for quick edits and iteration. Use it with explicit iteration and token bounds so it stays small and focused.
