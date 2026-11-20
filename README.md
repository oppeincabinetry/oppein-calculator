# OPPEIN Kitchen Calculator

Phone-friendly rough-quote calculator for OPPEIN cabinetry — the same
Calculator as the 2026–2027 combined order workbook, as a single web page.

**Live app:** https://oppeincabinetry.github.io/oppein-calculator/

Open it on a phone and use Share → Add to Home Screen ("OPPEIN Calc").

## What it does

Pick the line (Regular / GOLA), box material (GOLA is PB only), lowers and
uppers door colours, base / wall / tall linear feet and heights, RTA or
Assembled, and a dealer tier (A–H). It returns the itemized estimate, the
NET TOTAL, and the Price per Lft = NET ÷ (Base Lft + Tall Lft).

## Rates

`index.html` embeds the rate table in `rates.json`, computed from the
OPPEIN 2026–2027 order forms' Data base. Base and wall $/Lft come from a
fixed 10x10 cabinet list (with a 24" drawer base); the dealer discount
applies to the cabinet subtotal only — assembly is added after, at full
price. Rough quotes only: the itemized order form is the real quote.
