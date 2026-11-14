# Ryan Osborne

Data engineer with 18+ years in IT across data engineering, data governance, and business analysis. 

## What I do

- **Data engineering:** build and automate ETL/ELT pipelines, including an on-prem SQL Server to Azure Synapse migration, and the pipelines behind production Power BI reporting
- **Data modeling and warehousing:** dimensional models, reconciliation logic, and data quality checks
- **Data governance:** data lineage, data dictionaries, business glossaries, and quality rules for critical data elements
- **Business analysis:** turning stakeholder requirements into specs developers can build from

## Tech

| Area | Tools |
|---|---|
| Languages | SQL (T-SQL), Python |
| Azure | Synapse, Data Factory, ADLS, Azure DevOps (CI/CD) |
| Platforms | SQL Server, Databricks, Snowflake, Microsoft Fabric |
| Governance | Collibra, Informatica, IBM Cloud Pak |
| Reporting | Power BI |

## Projects

- **[columbus_housing](https://github.com/ryanosborne142980-cpu/columbus_housing)**: Weekly pipeline that turns Franklin County's home-sale report pages into parcel-level sales data, checked against the county's own counts. Python and SQL Server load the data, Databricks holds bronze and silver tables, a 23-rule quality gate stops bad data before it lands, and GitHub Actions runs the tests against a real SQL Server on every pull request.
- **[nfl-injury-analyzer](https://github.com/ryanosborne142980-cpu/nfl-injury-analyzer)**: In progress. A dimensional warehouse of NFL player availability and injuries since 2010, built from nflverse data on SQL Server. The extract and raw-layer load are built and tested. Staging, dimensions, and facts are next.

## Selected files

- [Data quality rules](https://github.com/ryanosborne142980-cpu/columbus_housing/blob/main/pipeline/quality.py) — source-count, volume, and record-consistency checks.
- [SQL Server schema](https://github.com/ryanosborne142980-cpu/columbus_housing/blob/main/sql/schema.sql) — landing and cleaned data tables.
- [Source data profile](https://github.com/ryanosborne142980-cpu/nfl-injury-analyzer/blob/main/docs/data_profile.md) — measured findings that drive staging rules.
- [Data extraction](https://github.com/ryanosborne142980-cpu/nfl-injury-analyzer/blob/main/src/ingestion/extract.py) — retry-aware downloads with checksums and manifests.

## Planned learning work

- **Ingest and move:** batch/API ingestion, streaming, migration, orchestration, and backfills
- **Store and transform:** lakehouse design, incremental processing, and warehouse modeling
- **Trust and operate:** data contracts, quality checks, observability, governance, lineage, security, and privacy
- **Serve and optimize:** semantic layers, downstream interfaces, performance, cost, and deployment automation

These are planned demonstrations, not completed projects. [See the roadmap](https://ryanosborne142980-cpu.github.io/#roadmap).

## Domain experience

Financial services, reinsurance, and credit card operations. Across those I have worked on financial reconciliation, reporting automation, and data quality at scale.

## Connect

[Portfolio](https://ryanosborne142980-cpu.github.io) | [LinkedIn](https://www.linkedin.com/in/ryan-osborne-20306014)
