---
type: concept
aliases: [Resource Replication]
relationships:
  - target: virtualization
    type: is-a-feature-of
  - target: failover-system
    type: is_used_by
  - target: hypervisor-cluster-architecture
    type: is-used-by
  - target: load-balanced-virtual-server-instances-architecture
    type: is-used-by
  - target: storage-replication
    type: complements
  - target: hypervisor
    type: uses
tags: [virtualization, data-management, resiliency, cloud-mechanism, availability, replication, high-availability, mechanism, cloud-architecture, disaster-recovery]
sourced_from: Cloud Computing  Concepts, Technology, Security, And    Thomas Erl, Eric Barcelo    2, 2023    Pears Content
---

# Resource Replication

A feature of virtualization that allows for easy replication, migration, and backup of a virtual server by performing simple file operations on its virtual disk image. A parent mechanism representing different types of software programs capable of replicating IT resources, such as virtual servers or cloud storage devices. A mechanism utilized by failover systems to provide redundant instances of an IT resource that are actively monitored for errors and unavailability conditions. A mechanism used in clustered environments to replicate updates, status, and availability information or to instantiate copies of cloud services across different hosts. A mechanism used to create and maintain synchronized duplicate virtual instances of physical infrastructure in a cloud environment.

## Relationships

- **is-a-feature-of**: [[virtualization|Virtualization]]
- **is_used_by**: [[failover-system|Failover System]]
- **is-used-by**: [[hypervisor-cluster-architecture|Hypervisor Cluster Architecture]]
- **is-used-by**: [[load-balanced-virtual-server-instances-architecture|Load Balanced Virtual Server Instances Architecture]]
- **complements**: [[storage-replication|Storage Replication]]
- **uses**: [[hypervisor|Hypervisor]]

---
*Extracted from: Cloud Computing  Concepts, Technology, Security, And    Thomas Erl, Eric Barcelo    2, 2023    Pears Content*