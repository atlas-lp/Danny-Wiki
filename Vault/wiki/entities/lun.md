---
type: entity
aliases: [Logical Unit Number (LUN)]
relationships:
  - target: cloud-storage-device
    type: hosted_on
  - target: hypervisor
    type: managed_by
tags: [storage, virtualization]
sourced_from: Cloud Computing  Concepts, Technology, Security, And    Thomas Erl, Eric Barcelo    2, 2023    Pears Content
---

# Logical Unit Number (LUN)

A logical unit of RAW block-based storage created on a cloud storage device that can be mapped directly to virtual servers by a hypervisor.

## Relationships

- **hosted_on**: [[cloud-storage-device|Cloud Storage Device]]
- **managed_by**: [[hypervisor|Hypervisor]]

---
*Extracted from: Cloud Computing  Concepts, Technology, Security, And    Thomas Erl, Eric Barcelo    2, 2023    Pears Content*