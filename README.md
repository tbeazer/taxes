# Taxes, Starting With Form 1040

A public-domain study guide to the U.S. individual income tax return. Every individual return starts with **Form 1040**, and nearly every other form or schedule feeds a number onto one of its lines. This repository maps those connections one tax year at a time, so it can grow as the tax code changes.

**Browse it:** open `index.html`, or turn on GitHub Pages (Settings → Pages → Deploy from a branch → `main`, `/ (root)`).

## What's here

| Folder | What it covers |
|---|---|
| [`form-1040/`](form-1040/) | How Form 1040 is organized, with one subfolder per tax year |
| [`form-1040/2025/`](form-1040/2025/) | Interactive flow map for tax year 2025: every common form, the 1040 line it feeds, 2025 limits, due diligence questions and links to the official IRS forms |
| [`definitions/`](definitions/) | 134 tax terms, forms and schedules in plain English |

## How a Form 1040 flows

1. **Income** (lines 1–9): wages, interest, dividends, retirement income, capital gains, and other income from Schedule 1.
2. **Adjustments** (lines 10–11): above-the-line items from Schedule 1, Part II, subtracted to reach adjusted gross income (AGI).
3. **Deductions** (lines 12–15): the standard deduction or itemized deductions (Schedule A), plus the QBI deduction and Schedule 1-A deductions, to reach taxable income.
4. **Tax** (lines 16–18): tax from the Tax Table, plus additional taxes from Schedule 2, Part I.
5. **Credits and other taxes** (lines 19–24): nonrefundable credits (Schedule 8812, Schedule 3) reduce the tax; other taxes such as self-employment tax are added to reach total tax.
6. **Payments** (lines 25–33): withholding, estimated payments and refundable credits.
7. **Result** (lines 34–38): a refund if payments are more than total tax, or a balance due if less.

## Adding a new tax year

1. Copy the latest year's folder, for example `form-1040/2025/` to `form-1040/2026/`.
2. Update the figures and line numbers from that year's IRS forms, instructions and inflation adjustment revenue procedure.
3. Update that folder's `README.md` source list.
4. Add the year to the table in [`form-1040/README.md`](form-1040/README.md) and to the year list in `index.html`.
5. If a new term appears, add it to `definitions/`.

## Sources

All content is based on public U.S. government sources: IRS forms, instructions, publications, revenue procedures and news releases, and federal law. Works of the U.S. government are not subject to copyright (17 U.S.C. § 105). Each tax year folder lists its specific sources.

## Public domain

This work is dedicated to the public domain under [CC0 1.0](LICENSE). Anyone may copy, change, share or use it for any purpose, without asking permission and without giving credit.

## Disclaimer

An independent educational project, dedicated to the public domain. It is not tax advice and is not affiliated with or endorsed by the IRS or any tax preparation company. Figures come from public IRS and federal sources; confirm them against current IRS instructions before preparing a return.
