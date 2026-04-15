---
type: concept
aliases: [Customized Container Image]
relationships:
  - target: container-image
    type: is_a_type_of
  - target: base-container-image
    type: created_from
  - target: base-container-image
    type: is_built_from
  - target: container-build-file
    type: is_specified_by
  - target: container-image-layers
    type: is_composed_of
  - target: container-engine
    type: is_created_by
tags: [containerization, packaging, image-management]
sourced_from: Cloud Computing  Concepts, Technology, Security, And    Thomas Erl, Eric Barcelo    2, 2023    Pears Content
---

# Customized Container Image

A container image created by a container engine from a base image, which is then used to create actual, deployed containers. A container image created from a base image with additional layers to provide a customized and optimized hosting environment for specific software programs.

## Relationships

- **is_a_type_of**: [[container-image|Container Image]]
- **created_from**: [[base-container-image|Base Container Image]]
- **is_built_from**: [[base-container-image|Base Container Image]]
- **is_specified_by**: [[container-build-file|Container Build File]]
- **is_composed_of**: [[container-image-layers|Container Image Layers]]
- **is_created_by**: [[container-engine|Container Engine]]

---
*Extracted from: Cloud Computing  Concepts, Technology, Security, And    Thomas Erl, Eric Barcelo    2, 2023    Pears Content*