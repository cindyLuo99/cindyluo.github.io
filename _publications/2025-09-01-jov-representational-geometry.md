---
title: "Representational Geometry Dynamics in Networks After Long-Range Modulatory Feedback (journal version)"
collection: publications
category: manuscripts
permalink: /publication/2025-jov-representational-geometry
excerpt: 'Journal of Vision, 25(9), 2343.'
date: 2025-09-01
venue: 'Journal of Vision'
is_duplicate_of: '/publication/2025-ccn-representational-geometry'
authors: 'Kexin Cindy Luo, George A. Alvarez, Talia Konkle'
paperurl: 'https://doi.org/10.1167/jov.25.9.2343'
citation: 'Luo, K. C., Alvarez, G., & Konkle, T. (2025). Representational geometry dynamics in networks after long-range modulatory feedback. <i>Journal of Vision</i>, <i>25</i>(9), 2343.'
---

 The human visual system relies on extensive long-range feedback circuitry, where feedforward and feedback connections iteratively refine interpretations through reentrant loops (Di Lollo, 2012). Inspired by this neuroanatomy, a recent model introduced long-range feedback pathways into a convolutional neural network, where late-stage feature channels learn how to influence early-stage channels, to support successful object classification (Konkle & Alvarez, 2023). The model operates in two passes—a feedforward pass, generating initial representations, and a modulated pass, where activations reflect both the feedforward and feedback-modulatory processing. While prior work focused on injecting an external goal signal into the model to leverage feedback connections for category-based attention, here we examine the representational dynamics of this model during its default operation, without any top-down goals. Specifically, we explored how the representational geometry of exemplars and categories changes in the modulated pass, relative to the feedforward pass. We analyzed activations from 100 randomly selected ImageNet categories (300 images each). Local representational structure was evaluated through cluster sizes and k-nearest neighbor analysis, while global representational structure was assessed via prototype shifts and pairwise distances within and between categories. We found that default feedback modulation induced notable changes in representational geometry: Category cluster sizes significantly reduce as exemplar embeddings move closer to category prototypes. Locally, more nearest neighbors fall within the same category, and within-category distances decrease, reflecting tighter clustering. Meanwhile, the distances between categories remain relatively stable. Finally, the larger the prototype shift, the greater the cluster shrinkage, indicating a relationship between internal cohesion and global repositioning. These findings suggest that fixed long-range feedback connections induce an automatic prototype effect in the representational geometry, compacting clusters within categories while preserving global structure. Broadly, these emergent feedback dynamics might naturally induce categorical processing effects by refining local representations without disrupting overall structure, improving downstream category-based task efficiency.


