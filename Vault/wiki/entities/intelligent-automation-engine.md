---
type: entity
aliases: [Intelligent Automation Engine]
relationships:
  - target: dynamic-scalability-architecture
    type: is_a_component_of
  - target: automated-scaling-listener
    type: is_triggered_by
  - target: automated-scaling-listener
    type: triggered_by
tags: [cloud-mechanism, automation, scripting, networking]
sourced_from: Cloud Computing  Concepts, Technology, Security, And    Thomas Erl, Eric Barcelo    2, 2023    Pears Content
---

# Intelligent Automation Engine

A mechanism that automates administration tasks, such as resource allocation for scaling, by executing scripts that contain workflow logic. A component that uses scripts to dynamically allocate additional network bandwidth or ports when triggered by the automated scaling listener.

## Relationships

- **is_a_component_of**: [[dynamic-scalability-architecture|Dynamic Scalability Architecture]]
- **is_triggered_by**: [[automated-scaling-listener|Automated Scaling Listener]]
- **triggered_by**: [[automated-scaling-listener|Automated Scaling Listener]]

---
*Extracted from: Cloud Computing  Concepts, Technology, Security, And    Thomas Erl, Eric Barcelo    2, 2023    Pears Content*