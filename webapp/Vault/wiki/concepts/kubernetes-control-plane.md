---
type: concept
aliases: [Kubernetes Control Plane]
relationships:
  - target: kubernetes-cluster
    type: manages
  - target: kubernetes-api
    type: contains
  - target: cloud-controller-manager
    type: contains
tags: [kubernetes, management, architecture-component]
sourced_from: Cloud Computing  Concepts, Technology, Security, And    Thomas Erl, Eric Barcelo    2, 2023    Pears Content
---

# Kubernetes Control Plane

A component in a Kubernetes cluster responsible for making decisions applicable to the entire cluster and providing a common set of tools for managing the nodes.

## Relationships

- **manages**: [[kubernetes-cluster|Kubernetes Cluster]]
- **contains**: [[kubernetes-api|Kubernetes Api]]
- **contains**: [[cloud-controller-manager|Cloud Controller Manager]]

---
*Extracted from: Cloud Computing  Concepts, Technology, Security, And    Thomas Erl, Eric Barcelo    2, 2023    Pears Content*