# cmt-pr-large

Test repository for check-my-toolkit PR size checks.

This repo is configured to test PRs that **exceed** size limits.

## Configuration

```toml
[process.pr]
enabled = true
max_files = 5
max_lines = 100
```

Create a PR with more than 5 files or 100 lines to see the check fail.
