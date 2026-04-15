---
type: concept
aliases: [Hypervisor Cluster Architecture]
relationships:
  - target: virtual-infrastructure-manager-vim
    type: is-managed-by
  - target: hypervisor
    type: uses
  - target: logical-network-perimeter
    type: can-incorporate
  - target: resource-replication
    type: can-incorporate
tags: [architecture, cloud-computing, virtualization]
sourced_from: Cloud Computing  Concepts, Technology, Security, And    Thomas Erl, Eric Barcelo    2, 2023    Pears Content
---

# Hypervisor Cluster Architecture

An architecture where hypervisors on multiple physical servers are enabled as a cluster via a central VIM, sharing a cloud storage device for virtual server configuration files.

## Relationships

- **is-managed-by**: [[virtual-infrastructure-manager-vim|Virtual Infrastructure Manager Vim]]
- **uses**: [[hypervisor|Hypervisor]]
- **can-incorporate**: [[logical-network-perimeter|Logical Network Perimeter]]
- **can-incorporate**: [[resource-replication|Resource Replication]]

---
*Extracted from: Cloud Computing  Concepts, Technology, Security, And    Thomas Erl, Eric Barcelo    2, 2023    Pears Content*