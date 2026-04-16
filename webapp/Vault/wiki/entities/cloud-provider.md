---
type: entity
aliases: [Cloud Provider]
relationships:
  - target: cloud-consumer
    type: has-contract-with
  - target: cloud
    type: provides
  - target: cloud-consumer
    type: provides_services_to
  - target: cloud-shared-responsibility-model
    type: proposes
tags: [role, organization, cloud-computing]
sourced_from: Cloud Computing  Concepts, Technology, Security, And    Thomas Erl, Eric Barcelo    2, 2023    Pears Content
---

# Cloud Provider

The party, usually an organization, that provides cloud-based IT resources. The party that makes IT resources available for lease, either by owning the resources or by reselling resources leased from other providers.

## Relationships

- **has-contract-with**: [[cloud-consumer|Cloud Consumer]]
- **provides**: [[cloud|Cloud]]
- **provides_services_to**: [[cloud-consumer|Cloud Consumer]]
- **proposes**: [[cloud-shared-responsibility-model|Cloud Shared Responsibility Model]]

---
*Extracted from: Cloud Computing  Concepts, Technology, Security, And    Thomas Erl, Eric Barcelo    2, 2023    Pears Content*