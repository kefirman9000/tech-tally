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

## Feature ideas for the tool

| Priority | Feature | Why |
|---|---|---|
| High | **Date range filter** (this week / month / custom) | Review a specific period without editing CSVs |
| High | **Trend view**: score and efficiency by week for each person | Shows whether someone is improving, which is more useful than one number |
| High | **Role / crew grouping** (apprentice, journeyman, foreman) | Fairer comparisons and crew-level totals |
| Medium | **Adjustable score weights** | Let each shop decide what matters (e.g. callbacks count more) |
| Medium | **Saved column mappings** (stored in the browser) | Recurring exports from the same software map instantly |
| Medium | **Single ZIP export** of all individual CSVs | One download instead of many separate files |
| Medium | **Excel (.xlsx) input** | Many timekeeping systems export Excel |
| Low | **Material cost and gross margin per job** | Ties labor efficiency to profit |
| Low | **Charts** (hours by task, efficiency vs. team) | Faster to read in one-on-ones |
| Low | **Notes field per employee** included in the exported report | Managers can add context before printing |
| Low | **Presets for common software exports** (ServiceTitan, Jobber, Housecall Pro, QuickBooks Time) | Zero-setup imports |
