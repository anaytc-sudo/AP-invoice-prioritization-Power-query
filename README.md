# AP Invoice Prioritization Automation (Power Query)

Automation built in Excel Power Query that streamlines the daily process of identifying and prioritizing Accounts Payable invoices — replacing a manual VLOOKUP-based workflow.

*Impact:* reduced daily processing time from 20 minutes to 5 minutes (*75% reduction*), while eliminating repeated review of invoices already flagged with PO issues.

## What it does

- Connects to and consolidates invoice data from the ERP export
- Cross-references the daily invoice list against a separate PO issues tracker, automatically excluding invoices already flagged
- Sorts the remaining ("workable") invoices by creation date, oldest first
- Refreshes with a single click

## Files

- [AP Invoice Prioritization Automation with Power Query.docx](<./AP%20Invoice%20Prioritization%20Automation%20with%20Power%20Query.docx>) — full write-up: problem, solution, and measured impact
- [Portfolio_Power_Query_AP_Invoices_example_EN.xlsx](./Portfolio_Power_Query_AP_Invoices_example_EN.xlsx) — example workbook (fictional data) showing the same structure and logic as the real process

> Note: all data in this repository is fictional. It replicates the structure and logic of a real production workflow without exposing confidential client information.

## Skills demonstrated

Power Query · Advanced Excel · Process Automation · ERP (SAP / Oracle Fusion) · Process Documentation
