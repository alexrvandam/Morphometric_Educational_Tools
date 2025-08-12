# Morphometric_Educational_Tools
Simulate different morphological species scenarios for PCA clustering

How To Install and Run:
Simply download the .html file and then right click it and open in your browser.

Explore how morphological variation within and between species affects our ability
to cluster them via PCA and then assign new species via Mahanalobis Clustering
Explore how sample size affects the power of the features used to discriminate 
between species.


Once opened here is a brief, How to: Freeze PCA on your two well-sampled reference species (A, B), then project rare taxa and singletons into the same space. 
Use Mahalanobis distances with df = k PCs: specimens whose MD² exceed the χ² threshold for both A and B are flagged as outliers (candidate novelties). 
For small groups (n≈3–10), use Hotelling’s T² power: target ≥80% power by increasing per-group sample sizes, 
favoring a compact set of informative PCs (k≈3–6), or refining features to increase separation. 
The Energy test provides a nonparametric check of separation that complements T².
