<p align="center">
  <h1 align="center"> Leveraging Camera Triplets for Efficient and Accurate Structure-from-Motion
  <h2 align="center">
    <a href="https://scholar.google.co.in/citations?user=9UpkJwMAAAAJ">Lalit Manam</a>
    ·
    <a href="https://scholar.google.co.in/citations?hl=en&user=3De533YAAAAJ">Venu Madhav Govindu</a>
  </p>
  <h2 align="center"><p>
    <a href="https://openaccess.thecvf.com/content/CVPR2024/papers/Manam_Leveraging_Camera_Triplets_for_Efficient_and_Accurate_Structure-from-Motion_CVPR_2024_paper.pdf" align="center">Paper</a> | <a href="https://ee.iisc.ac.in/cvlab/research/camtripsfm/cam_triplets_sfm_supp.pdf" align="center">Suppl</a> | 
    <a href="https://ee.iisc.ac.in/cvlab/research/camtripsfm/" align="center">Project Page</a>
  </p></h2>
  <div align="center"></div>
</p>
<br/>
<p align="center">
    <img src="https://ee.iisc.ac.in/cvlab/images/projects/camtripsfm/Epipolar_inliers.png" alt="example" width=80%>
</p>

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


## BibTeX
If you find our models useful, please consider citing the paper!
```
@inproceedings{manam2024camtripsfm,
  title                    = {Leveraging Camera Triplets for Efficient and Accurate Structure-from-Motion},
  author                   = {Manam, Lalit and Govindu, Venu Madhav},
  booktitle                = {Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)},
  pages			   = {4959--4968},
  month			   = {June},
  year                     = {2024},
  organization             = {IEEE},
  Comment		   = {<a href="https://ee.iisc.ac.in/cvlab/research/camtripsfm/">[project page]</a>},
  url			   = {https://ee.iisc.ac.in/cvlab/research/camtripsfm/cam_triplets_sfm.pdf}
}
```
