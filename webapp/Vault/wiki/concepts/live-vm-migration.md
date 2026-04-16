---
type: concept
aliases: [Live VM Migration]
relationships:
  - target: virtual-server
    type: acts_on
  - target: resource-cluster
    type: is_a_feature_of
  - target: non-disruptive-service-relocation-architecture
    type: is-used-by
  - target: virtual-infrastructure-manager-vim
    type: is-initiated-by
tags: [virtualization, cloud-management, scalability, high-availability, technique, process]
sourced_from: Cloud Computing  Concepts, Technology, Security, And    Thomas Erl, Eric Barcelo    2, 2023    Pears Content
---

# Live VM Migration

A feature of a virtualization platform that allows moving virtual servers among physical servers within the same data center to scale up in response to an increase in workload. A process where a virtualization platform suspends the execution of a virtual server on one physical server and resumes it on another, transparently to the virtual server's operating system. A process initiated by a VIM to dynamically move affected virtual servers to a new host when their current host hypervisor fails. A process to dynamically move a virtual server from one physical server to another at runtime, often triggered by a VIM to handle failures or load balancing.

## Relationships

- **acts_on**: [[virtual-server|Virtual Server]]
- **is_a_feature_of**: [[resource-cluster|Resource Cluster]]
- **is-used-by**: [[non-disruptive-service-relocation-architecture|Non Disruptive Service Relocation Architecture]]
- **is-initiated-by**: [[virtual-infrastructure-manager-vim|Virtual Infrastructure Manager Vim]]

---
*Extracted from: Cloud Computing  Concepts, Technology, Security, And    Thomas Erl, Eric Barcelo    2, 2023    Pears Content*