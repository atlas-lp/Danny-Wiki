---
type: concept
aliases: [Automated Scaling Listener]
relationships:
  - target: virtual-infrastructure-manager
    type: sends_commands_to
  - target: non-disruptive-service-relocation-architecture
    type: is-used-by
  - target: virtual-infrastructure-manager-vim
    type: signals
  - target: failover-system
    type: works_with
tags: [cloud-mechanism, scalability, monitoring, mechanism, auto-scaling, cloud-architecture, scaling, load-balancing, automation, workload-management]
sourced_from: Cloud Computing  Concepts, Technology, Security, And    Thomas Erl, Eric Barcelo    2, 2023    Pears Content
---

# Automated Scaling Listener

A service agent that monitors IT resources and automatically triggers scaling actions when usage crosses predefined thresholds or falls below allocated resources. A mechanism that monitors the workload for a cloud service and signals the VIM to initiate relocation when a pre-defined threshold is reached. A mechanism that controls cloud balancing by redirecting cloud service consumer requests to one of several redundant IT resource implementations based on current scaling and performance requirements. A mechanism used to watch and respond to workload fluctuations, for example by routing requests to local cloud service implementations.

## Relationships

- **sends_commands_to**: [[virtual-infrastructure-manager|Virtual Infrastructure Manager]]
- **is-used-by**: [[non-disruptive-service-relocation-architecture|Non Disruptive Service Relocation Architecture]]
- **signals**: [[virtual-infrastructure-manager-vim|Virtual Infrastructure Manager Vim]]
- **works_with**: [[failover-system|Failover System]]

---
*Extracted from: Cloud Computing  Concepts, Technology, Security, And    Thomas Erl, Eric Barcelo    2, 2023    Pears Content*