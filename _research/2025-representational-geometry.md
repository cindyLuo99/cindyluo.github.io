---
title: "Representational Geometry Dynamics in Networks After Long-Range Modulatory Feedback"
collaborators: "Kexin Cindy Luo, George A. Alvarez, Talia Konkle"
year: 2025
order: 1
links:
  - label: "CCN 2025"
    url: "/publication/2025-ccn-representational-geometry"
  - label: "Journal of Vision"
    url: "/publication/2025-jov-representational-geometry"
keywords: "feedback modulation, representational geometry, deep neural networks, category learning"
resources:
  - label: "Abstract"
    url: "https://2025.ccneuro.org/abstract_pdf/Luo_2025_Representational_Geometry_Dynamics_Networks_After_Long-Range.pdf"
  - label: "Code"
    url: "https://github.com/cindyLuo99/reprGeo_LRM.git"
---

 The human visual system employs extensive long-range feedback circuitry, where feedforward and feedback connections iteratively refine interpretations through reentrant loops (Di Lollo, 2012). Inspired by this neuroanatomy, a recent computational model incorporated long-range modulatory feedback into a convolutional neural network (Konkle & Alvarez, 2023). While this prior work focused on injecting an external goal signal to leverage feedback for category-based attention, here we investigated its default operation: how learned feedback intrinsically reshapes representational geometry without top-down goals. Analyzing activations from this model across two passes—feedforward versus modulated—on ImageNet data, we examined local (within-category) and global (between-category) structure. Our results demonstrate that feedback significantly compacts category clusters: exemplars move closer to prototypes, and the local structure improves as more near neighbors fall within the same category. Notably, this occurs while largely preserving global structure, as between-category distances remain relatively stable. An exploratory analysis linking local and global changes suggested a positive relationship between local compaction and prototype shifts. These findings reveal an emergent "prototype effect" where fixed long-range feedback automatically refines local representations, potentially enhancing categorical processing efficiency without disrupting overall representational organization. This suggests intrinsic feedback dynamics might contribute fundamentally to perceptual organization.


