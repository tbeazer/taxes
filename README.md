# Taxes, Starting With Form 1040

A public-domain study guide to the U.S. individual income tax return. Every individual return starts with **Form 1040**, and nearly every other form or schedule feeds a number onto one of its lines. This repository maps those connections one tax year at a time, so it can grow as the tax code changes.

**Browse it:** open `index.html`, or turn on GitHub Pages (Settings → Pages → Deploy from a branch → `main`, `/ (root)`).

## What's here

| Folder | What it covers |
|---|---|
| [`questions/`](questions/) | Questions every taxpayer has to ask, grouped by life situation, each linked to the forms it leads to |
| [`resources/`](resources/) | Free IRS help for new filers and the VITA/TCE volunteer forms and guides, including the Form 13614-C intake sheet |
| [`form-1040/`](form-1040/) | How Form 1040 is organized, with one subfolder per tax year |
| [`form-1040/2026/`](form-1040/2026/) | Tax year 2026 (returns filed in 2027), built from the final 2026 IRS amounts and the IRS's draft 2026 forms |
| [`form-1040/2025/`](form-1040/2025/) | Tax year 2025 (returns filed in 2026): every common form, the 1040 line it feeds, 2025 limits, due diligence questions and links to the official IRS forms |
| [`form-1040/2024/`](form-1040/2024/) | Tax year 2024 (returns filed in 2025), a reference year from before the One Big Beautiful Bill Act changes |
| [`definitions/`](definitions/) | 158 tax terms, forms and schedules in plain English |

## How a Form 1040 flows

1. **Income** (lines 1–9): wages, interest, dividends, retirement income, capital gains, and other income from Schedule 1.
2. **Adjustments** (lines 10–11): above-the-line items from Schedule 1, Part II, subtracted to reach adjusted gross income (AGI).
3. **Deductions** (lines 12–15): the standard deduction or itemized deductions (Schedule A), plus the QBI deduction and Schedule 1-A deductions, to reach taxable income.
4. **Tax** (lines 16–18): tax from the Tax Table, plus additional taxes from Schedule 2, Part I.
5. **Credits and other taxes** (lines 19–24): nonrefundable credits (Schedule 8812, Schedule 3) reduce the tax; other taxes such as self-employment tax are added to reach total tax.
6. **Payments** (lines 25–33): withholding, estimated payments and refundable credits.
7. **Result** (lines 34–38): a refund if payments are more than total tax, or a balance due if less.

## Adding a new tax year

1. Copy the latest year's folder, for example `form-1040/2026/` to `form-1040/2027/`.
2. In the new `index.html`, update the figures and line numbers from that year's IRS forms, instructions and inflation adjustment revenue procedure. The script holds the base cards in `F`, the changes for that year in `PATCH` (edit a card, or `remove` it) and `ADD` (new cards), and the PDF link for each form in `LINKS`.
3. Update that folder's `README.md` source list.
4. Add the year to the table in [`form-1040/README.md`](form-1040/README.md) and to the year list in `index.html`.
5. If a new term appears, add it to `definitions/`.

## Sources

All content is based on public U.S. government sources: IRS forms, instructions, publications, revenue procedures and news releases, and federal law. Works of the U.S. government are not subject to copyright (17 U.S.C. § 105). Each tax year folder lists its specific sources.

## Public domain

This work is dedicated to the public domain under [CC0 1.0](LICENSE). Anyone may copy, change, share or use it for any purpose, without asking permission and without giving credit.

## Disclaimer

An independent educational project, dedicated to the public domain. It is not tax advice and is not affiliated with or endorsed by the IRS or any tax preparation company. Figures come from public IRS and federal sources; confirm them against current IRS instructions before preparing a return.
