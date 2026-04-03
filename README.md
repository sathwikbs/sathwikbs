# Sathwik BS

Data Engineer specializing in Data Vault 2.0 and Kimball dimensional modeling.

I build tools that bridge the gap between raw data ingestion and business-ready analytics — making it easier for data teams to go from source systems to star schemas without losing auditability or flexibility.

## What I'm working on

**[automate-dv-kimball](https://github.com/sathwikbs/automate-dv-kimball)** — A dbt package that generates Kimball dimensional models on top of Data Vault 2.0 raw vaults. 6 macros, 5 platform adapters, 18 generic tests, and an AI skill that guides developers through DV2-to-Kimball mapping.

**[automate-dv-kimball-sample](https://github.com/sathwikbs/automate-dv-kimball-sample)** — A complete working pipeline from raw source data through staging, DV2 raw vault, business vault, Kimball star schema, and MetricFlow semantic layer. 93 models, 348 tests, 11 metrics.

## Domain expertise

- Data Vault 2.0 — hubs, links, satellites, effectivity satellites, multi-active satellites, PIT, bridge, XTS
- Kimball dimensional modeling — SCD types 1/2, transaction facts, periodic/accumulating snapshots, factless facts, conformed dimensions, bus matrix architecture
- dbt — macro development, multi-platform adapter dispatch, generic tests, MetricFlow semantic layer
- Warehouse platforms — Databricks, Snowflake, BigQuery, PostgreSQL, SQL Server

## Approach

Keep the raw vault auditable. Keep the star schema simple. Let the macros handle the plumbing so modelers can focus on the business logic.
