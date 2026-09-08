# Personal Bill Tracker — Version 1.0

A local-first personal finance tracker for bills, everyday expenses, bank accounts, transfers, physical cash, monthly reports, and backup/export.

## What the app stores
- Bills and expenses
- Paid / Unpaid status
- Payment Source: Cash or GCash
- Bank accounts and opening balances
- Bank deposits and normal withdrawals
- Fast transfers between banks
- Physical cash withdrawals
- Cash used by paid Cash bills/expenses
- Cash remaining in hand

## Data and privacy
Your records are stored locally in the browser used for the app. GitHub should contain only the application files, not your bills or financial records.

Regularly use **Backup** to create a JSON backup file. Keep that file somewhere safe.

## Import and restore
Use **Import** to restore a JSON backup. Import replaces the current local data after confirmation.

## Excel report
Use **Excel Report** to create a real `.xlsx` workbook with three worksheets:

1. **Dashboard & Reports** — a quick summary and monthly overview.
2. **Bills & Expenses** — the complete bill/expense record, including notes.
3. **Bank & Cash** — bank accounts, bank activity, transfers, physical cash withdrawals, and cash summaries.

Dates are written in a clear format such as `08 Sep 2026`, with month information included for easier sorting and filtering.

The JSON backup is the restore format. The Excel report is intended for reading, sharing, and reporting.

## Mobile / PWA
The app includes a web app manifest and service worker so it can be installed on a phone when served from a secure web host (HTTPS). Opening `index.html` directly with `file://` is useful for PC testing, but browser PWA installation/service-worker features normally require a web server or HTTPS hosting.

## Version 1.0 release checklist
- PC responsive interface
- Mobile responsive layout
- Mobile-safe custom dropdowns
- Bills and expenses management
- Bank and cash tracking
- Fast bank transfers
- JSON backup/import
- Multi-sheet Excel report
- PWA installation foundation


V8.3.14: fixed dark-mode mobile table rows and custom dropdown menus so they no longer render white.
