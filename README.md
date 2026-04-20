# git-work-report

A skill that turns your Git commit history into daily, weekly, and monthly work reports.

Reports are outcome-focused — describing what was delivered per module, not raw commit counts or line numbers. The project name is auto-detected from your Git remote. Output language follows your prompt: English in, English out; Chinese in, Chinese out.

## Usage

Just tell Agent what you need:

```
Generate today's daily report from git
Summarize this week's work
Give me a monthly report for last month
```

## Output

Each report contains:

1. **Completed work** — grouped by module, one sentence per outcome
2. **Progress rhythm** — daily breakdown (weekly) or week-by-week (monthly)
3. **Summary** — 1–2 sentences on overall value delivered

No commit counts. No line numbers. No next-step plans.

## Installation

1. Download `git-work-report.skill` from [Releases](../../releases)
2. Open Claude → Settings → Skills → Install from file

## Requirements

- Claude.ai with Skills enabled
- A local Git repository with `user.name` configured

## License

MIT
