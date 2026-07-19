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
