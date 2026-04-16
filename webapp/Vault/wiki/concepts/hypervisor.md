---
type: concept
aliases: [Hypervisor]
relationships:
  - target: hardware-based-virtualization
    type: is-a-key-component-of
  - target: virtualization
    type: enables
  - target: physical-server
    type: runs_on
  - target: technology-mechanisms
    type: is_a
  - target: virtual-server
    type: manages
tags: [virtualization, software, cloud-infrastructure]
sourced_from: Cloud Computing  Concepts, Technology, Security, And    Thomas Erl, Eric Barcelo    2, 2023    Pears Content
---

# Hypervisor

A thin layer of software in hardware-based virtualization that handles hardware management functions to establish a virtualization management layer for provisioning virtual servers. The component responsible for creating and running multiple virtual servers from a physical server by presenting emulated hardware to each guest operating system. A technology that can be installed directly on bare-metal servers and provides features for controlling, sharing, and scheduling the usage of hardware resources for virtual servers. A mechanism that allows physical hosts in a cloud environment to host virtual servers that are replicas of on-premise servers.

## Relationships

- **is-a-key-component-of**: [[hardware-based-virtualization|Hardware Based Virtualization]]
- **enables**: [[virtualization|Virtualization]]
- **runs_on**: [[physical-server|Physical Server]]
- **is_a**: [[technology-mechanisms|Technology Mechanisms]]
- **manages**: [[virtual-server|Virtual Server]]

---
*Extracted from: Cloud Computing  Concepts, Technology, Security, And    Thomas Erl, Eric Barcelo    2, 2023    Pears Content*