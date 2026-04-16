---
type: entity
aliases: [Container]
relationships:
  - target: pod
    type: can_be_grouped_in
  - target: host
    type: is_deployed_on
  - target: container-engine
    type: is_managed_by
  - target: containerization-platform
    type: is_created_by
tags: [virtualization, software-deployment]
sourced_from: Cloud Computing  Concepts, Technology, Security, And    Thomas Erl, Eric Barcelo    2, 2023    Pears Content
---

# Container

An isolated environment that hosts a software program and provides only the subset of operating system resources required by that software, in contrast to a virtual server which provides a full OS.

## Relationships

- **can_be_grouped_in**: [[pod|Pod]]
- **is_deployed_on**: [[host|Host]]
- **is_managed_by**: [[container-engine|Container Engine]]
- **is_created_by**: [[containerization-platform|Containerization Platform]]

---
*Extracted from: Cloud Computing  Concepts, Technology, Security, And    Thomas Erl, Eric Barcelo    2, 2023    Pears Content*