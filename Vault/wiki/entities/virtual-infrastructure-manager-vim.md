---
type: entity
aliases: [Virtual Infrastructure Manager (VIM)]
relationships:
  - target: hypervisor-cluster-architecture
    type: manages
  - target: live-vm-migration
    type: initiates
  - target: capacity-watchdog-monitor
    type: receives-reports-from
  - target: automated-scaling-listener
    type: is-signaled-by
tags: [component, management-plane, cloud-computing]
sourced_from: Cloud Computing  Concepts, Technology, Security, And    Thomas Erl, Eric Barcelo    2, 2023    Pears Content
---

# Virtual Infrastructure Manager (VIM)

A central component that manages a hypervisor cluster, receives reports from monitors, and initiates actions like live VM migration.

## Relationships

- **manages**: [[hypervisor-cluster-architecture|Hypervisor Cluster Architecture]]
- **initiates**: [[live-vm-migration|Live Vm Migration]]
- **receives-reports-from**: [[capacity-watchdog-monitor|Capacity Watchdog Monitor]]
- **is-signaled-by**: [[automated-scaling-listener|Automated Scaling Listener]]

---
*Extracted from: Cloud Computing  Concepts, Technology, Security, And    Thomas Erl, Eric Barcelo    2, 2023    Pears Content*