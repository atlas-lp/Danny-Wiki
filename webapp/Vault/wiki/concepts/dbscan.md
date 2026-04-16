---
type: concept
aliases: [DBSCAN]
relationships:
  - target: clustering
    type: is_a
  - target: core-sample
    type: identifies
  - target: boundary-point
    type: identifies
  - target: noise-point
    type: identifies
  - target: agglomerative-clustering
    type: is_an_alternative_to
  - target: standard-scaler
    type: benefits_from_preprocessing_with
  - target: clustering-algorithm
    type: is_a
  - target: k-means
    type: contrasted_with
tags: [clustering, unsupervised-learning, density-based-algorithm]
sourced_from: Introduction To Machine Learning With Python   A Guide For    Andreas C  MüLler And Sarah Guido    1 Content
---

# DBSCAN

A density-based clustering algorithm (Density-Based Spatial Clustering of Applications with Noise) that does not require the user to set the number of clusters and can identify clusters of complex shapes. A clustering algorithm that defines proximity using the `eps` parameter, can detect noise points, and allows for complex cluster shapes and varying cluster sizes.

## Relationships

- **identifies**: [[core-sample|Core Sample]]
- **identifies**: [[boundary-point|Boundary Point]]
- **identifies**: [[noise-point|Noise Point]]
- **is_an_alternative_to**: [[agglomerative-clustering|Agglomerative Clustering]]
- **benefits_from_preprocessing_with**: [[standard-scaler|Standard Scaler]]
- **is_a**: [[clustering-algorithm|Clustering Algorithm]]
- **contrasted_with**: [[k-means|K Means]]

---
*Extracted from: Introduction To Machine Learning With Python   A Guide For    Andreas C  MüLler And Sarah Guido    1 Content*

---
*Also referenced in: ǂThe ǂHundred Page Machine Learning Book    Andriy Burkov    Lugar De PublicacióN No Identificado, 2 Content*