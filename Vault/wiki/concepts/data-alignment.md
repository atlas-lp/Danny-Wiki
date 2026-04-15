---
type: concept
aliases: [Data Alignment]
relationships:
  - target: pandas-series
    type: is_a_feature_of
  - target: pandas-dataframe
    type: is_a_feature_of
tags: [pandas, data-processing, indexing, computation]
sourced_from: Python For Data Analysis  Data Wrangling With Pandas, Numpy,    Wes Mckinney    2Nd, 2017    O Reill Content
---

# Data Alignment

A feature of pandas Series where arithmetic operations automatically align data by index label, which is similar to a join operation in databases. An internal feature of pandas where arithmetic operations between objects align data on both row and column labels, introducing missing values in locations that don't overlap.

## Relationships

- **is_a_feature_of**: [[pandas-series|Pandas Series]]
- **is_a_feature_of**: [[pandas-dataframe|Pandas Dataframe]]

---
*Extracted from: Python For Data Analysis  Data Wrangling With Pandas, Numpy,    Wes Mckinney    2Nd, 2017    O Reill Content*