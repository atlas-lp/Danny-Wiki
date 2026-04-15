---
type: concept
aliases: [Ambassador Container]
relationships:
  - target: multi-container-types
    type: is_a_type_of
  - target: pod
    type: is_deployed_in
tags: [containerization, design-pattern]
sourced_from: Cloud Computing  Concepts, Technology, Security, And    Thomas Erl, Eric Barcelo    2, 2023    Pears Content
---

# Ambassador Container

A multi-container pattern where a separate container in the same pod handles external communication logic, such as protocols and security, to decouple the main application from external services.

## Relationships

- **is_a_type_of**: [[multi-container-types|Multi Container Types]]
- **is_deployed_in**: [[pod|Pod]]

---
*Extracted from: Cloud Computing  Concepts, Technology, Security, And    Thomas Erl, Eric Barcelo    2, 2023    Pears Content*