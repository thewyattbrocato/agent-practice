# tmux Cheatsheet

## Mental model

tmux is a terminal workspace manager.

- Session: a persistent workspace
- Window: like a tab inside tmux
- Pane: a split inside a window
- Prefix: `Ctrl+b`, followed by another key

## Core commands

Start a session:

```bash
tmux new -s practice