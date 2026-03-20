# iFixandRepair — Employee Timesheet

A simple, mobile-friendly employee timesheet web app for iFixandRepair. Built as a single HTML file with no dependencies, no backend, and no installation required.

## What It Does

- Employees enter their name and select their pay period
- Choose any month, year, and pay period half (1st–15th or 16th–end of month)
- Fill in daily hours and store location for each date
- Live totals update instantly for G1, G2, G3, and overall hours
- Submit generates a printable summary that can be copied and sent to a manager

## How to Use

1. Open `index.html` in any browser
2. Enter your full name
3. Select the correct month, year, and pay period half
4. For each date, choose your store (G1, G2, G3, or Off) and hours (9.5, 10, or Custom)
5. Click **Submit Timesheet** to generate your summary
6. Print or copy the summary to send to your manager

## Features

- Auto-detects the current pay period on load
- Supports any month and year — no manual date editing ever needed
- Handles February 28/29, and months with 30 or 31 days automatically
- Custom hours input supports decimals (e.g. 8.5)
- Off days count as 0 and are excluded from totals
- Printable summary page
- Copy to clipboard button for easy sharing
- Works fully offline — no internet required after opening

## Hosting

This app is hosted via GitHub Pages at:
`https://kritesh2006.github.io/Pay-report/`

No server, no database, no setup needed.

## Files

| File | Description |
|---|---|
| index.html | The entire app — HTML, CSS, and JavaScript in one file |

## Customization

All editable items are inside `index.html`:

- **To change the manager email or add a backend** — connect to Google Apps Script (see setup guide)
- **No other configuration needed** — the app is self-contained

## Built With

- Plain HTML, CSS, and JavaScript
- No frameworks
- No external libraries
- No build tools

---

*Internal tool for iFixandRepair.*
