# Bill Tracker

A lightweight personal finance tracker for bills, expenses, bank accounts, cash withdrawals, transfers, and time deposits.

## Time Deposits
- Create a time deposit from an existing bank account.
- Enter principal, annual interest rate (% p.a.), term in months, and start date.
- Active deposits are reserved from the source bank's available balance.
- Estimated interest uses simple interest prorated by term: principal × annual rate × months / 12.
- At or after maturity, transferring back returns principal plus estimated interest to the original bank.
- Early transfer-back returns principal only (no estimated interest).
- Actual bank rates, tax, fees, compounding, and early-withdrawal rules may differ; confirm the bank's terms.

All app data remains in the browser's local storage. Use Backup before replacing files or clearing browser data.
