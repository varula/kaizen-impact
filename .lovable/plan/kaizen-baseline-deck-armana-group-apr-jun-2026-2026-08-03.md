## Kaizen Baseline Deck — Armana Group (Apr–Jun 2026)

Build a management-ready PowerPoint from the uploaded baseline report + workbook. Inter typeface, tight/dark theme, no invented numbers — every figure traced to the PDF or the Excel sheets.

### Theme
- **Palette (tight/dark):** near-black canvas `0E1116`, elevated card `171C24`, hairline rule `2A313C`, primary accent amber `E9B949`, positive teal `3FBFA8`, alert red `E05252`, body text `C9D1DB`.
- **Typography:** Inter Black/Bold titles, Inter SemiBold labels, Inter Regular body. Titles 40pt, section headers 24pt, body 18–20pt, tables 12–14pt, chrome 11pt.
- **Motif:** thin amber left-edge rule plus a small uppercase kicker on every content slide; dark canvas throughout for a consistent premium feel.

### Slide flow (16 slides)
1. Title — Kaizen Baseline Report, 10 priority sewing lines, Apr–Jun 2026
2. Executive summary — 4 stat callouts (67.1% efficiency, 20.3% OT, 72.9% balancing, 36.7 min changeover) + 8-of-10 coverage note
3. Scope & method — volume-weighted KPIs, no imputation, 2,063 in-window records
4. Baseline KPI table — all 10 lines, "No data" shown as recorded
5. Efficiency by line — horizontal bars for the 8 valid lines with 75% target marker
6. Monthly efficiency trend — Apr / May / Jun series (Sheet 2)
7. Overtime vs efficiency — the cost leak; DTX:Floor-3:L12 at 45.5%, ZAL:Sonali:L4 at 23.7%
8. Line balancing gap — bars against the 85% standard, AAL:Floor-2:L8 at 51.7% called out
9. Changeover / SMED — 0–90 min spread, Mitali 20.2 min as the internal proof point
10. Line-wise analysis A — AAL lines (L3, L8, L9) verdict cards
11. Line-wise analysis B — ZAL, DML, SSL verdict cards
12. Composite ranking — ranked table with score and verdict
13. Improvement opportunities — the five blocks (#1 balancing → #5 data capture)
14. 90-day Kaizen targets — KPI / baseline / target / gain / priority / lever table
15. Data quality & validation — days, records and status per line, DTX critical gaps
16. Recommendation & Wave 1 — approve 8 lines, pilot ZAL:Mitali:L12 + AAL:Floor-2:L8, hold the two DTX lines

Speaker notes on every slide.

### Technical
- Generate with pptxgenjs (16:9), Inter set explicitly on all text, tables, chart axes, data labels and legends.
- Figures read directly from the workbook sheets (Baseline Summary, Monthly Trend, Kaizen Targets, Line-wise Targets) so they match source exactly.
- QA: validate the .pptx, convert to PDF, render every slide to JPG and inspect for overflow, contrast, chart labels and table clipping; fix and re-verify.
- Deliver as `Armana_Kaizen_Baseline_Apr-Jun2026.pptx`.
