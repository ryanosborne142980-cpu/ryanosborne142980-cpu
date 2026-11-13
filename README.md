# Ryan Osborne

Data engineer with 18+ years in IT across data engineering, data governance, and business analysis. I design and build data pipelines, warehouses, and the governance around them, so that the numbers people report on can be trusted. Based in the Columbus, OH area.

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

## Domain experience

Financial services, reinsurance, and credit card operations. Across those I have worked on financial reconciliation, reporting automation, and data quality at scale.

## Background

B.S. in Journalism, Bowling Green State University. I moved from product support and business analysis into data governance and then data engineering, which is why I care as much about documenting and testing data as I do about moving it.

## Connect

[LinkedIn](https://www.linkedin.com/in/ryan-osborne-20306014)
