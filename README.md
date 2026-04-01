# ghostty-tools

CLI utilities for Ghostty terminal workflows.

## workspace

A tmux workspace manager that creates a 3-pane layout: Claude Code on the left, vim + terminal on the right.

```
workspace <name> [path]    Create or attach to a workspace
workspace ls               List active workspaces
workspace ls -la           List all workspaces (including hidden)
workspace rm <name>        Kill and remove a workspace
workspace hide <name>      Hide a workspace
```
