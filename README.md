# Winery Demand and Materials Planning — GMU DAEN Capstone

Academic operations-planning project. The intended decision is how wine demand, inventory, production lead times,
and planned cases inform future wine production and fruit requirements.

## Repository status

**Spreadsheet artifacts are present; the Python forecasting pipeline is not recoverable from this repository.**
All four committed Python files are zero-byte placeholders. Running them produces no analysis and must not be reported as a successful forecast run.
No forecast accuracy, savings, deployment, or individual contribution is asserted from the files alone.

## Available evidence

| File | Contents inspected |
|---|---|
| `winery_forecast_1.xlsx` | Historical cases/inventory worksheets; `Crush_Calculator`; `Class1_MRP`, `Class2_MRP`, and `Class3_MRP` planning outputs |
| `case_planning.xlsx` | Vintage, winery, wine, and planned-case fields |
| `class_mapping (2).xlsx` | Wine-name-to-class mapping |
| `crush (1).py`, `data_extractor (7).py`, `demand_predictor (4).py`, `run_all (1).py` | Empty source placeholders |

The MRP sheets contain lead time, stock, demand, stockout, planning-goal, and status columns.
Those are relevant to materials and inventory planning, but cached spreadsheet outputs do not establish how a forecast was trained or evaluated.

## What is required to reproduce the original work

1. Restore the original nonempty source files or notebooks from the team archive.
2. Document source periods, units, missing-data treatment, and each contributor's actual responsibility.
3. Recover the training/test cutoff, forecasting methods, baselines, and evaluation results.
4. Reconcile forecast demand to inventory, lead times, planned cases, and fruit-conversion assumptions.
5. Document stakeholder feedback or adoption only if supported by records.

October 14 review: inspected the existing workbooks and confirmed all four scripts are empty.
The original spreadsheets were preserved. The forecasting pipeline could not be executed; no replacement forecast was invented.
