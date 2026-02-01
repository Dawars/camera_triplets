# Leveraging Camera Triplets for Efficient and Accurate Structure-from-Motion

This step is run after two-view-geometry calculation.

Typical pipeline:
1) Feature extraction
2) Image matching
3) Two-view-geometry calculation (Fundamental matrix calculation)
4) `Camera Triplet scoring and view graph pruning`
5) Scene reconstruction

This prorotype is implemented in a Jupyer notebook.

Requirements:
- networkx
- pycolmap
- tqdm
