# Tech Tally

A single-file, offline tool that turns timesheet / work-order CSVs into a **performance & efficiency summary for every employee** on an electrical crew.

**▶ Live page:** https://kefirman9000.github.io/tech-tally/

Everything runs in your browser. No data is uploaded anywhere — you can also download `index.html` and open it with no internet connection.

## How to use

1. Open the page (or `index.html` locally).
2. Drag one or more CSV files onto it (e.g. one per week or per crew). Try `sample-timesheets.csv` or the **Load sample data** button.
3. Check the auto-matched columns. Only **Employee name** is required.
4. Export:
   - **Team summary CSV**: one row per employee
   - **Each employee CSV**: one summary file per person
   - **All reports HTML** or **Print / PDF**: one page per employee

## Recognized columns

Column names are matched automatically and can be changed in the dropdowns. Files with different layouts can be combined.

| Field | Example headers | Unlocks |
|---|---|---|
| Employee name * | Employee, Tech, Electrician, Name / First + Last | everything |
| Date | Date, Work Date | days worked, weekly overtime |
| Actual hours | Hours, Actual Hours, Hours Worked (or Clock In + Clock Out) | workload |
| Estimated hours | Estimated Hours, Budget, Quoted, Flat Rate | **efficiency** |
| Job / work order | Work Order, Job #, Ticket | jobs, hours per job |
| Task / work type | Task, Work Type, Category | per-task breakdown |
| Status | Status, Completed | completion rate |
| Callback / rework | Callback, Rework, Return Visit | quality, callback rate |
| Billable hours | Billable Hours (or Y/N) | utilization |
| Overtime | Overtime, OT Hours | overtime (otherwise computed > 40 hrs/week) |
| Revenue | Revenue, Invoice, Amount | revenue per hour |
| Inspection | Inspection (Pass/Fail) | inspection pass rate |
| Safety | Safety Incidents | safety count |

## Metrics

- **Efficiency** = estimated hours ÷ actual hours on jobs that have an estimate. Over 100% means faster than estimated.
- **Score (0–100)** is a weighted blend of efficiency (40%), completion (25%), callbacks (20%), inspection pass (15%) and billable utilization (15%). It uses only the metrics your data contains and re-weights to match.
- Names are normalized, so `Torres, Mike`, `mike torres` and `Mike Torres` count as one person.

See [SUGGESTIONS.md](SUGGESTIONS.md) for ideas on improving the data and the tool.
