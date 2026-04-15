---
type: concept
aliases: [Pod]
relationships:
  - target: container
    type: hosts
  - target: container
    type: contains
  - target: host
    type: is_deployed_on
  - target: sidecar-container
    type: can_contain
  - target: adapter-container
    type: can_contain
  - target: ambassador-container
    type: can_contain
tags: [containerization, orchestration, container-management]
sourced_from: Cloud Computing  Concepts, Technology, Security, And    Thomas Erl, Eric Barcelo    2, 2023    Pears Content
---

# Pod

A special type of system container, also known as a logical pod container, used to host one or more containers that share storage, network resources, and configuration. A group of one or more containers deployed on a single host that share resources such as the same IP address and file systems, and provides capabilities for orchestration and scaling. A deployment unit that can host multiple co-located containers, such as a main application container and its associated secondary utility containers.

## Relationships

- **hosts**: [[container|Container]]
- **contains**: [[container|Container]]
- **is_deployed_on**: [[host|Host]]
- **can_contain**: [[sidecar-container|Sidecar Container]]
- **can_contain**: [[adapter-container|Adapter Container]]
- **can_contain**: [[ambassador-container|Ambassador Container]]

---
*Extracted from: Cloud Computing  Concepts, Technology, Security, And    Thomas Erl, Eric Barcelo    2, 2023    Pears Content*