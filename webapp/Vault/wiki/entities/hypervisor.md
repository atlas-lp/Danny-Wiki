---
type: entity
aliases: [Hypervisor]
relationships:
  - target: virtualization
    type: enables
  - target: virtual-server
    type: creates
  - target: resource-replication
    type: example_of
  - target: virtual-server
    type: creates_and_manages
  - target: virtual-infrastructure-manager-vim
    type: is-managed-by
  - target: hypervisor-cluster-architecture
    type: is-a-component-of
  - target: lun
    type: manages
  - target: virtual-switch
    type: manages
tags: [software, virtualization, cloud-mechanism, component, cloud-component]
sourced_from: Cloud Computing  Concepts, Technology, Security, And    Thomas Erl, Eric Barcelo    2, 2023    Pears Content
---

# Hypervisor

Software, also known as a virtual machine manager (VMM), that is used to implement virtualization by creating and managing virtual machines. A software layer that creates virtual servers on a physical server. A virtualization platform program that creates and manages multiple instances of a virtual server by using a stored virtual server image. A system that hosts virtual servers and where workloads may require distribution between the hypervisor and the virtual servers it hosts. A component installed on a physical server that creates and runs virtual servers, and can be managed as part of a cluster by a VIM. A component that maps LUNs to virtual servers, processes and forwards storage requests, and provides virtual servers with access to the physical network.

## Relationships

- **enables**: [[virtualization|Virtualization]]
- **creates**: [[virtual-server|Virtual Server]]
- **example_of**: [[resource-replication|Resource Replication]]
- **creates_and_manages**: [[virtual-server|Virtual Server]]
- **is-managed-by**: [[virtual-infrastructure-manager-vim|Virtual Infrastructure Manager Vim]]
- **is-a-component-of**: [[hypervisor-cluster-architecture|Hypervisor Cluster Architecture]]
- **manages**: [[lun|Lun]]
- **manages**: [[virtual-switch|Virtual Switch]]

---
*Extracted from: Cloud Computing  Concepts, Technology, Security, And    Thomas Erl, Eric Barcelo    2, 2023    Pears Content*