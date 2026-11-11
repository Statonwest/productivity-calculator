# Workday Productivity Calculator

A mobile-first productivity calculator for planning a therapy or clinical workday. Two modes on one screen, works offline, installable as a home-screen app.

**Live:** <https://statonwest.github.io/productivity-calculator/>

## Modes

**Productivity Score** — enter total work time and productive time to get your productivity rate, score /100, time lost, and a productivity level (Very Low → Excellent) with a suggestion.

**Perfect End Time** — plan a workday from clock times:
- Start time, lunch out/in, other non-billable time (meetings, training), billable time, and productivity target %.
- Leave *clock out* blank to solve the time you can leave; set it to see your actual productivity %.

## Rounding

All clock times round to the **nearest 15 minutes** (7.5-minute rule). Each field shows what it rounds to. Example: lunch out at 12:08 → 12:15, back at 12:52 → 12:45 = a **30-minute lunch**.

## Formulas

- Productivity Rate = Productive ÷ Total Work Time × 100
- Total Worked = Billable ÷ (Target ÷ 100)
- Paid hours = clocked time − lunch − other non-billable time

## Install

iPhone: Safari → Share → **Add to Home Screen**. Runs full-screen and works offline after the first load (service worker). Inputs are stored locally on your device — nothing is sent to a server.

## Notes

Planning math only. Confirm billing/timekeeping policy (rounding rules, counted time) with your organization before relying on it.

## License

[Apache License 2.0](LICENSE)
