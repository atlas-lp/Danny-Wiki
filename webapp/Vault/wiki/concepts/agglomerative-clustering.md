---
type: concept
aliases: [Agglomerative Clustering]
relationships:
  - target: linkage-criteria
    type: uses
  - target: dendrogram
    type: is-visualized-by
  - target: dbscan
    type: is_compared_to
  - target: clustering-algorithm
    type: is_a
  - target: dendrogram
    type: visualized_by
tags: [clustering, unsupervised-learning, hierarchical-clustering]
sourced_from: Introduction To Machine Learning With Python   A Guide For    Andreas C  MüLler And Sarah Guido    1 Content
---

# Agglomerative Clustering

A collection of hierarchical clustering algorithms that start with each point as its own cluster and iteratively merge the two most similar clusters until a specified number of clusters remain. A hierarchical clustering algorithm where, starting from the bottom, pairs of clusters are successively merged, a process which can be visualized with a dendrogram. A clustering algorithm that provides a hierarchy of possible data partitions, which can be specified by the number of desired clusters and visualized using dendrograms.

## Relationships

- **uses**: [[linkage-criteria|Linkage Criteria]]
- **is-visualized-by**: [[dendrogram|Dendrogram]]
- **is_compared_to**: [[dbscan|Dbscan]]
- **is_a**: [[clustering-algorithm|Clustering Algorithm]]
- **visualized_by**: [[dendrogram|Dendrogram]]

---
*Extracted from: Introduction To Machine Learning With Python   A Guide For    Andreas C  MüLler And Sarah Guido    1 Content*