---
type: concept
aliases: [Data Warehouse]
relationships:
  - target: star-schema
    type: uses_architecture
  - target: snowflake-schema
    type: uses_architecture
  - target: star-schema
    type: uses_design
  - target: etl
    type: is_updated_by
  - target: erp-system
    type: sources_data_from
  - target: data-mart
    type: is_related_to
tags: [database-systems, business-intelligence, data-analysis, data-management, it-infrastructure]
sourced_from: Data Analytics Made Accessible Content
---

# Data Warehouse

An organized store of data from all over an organization, specially designed with lower granularity to help make management decisions and perform analysis. A special data management facility intended for creating reports and analysis that simplifies data access for end users and does not burden operational databases.

## Relationships

- **uses_architecture**: [[star-schema|Star Schema]]
- **uses_architecture**: [[snowflake-schema|Snowflake Schema]]
- **uses_design**: [[star-schema|Star Schema]]
- **is_updated_by**: [[etl|Etl]]
- **sources_data_from**: [[erp-system|Erp System]]
- **is_related_to**: [[data-mart|Data Mart]]

---
*Extracted from: Data Analytics Made Accessible Content*