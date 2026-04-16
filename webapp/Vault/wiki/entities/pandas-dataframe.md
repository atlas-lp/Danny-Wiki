---
type: entity
aliases: [pandas DataFrame]
relationships:
  - target: pandas
    type: is_a_data_structure_in
  - target: pandas-series
    type: can_be_retrieved_as
  - target: pandas-index
    type: has
  - target: loc-operator
    type: is_indexed_by
  - target: iloc-operator
    type: is_indexed_by
tags: [pandas, data-structure]
sourced_from: Python For Data Analysis  Data Wrangling With Pandas, Numpy,    Wes Mckinney    2Nd, 2017    O Reill Content
---

# pandas DataFrame

A rectangular table of data in pandas that contains an ordered collection of columns, each of which can be a different value type, and has both a row and column index. A two-dimensional data structure in pandas that can be constructed from various inputs like a dict of Series and whose data is stored as a two-dimensional ndarray.

## Relationships

- **is_a_data_structure_in**: [[pandas|Pandas]]
- **can_be_retrieved_as**: [[pandas-series|Pandas Series]]
- **has**: [[pandas-index|Pandas Index]]
- **is_indexed_by**: [[loc-operator|Loc Operator]]
- **is_indexed_by**: [[iloc-operator|Iloc Operator]]

---
*Extracted from: Python For Data Analysis  Data Wrangling With Pandas, Numpy,    Wes Mckinney    2Nd, 2017    O Reill Content*