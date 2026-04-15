---
type: entity
aliases: [GroupBy Object]
relationships:
  - target: groupby-operations
    type: is_created_by
  - target: groupby
    type: created_by
tags: [pandas, software-component, api-object, data-structure]
sourced_from: Python For Data Analysis  Data Wrangling With Pandas, Numpy,    Wes Mckinney    2Nd, 2017    O Reill Content
---

# GroupBy Object

A pandas object that contains intermediate data about a group key and has all the information needed to apply an operation to each group. An object returned by the groupby method in pandas that contains the grouped information, on which aggregation or transformation operations can be performed.

## Relationships

- **is_created_by**: [[groupby-operations|Groupby Operations]]
- **created_by**: [[groupby|Groupby]]

---
*Extracted from: Python For Data Analysis  Data Wrangling With Pandas, Numpy,    Wes Mckinney    2Nd, 2017    O Reill Content*