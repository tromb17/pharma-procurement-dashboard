# Pharma Procurement Dashboard

Demo portfolio project based on real procurement and inventory tasks
in a pharmaceutical company.

## Project overview

The goal of this project is to:

- analyse contract demand and shipment schedules;
- monitor current stock, overstock and potential non-liquid items;
- highlight risks (uncontracted stock, approaching expiry);
- prepare clean tables for reporting and Power BI dashboards.

All business data is anonymized: product names, manufacturers, customers
and monetary amounts are replaced with pseudonyms and normalized values
while preserving the structure and logic of analysis.

## Repository structure

- `notebooks/` – Jupyter Notebook with data loading, cleaning,
  feature engineering and metrics calculation for procurement and stock.
- `data/` – small demo CSV/Excel files with anonymized sample data
  that mirror the structure of real datasets.
- `images/` – screenshots of the Power BI dashboard and key tables.
- `README.md` – project description and usage notes.

## Tech stack

- Python, Pandas
- Jupyter Notebook / JupyterLab
- Excel
- Power BI (for the dashboard)

## What this project demonstrates

- End-to-end workflow: from raw ERP/1C-like exports to analytical tables.
- Calculation of demand, residuals, overstock and non-liquid inventory.
- Preparation of data model for Power BI dashboard.
