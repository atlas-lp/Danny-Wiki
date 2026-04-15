---
type: entity
aliases: [datetime.datetime]
relationships:
  - target: datetime-timedelta
    type: produces
  - target: immutable-object
    type: is_a
  - target: timedelta
    type: used-to-calculate
tags: [python, datetime, data-types, python-standard-library, data-type]
sourced_from: Python For Data Analysis  Data Wrangling With Pandas, Numpy,    Wes Mckinney    2Nd, 2017    O Reill Content
---

# datetime.datetime

An immutable type in Python used for working with dates and times, which can be formatted into strings using `strftime` or parsed from strings using `strptime`. A widely used data type from the Python standard library that stores both date and time information down to the microsecond.

## Relationships

- **produces**: [[datetime-timedelta|Datetime Timedelta]]
- **is_a**: [[immutable-object|Immutable Object]]
- **used-to-calculate**: [[timedelta|Timedelta]]

---
*Extracted from: Python For Data Analysis  Data Wrangling With Pandas, Numpy,    Wes Mckinney    2Nd, 2017    O Reill Content*