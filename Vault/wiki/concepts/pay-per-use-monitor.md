---
type: concept
aliases: [Pay-per-use Monitor]
relationships:
  - target: billing-management-system
    type: is_used_by
  - target: cloud-usage-monitor
    type: uses_data_from
  - target: billing-management-system
    type: provides_data_to
tags: [monitoring, billing, metering, mechanism]
sourced_from: Cloud Computing  Concepts, Technology, Security, And    Thomas Erl, Eric Barcelo    2, 2023    Pears Content
---

# Pay-per-use Monitor

A mechanism that tracks cloud service usage by receiving and logging "start," "stop," and "changed usage" events for billing purposes. A monitoring agent that tracks the usage of a cloud service and collects data relevant to billing, which is then forwarded to a billing management system.

## Relationships

- **is_used_by**: [[billing-management-system|Billing Management System]]
- **uses_data_from**: [[cloud-usage-monitor|Cloud Usage Monitor]]
- **provides_data_to**: [[billing-management-system|Billing Management System]]

---
*Extracted from: Cloud Computing  Concepts, Technology, Security, And    Thomas Erl, Eric Barcelo    2, 2023    Pears Content*