---
type: entity
aliases: [Cloud Consumer]
relationships:
  - target: cloud-provider
    type: has-contract-with
  - target: cloud-service
    type: uses
  - target: cloud-provider
    type: has_contract_with
  - target: trust-boundary
    type: expands
tags: [role, organization, cloud-computing]
sourced_from: Cloud Computing  Concepts, Technology, Security, And    Thomas Erl, Eric Barcelo    2, 2023    Pears Content
---

# Cloud Consumer

The party, usually an organization, that uses cloud-based IT resources. An organization or human with a formal contract or arrangement to use IT resources made available by a cloud provider.

## Relationships

- **has-contract-with**: [[cloud-provider|Cloud Provider]]
- **uses**: [[cloud-service|Cloud Service]]
- **has_contract_with**: [[cloud-provider|Cloud Provider]]
- **expands**: [[trust-boundary|Trust Boundary]]

---
*Extracted from: Cloud Computing  Concepts, Technology, Security, And    Thomas Erl, Eric Barcelo    2, 2023    Pears Content*