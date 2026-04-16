---
type: concept
aliases: [Failover System]
relationships:
  - target: resource-replication
    type: uses
  - target: ha-cluster
    type: is_component_of
  - target: active-passive-configuration
    type: can_be_implemented_as
  - target: automated-scaling-listener
    type: informs
  - target: redundant-physical-connection-for-virtual-servers-architecture
    type: component_of
  - target: vim
    type: implemented_by
tags: [resiliency, high-availability, disaster-recovery, cloud-reliability, cloud-architecture, resilience, cloud-management, cloud-mechanism, networking]
sourced_from: Cloud Computing  Concepts, Technology, Security, And    Thomas Erl, Eric Barcelo    2, 2023    Pears Content
---

# Failover System

A system that provides a redundant IT resource to take over processing when an active IT resource becomes unavailable, commonly used for mission-critical programs. A system that monitors the operational status of IT resources, detects failure conditions, and redirects workloads away from failed instances to redundant or standby implementations. A mechanism that instills resiliency within an architecture by ensuring redundant IT resources are capable of cross-cloud failover in the event of a failure. A system used to detect and respond to cloud service failures, enabling failover to redundant cloud service implementations that are both within and across clouds. A mechanism that performs the transition from an unavailable primary uplink to a standby uplink to maintain network connectivity for virtual servers. A high-availability configuration of replicated IT resources, which can be implemented via standard VIM features to handle failures.

## Relationships

- **uses**: [[resource-replication|Resource Replication]]
- **is_component_of**: [[ha-cluster|Ha Cluster]]
- **can_be_implemented_as**: [[active-passive-configuration|Active Passive Configuration]]
- **informs**: [[automated-scaling-listener|Automated Scaling Listener]]
- **component_of**: [[redundant-physical-connection-for-virtual-servers-architecture|Redundant Physical Connection For Virtual Servers Architecture]]
- **implemented_by**: [[vim|Vim]]

---
*Extracted from: Cloud Computing  Concepts, Technology, Security, And    Thomas Erl, Eric Barcelo    2, 2023    Pears Content*