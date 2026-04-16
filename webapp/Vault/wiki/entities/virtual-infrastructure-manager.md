---
type: entity
aliases: [Virtual Infrastructure Manager (VIM)]
relationships:
  - target: virtual-server
    type: manages
  - target: automated-scaling-listener
    type: receives_commands_from
tags: [virtualization, management, software]
sourced_from: Cloud Computing  Concepts, Technology, Security, And    Thomas Erl, Eric Barcelo    2, 2023    Pears Content
---

# Virtual Infrastructure Manager (VIM)

A management platform that coordinates between data centers to overcome failures by reallocating virtual servers and executes scaling commands from automated listeners.

## Relationships

- **manages**: [[virtual-server|Virtual Server]]
- **receives_commands_from**: [[automated-scaling-listener|Automated Scaling Listener]]

---
*Extracted from: Cloud Computing  Concepts, Technology, Security, And    Thomas Erl, Eric Barcelo    2, 2023    Pears Content*