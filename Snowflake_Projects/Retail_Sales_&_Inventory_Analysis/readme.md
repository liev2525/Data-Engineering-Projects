# Retail Sales & Inventory Analytics Platform on Microsoft Fabric

## Business Objective
Create a modern analytics pipeline that turns raw retail files into trusted dashboards for management.

## Business Scenario
A mid-sized retail company receives daily CSV files from stores containing:
- sales transactions
- product master data
- store master data
- inventory snapshots
###The business wants one trusted reporting layer for:
- daily sales by store and product
- inventory on hand
- low-stock alerts
- top-selling categories
- month-to-date revenue and margin trends

## Functional Requirements
- Ingest raw CSV files into Microsoft Fabric daily.
- Store raw data in a Bronze layer without major transformation.
- Clean and standardize data into a Silver layer.
- Build analytics-ready fact and dimension tables in a Gold layer.
- Support Power BI dashboards for leadership.
- Track pipeline success/failure.
- Validate schema and data quality before publishing curated data.
- Version-control pipeline code and deployment scripts in GitLab.
- Containerize local development so the project runs consistently on Ubuntu.

## Non-functional Requirements
- Re-runnable pipeline without breaking prior data.
- Clear folder/repo structure for portfolio presentation.
- Basic security via environment variables and secrets.
- Easy promotion from dev to prod later.
- Maintainable documentation and diagram.

## Success Metrics
- Daily data load completes successfully
- Duplicate records below target threshold
- Dashboard refresh available same day
- Manual Excel prep time reduced significantly
- Clear lineage from raw file to report

## Tech Stack
- Microsoft Fabric
- Fabric Data Factory
- Lakehouse
- PySpark notebooks
- Power BI
- GitLab CI/CD
- Docker
- Ubuntu
- Python
- SQL

## Key Engineering Features
- Bronze/Silver/Gold architecture
- data quality validation
- CI/CD pipeline
- Dockerized local testing
- semantic model reporting

