---
type: entity
aliases: [Virtual Server]
relationships:
  - target: hypervisor
    type: is_created_by
  - target: host
    type: is_a_type_of
  - target: hypervisor
    type: created_by
tags: [virtualization, infrastructure, it-resource]
sourced_from: Cloud Computing  Concepts, Technology, Security, And    Thomas Erl, Eric Barcelo    2, 2023    Pears Content
---

# Virtual Server

A virtual version of a physical server's entire operating system, created by a hypervisor, which can act as a host. A replicated instance of a server created from a virtual server image by a hypervisor and run on a physical server.

## Relationships

- **is_created_by**: [[hypervisor|Hypervisor]]
- **is_a_type_of**: [[host|Host]]
- **created_by**: [[hypervisor|Hypervisor]]

---
*Extracted from: Cloud Computing  Concepts, Technology, Security, And    Thomas Erl, Eric Barcelo    2, 2023    Pears Content*