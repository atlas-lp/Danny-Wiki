---
type: concept
aliases: [Billing Management System]
relationships:
  - target: pay-per-use-monitor
    type: uses_data_from
  - target: pay-per-use-measurements-repository
    type: contains
  - target: pricing-and-contract-manager
    type: contains
tags: [billing, cloud-management, system]
sourced_from: Cloud Computing  Concepts, Technology, Security, And    Thomas Erl, Eric Barcelo    2, 2023    Pears Content
---

# Billing Management System

A system that uses data from monitors to identify the range of usage fees applicable to each usage event based on categories like subscription type and resource usage. A system that defines pricing policies, calculates consolidated cloud service usage fees from collected data, and generates invoices for cloud consumers.

## Relationships

- **uses_data_from**: [[pay-per-use-monitor|Pay Per Use Monitor]]
- **contains**: [[pay-per-use-measurements-repository|Pay Per Use Measurements Repository]]
- **contains**: [[pricing-and-contract-manager|Pricing And Contract Manager]]

---
*Extracted from: Cloud Computing  Concepts, Technology, Security, And    Thomas Erl, Eric Barcelo    2, 2023    Pears Content*