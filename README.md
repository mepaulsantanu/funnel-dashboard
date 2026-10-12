# E-Commerce Funnel Performance Dashboard

Load any e-commerce dataset and get a cleaned, interactive funnel dashboard. Everything runs in the browser.

## Use it
- Open the site and drop in a CSV, Excel (.xlsx/.xls) or JSON file.
- Or paste a Google Sheets link (File > Share > Publish to web > CSV works best).
- Or copy cells from Excel and paste them on the start page.
- Add `?sample` to the URL to load the demo dataset.
- Add `?data=<link>` to the URL to open a dataset straight from a link.

## What it does on its own
Finds the header row, removes blank, total and notes rows, converts text to numbers (₹, commas, %, lakh, crore), reads mixed date formats, merges messy labels (for example "fb ads" and "Meta Ads" become "Paid Social"), removes duplicates, fills gaps, flags outliers, and writes a cleaning log and data dictionary.

## Tabs
Overview, Funnel, Channels, Trends, Statistics, Data quality, Data, Custom charts.

## Customise it
- Custom charts: 16 chart types (column, bar, line, area, stacked, 100% stacked, combo, pie, donut, scatter, heatmap, funnel, treemap, scorecard, gauge, table). Pick the dimension, breakdown, metrics, sort, top N, colours, labels and width. Drag cards to reorder.
- Calculated metrics: write formulas like {revenue} - {ad_spend}.
- Funnel: hide or rename steps, switch between flow, bars and pyramid, and change colours.
- Colour themes for every chart.

Settings are saved in the browser you use.

## Exports
Excel workbook (cleaned data, data dictionary, cleaning log, funnel, KPIs, breakdowns, descriptive stats), cleaned CSV, data dictionary CSV, cleaning log, and PDF via print.
