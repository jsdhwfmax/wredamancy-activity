# Wredamancy activity

Daily aggregate data for [wredamancy.com](https://wredamancy.com/activity).

`data/codex-usage.json` contains daily token counts derived from retained local Codex session usage events, grouped by Australia/Sydney calendar date. Includes subagents and cached input. Total = input + output; cachedInput is already included in input. Days without observed usage records are marked `recorded: false`, not asserted to be zero usage. The current day is partial.

This is not account-wide usage, billing, unique text written, or a measure of work quality. Source prompts, transcripts, session IDs, paths, credentials and account identifiers are never published. Data refreshes daily from the owner's local Codex host; an offline host can delay updates, so always read `updatedAt`.

Only aggregate data lives here. Source projects and contributions are introduced on the website.
