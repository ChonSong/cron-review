# Hermes Cron Audit Dashboard

Live at **[chonsong.github.io/cron-review](https://chonsong.github.io/cron-review/)**

Interactive dashboard showing all 42 Hermes Agent cron jobs with:
- **Health breakdown** by category (healthy / API errors / dead symlinks / network / data bugs)
- **Search** by name, ID, or description
- **Filter** by category
- **24-hour schedule timeline** with live "now" marker
- **Per-job details**: schedule, next/last run, skills, repeat count, error messages

Generated from `hermes cron list` + `hermes gateway status` — 2026-06-28 20:25 AEST.
