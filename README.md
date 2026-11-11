# Meridian Manufacturing - Accounts Payable Document Repository

This repository is the intake point for vendor invoices handled by the
accounts payable team. All documents here are confidential.

Layout:
- `vendors.json` - approved vendor master data and per-vendor limits
- `policy.json` - the current accounts payable policy
- `invoices/` - one PDF invoice per file, plus `manifest.json`
- `audit/` - audit findings produced by the AP reviewer; escalated
  invoices also get one memo file each under `audit/escalations/`

Invoices arrive as PDF documents. Use the document link pattern from the
workspace repository pointer to open each PDF.
