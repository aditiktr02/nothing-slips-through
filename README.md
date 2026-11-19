# Nothing Slips Through — Northline Morning Desk

A morning operations dashboard for **Northline Supply**, a fictional NYC packaging and supplies distributor. Built for the *Nothing Slips Through* product challenge (NYU Product Management Club × Base44, Nov 16, 2026).

**Live dashboard:** https://northline-morning-desk-604a40a8.base44.app

## The problem

Northline's data is split across a delivery log, QuickBooks invoices and bills, price lists and contracts, purchase orders and a shared inbox. Money slips through the cracks every month. The app brings it together so the operations manager can:

1. See all the data in one place
2. Catch what slipped (uninvoiced deliveries, stale prices, duplicate fees, short shipments, supplier overcharges, unanswered emails, bank-detail fraud attempts, and more)
3. See the records behind every flag
4. Draft catch-up invoices, credits and replies for approval

## Repository contents

| Path | What it is |
|---|---|
| `data/september/` | September source data: customers, products, contract prices, delivery log, invoices, purchase orders, supplier bills, suppliers, inbox |
| `templates/` | Blank and example `findings.csv` / `evidence.csv` output formats |
| `START_HERE.md` | Challenge overview |
| `DATA_DICTIONARY.md` | Column-by-column description of every data file |
| `billing_rules.md` | Northline's billing rules used to detect problems |
| `FINDINGS_AND_EVIDENCE.md` | Spec for the findings and evidence outputs |
| `Challenge-Brief.pdf` | Original challenge brief |

All data is synthetic and was provided for the challenge.
