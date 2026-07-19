# The Domain Engineer
[The Domain Engineer Training](https://threedots.tech/the-domain-engineer/) by [Three Dots Labs](https://threedots.tech/)

## Links
[Training Portal](https://academy.threedots.tech/trainings/list)

## How

### Git integration

```bash
# Your progress will be tracked with git. Here's what happens automatically:

# When you complete an exercise:
  git add <exercise-dir> && git commit -m "completed <exercise>"

# When loading the next exercise:
  git fetch cli tdl/init/<exercise>
  git merge tdl/init/<exercise>

# After passing, the example solution is saved for comparison:
  git diff <your-branch>..tdl/example/<exercise> -- <exercise-dir>

# Press s after passing to sync with the example solution.
# Your work is saved to a backup branch first (never destructive).

# Defaults: auto-commit on, auto-sync off.
# To change:
  tdl training settings
```

### AI coding support

> MCP server (optional)
> 
> If you plan to use an AI coding tool (Claude Code, Cursor, etc.) alongside this training, the MCP server lets it run exercises and check results. It listens on 127.0.0.1 (localhost only) while tdl tr run is active.
> 
> The training works perfectly fine without it. It will integrate your coding agent with this CLI. Writing by hand is still the default, and may help the ideas stick. You can change this later with: tdl training settings
