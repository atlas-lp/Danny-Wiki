---
type: entity
aliases: [Storage Management Program]
relationships:
  - target: automated-scaling-listener
    type: triggered_by
  - target: lun-migration
    type: performs
tags: [storage-management, automation, cloud-mechanism]
sourced_from: Cloud Computing  Concepts, Technology, Security, And    Thomas Erl, Eric Barcelo    2, 2023    Pears Content
---

# Storage Management Program

A program that initiates LUN migration between different storage devices or internal disk tiers based on performance categories and notifications from an automated scaling listener.

## Relationships

- **triggered_by**: [[automated-scaling-listener|Automated Scaling Listener]]
- **performs**: [[lun-migration|Lun Migration]]

---
*Extracted from: Cloud Computing  Concepts, Technology, Security, And    Thomas Erl, Eric Barcelo    2, 2023    Pears Content*