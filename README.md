# Weekly Cleanup Review

Review a multi-assistant setup for duplicate work, inactive projects and opportunities to reduce recurring usage. The review can be requested on demand or scheduled for a cadence that suits the owner.

## Try it

```sh
npx skills add felipepetersmann22-star/weekly-cleanup-review-skill
```

Or copy this repository into your agent's skills directory, keeping `SKILL.md` and `assets/` together. Restart or refresh skill discovery if needed. Review the instructions before installing any third-party skill.

Ask your agent: “Review my assistants and routines. Skip anything active, and propose the three most useful improvements. Don't change anything.”

A review may identify an idle assistant that could use a handover and a running deployment that should be left alone. It records observations and proposals separately from completed actions. It does not schedule itself, move files, update memory, delete items or message others merely because a review was requested.

The included [report template](assets/cleanup-report.md) separates evidence, skipped work, completed actions and proposals. Companion skills can help when available but are optional. Coverage depends on the sources and platform tools actually accessible; actual usage or cost requires a relevant usage report.

## Source and license

Derived from the [original public skill](https://github.com/felipepetersmann22-star/agent-skills/tree/1b7a3d8867363c0ff0dda0f9a117aacb7a16a347/skills/weekly-cleanup-review). See [credits](CREDITS.md) and the [MIT license](LICENSE).
