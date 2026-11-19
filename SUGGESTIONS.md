# Suggestions

## Get more out of your data (no code changes needed)

1. **Record estimated or flat-rate hours on every job.** Efficiency is the most useful metric, and it only works on rows that have an estimate.
2. **Log callbacks against the original tech and work order.** Otherwise rework looks like new, productive work for whoever goes back out.
3. **Separate non-billable time** (drive, shop, supply house, training) with a Task value or a Billable column. Utilization is often where the hidden hours are.
4. **Use one export format for everyone.** Mixed layouts are handled, but consistent names (same spelling for each tech, same task categories) keep the reports clean.
5. **Compare people over the same period.** Someone with 3 days of data isn't comparable to someone with 4 weeks. Use the same date range for reviews.

## Fairness caveats when using this for reviews

- **Job mix matters.** Service calls and troubleshooting are less predictable than rough-in. Check the per-task table before comparing two people.
- **Apprentices vs. journeymen.** Rank them separately, or treat the score as a trend for each person rather than a league table.
- **Estimates can be wrong.** If one task type is always "inefficient" for everyone, fix the estimate, not the tech.
- **Use the score to start a conversation.** It should prompt questions, not decide anything on its own.

## Shipped

- Dark mode (default) with light toggle
- People & groups: rename, merge, group by crew / role, per-group summaries, save/load setup
- Data check panel with duplicate-row removal and downloadable issues list
- Automatic duplicate-name suggestions (initials, nicknames, typos)
- Score breakdown on hover/tap and in every report
- Compact drop bar, column views (Overview / Productivity / Quality / Money), frozen name column
- Four headline numbers with period-over-period change
- Phone card layout
- Report charts: hours per week and efficiency by task vs team
- Period filter + compare with previous period
- Manager notes per employee (in reports and exports)
- Installable offline app (PWA)
- One-ZIP export
- Visible privacy note

## Feature ideas for the tool

| Priority | Feature | Why |
|---|---|---|
| Medium | **Adjustable score weights** | Let each shop decide what matters (e.g. callbacks count more) |
| Medium | **Saved column mappings per export format** | Recurring exports from the same software map instantly |
| Medium | **Excel (.xlsx) input** | Many timekeeping systems export Excel |
| Low | **Material cost and gross margin per job** | Ties labor efficiency to profit |
| Low | **Presets for common software exports** (ServiceTitan, Jobber, Housecall Pro, QuickBooks Time) | Zero-setup imports |
| Low | **Goals per person** (e.g. callback rate under 3%) shown on their report | Turns reviews into targets |
